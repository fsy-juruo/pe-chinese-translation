### [869. Prime Guessing](https://projecteuler.net/problem=869)

A prime is drawn uniformly from all primes not exceeding $N$. The prime is written in binary notation, and a player tries to guess it bit-by-bit starting at the least significant bit. The player scores one point for each bit they guess correctly. Immediately after each guess, the player is informed whether their guess was correct, and also whether it was the last bit in the number - in which case the game is over.

Let $E(N)$ be the expected number of points assuming that the player always guesses to maximize their score. For example, $E(10)=2$, achievable by always guessing "1". You are also given $E(30)=2.9$.

Find $E(10^8)$. Give your answer rounded to eight digits after the decimal point.

### 869. 猜测质数

我们将从全体 $\leq N$ 的质数中均匀随机地抽出一个质数。随后，我们把这个质数用二进制表示，而玩家将从其最低有效位开始，逐位猜测这个质数。玩家每猜对该质数二进制表示中的一位，就能得一分。玩家一旦作出猜测，就会立刻知道本次猜测是否正确，以及是否已经猜到这个质数的最高位；如果是，那么游戏即刻结束。

记 $E(N)$ 为：当玩家使用能最大化得分的策略进行猜测时，其得分的期望值。例如，$E(10) = 2$，这可以通过采取 “不断猜测当前二进制位是 $1$” 的策略得到。你已知 $E(30) = 2.9$。

求 $E(10^8)$，并将答案四舍五入至小数点后第 8 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
