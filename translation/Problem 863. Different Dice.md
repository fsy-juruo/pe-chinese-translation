### [863. Different Dice](https://pe.xiaoyaowudi.com/problem=863)

Using only a six-sided fair dice and a five-sided fair dice, we would like to emulate an $n$-sided fair dice.

For example, one way to emulate a 28-sided dice is to follow this procedure:
1. Roll both dice, obtaining integers $1\le p\le 6$ and $1\le q\le 5$.
2. Combine them using $r = 5(p-1) + q$ to obtain an integer $1\le r\le 30$.
3. If $r\le 28$, return the value $r$ and stop.
4. Otherwise ($r$ being 29 or 30), roll both dice again, obtaining integers $1\le s\le 6$ and $1\le t\le 5$.
5. Compute $u = 30(r-29) + 5(s-1) + t$ to obtain an integer $1\le u\le 60$.
6. If $u > 4$, return the value $((u-5)\bmod 28) + 1$ and stop.
7. Otherwise (with $1\le u\le 4$), roll the six-sided dice twice, obtaining integers $1\le v\le 6$ and $1\le w\le 6$.
8. Compute $x = 36(u-1) + 6(v-1) + w$ to obtain an integer $1\le x\le 144$.
9. If $x > 4$, return the value $((x-5)\bmod 28) + 1$ and stop.
10. Otherwise (with $1\le x\le 4$), assign $u:=x$ and go back to step 7.

The expected number of dice rolls in following this procedure is 2.142476 (rounded to 6 decimal places). Note that rolling both dice at the same time is still counted as two dice rolls.

There exist other more complex procedures for emulating a 28-sided dice that entail a smaller average number of dice rolls. However, the above procedure has the attractive property that the sequence of dice rolled is predetermined: regardless of the outcome, it follows (D5,D6,D5,D6,D6,D6,D6,...), truncated wherever the process stops. In fact, amongst procedures for $n=28$ with this restriction, this one is optimal in the sense of minimising the expected number of rolls needed.

Different values of $n$ will in general use different predetermined sequences. For example, for $n=8$, the sequence (D5,D5,D5,...) gives an optimal procedure, taking 2.083333... dice rolls on average.

Define $R(n)$ to be the expected number of dice rolls for an optimal procedure for emulating an $n$-sided dice using only a five-sided and a six-sided dice, considering only those procedures where the sequence of dice rolled is predetermined. So, $R(8) \approx 2.083333$ and $R(28) \approx 2.142476$.

Let $S(n) = \displaystyle\sum_{k=2}^n R(k)$. You are given that $S(30) \approx 56.054622$.

Find $S(1000)$. Give your answer rounded to 6 decimal places.

### 863. 不同的骰子

我们可以用一枚六面体公平骰子和一枚五面体公平骰子来模拟一枚 $n$ 面体公平骰子。譬如，我们可以通过如下 10 步操作模拟一个二十八面体公平骰子：

1. 同时掷两枚骰子，其点数分别记为 $p, q (1 \leq p \leq 6, 1 \leq q \leq 5)$。
2. 计算 $r = 5(p - 1) + q$。
3. 如果 $r \le 28$，那么模拟出的点数即为 $r$，过程终止。
4. 否则，再次同时掷两枚骰子，新掷出的点数分别为 $s, t (1 \leq s \leq 6, 1 \leq t \leq 5)$。
5. 计算 $u = 30(r - 29) + 5(s - 1) + t$。
6. 如果 $u > 4$，那么模拟出的点数即为 $((u-5) \bmod 28) + 1$，过程终止。
7. 否则，掷两次六面体公平骰子，两次掷出的点数分别为 $v, w (1 \leq v, w \leq 6)$。
8. 计算 $x = 36(u - 1) + 6(v - 1) + w$。
9. 如果 $x > 4$，那么模拟出的点数即为 $((x-5) \bmod 28) + 1$，过程终止。
10. 否则命 $u := x$ 并回到第 7 步。

这个模拟方法期望需要掷 2.142476 次骰子（四舍五入至小数点后 6 位）。注意同时掷两枚骰子算作两次掷骰。

当然，还存在某些更复杂的模拟方法，可以在更少的期望掷骰次数内模拟一枚二十八面体公平骰子。但上述过程有一个迷人的特点：掷骰序列是固定的。不论最终模拟出的点数如何，这个过程的掷骰序列只会是 (D5, D6, D5, D6, D6, D6, D6...) 的一段前缀（其中 D5 指五面体公平骰子，D6 同理）。事实上，倘若加上「掷骰序列是固定的」这一限制，那么这个方法就是所有符合要求的模拟方法中，期望掷骰次数最小的。

当然，随着 $n$ 的变化，我们通常需要更换掷骰序列。如 $n = 8$ 时，掷骰序列 (D5, D5, D5...) 是最优的。其期望掷骰次数为 2.083333（四舍五入至小数点后 6 位）。

记 $R(n)$ 为：在只使用一枚六面体公平骰子和一枚五面体公平骰子，且固定掷骰序列时，在最优方案下，期望掷骰次数的最小值。故 $R(8) \approx 2.083333$、$R(28) \approx 2.142476$。再记 $S(n) = \displaystyle\sum_{k=2}^n R(k)$。已知 $S(30) \approx 56.054622$。

求 $S(1000)$。将你的答案四舍五入至小数点后第 6 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。