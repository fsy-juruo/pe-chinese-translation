
### [941. de Bruijn's Combination Lock](https://projecteuler.net/problem=941)

de Bruijn has a digital combination lock with $k$ buttons numbered $0$ to $k-1$ where $k \le 10$.  
The lock opens when the last $n$ buttons pressed match the preset combination.

Unfortunately he has forgotten the combination. He creates a sequence of these digits which contains every possible combination of length $n$. Then by pressing the buttons in this order he is sure to open the lock.

Consider all sequences of shortest possible length that contains every possible combination of the digits.  
Denote by $C(k, n)$ the lexicographically smallest of these.

For example, $C(3, 2) = $ 0010211220.

Define the sequence $a_n$ by $a_0=0$ and  
$$
a_n=(920461 a_{n-1}+800217387569)\bmod 10^{12} \text{ for }\  n > 0
$$
Interpret each $a_n$ as a $12$-digit combination, adding leading zeros for any $a_n$ with less than $12$ digits.

Given a positive integer $N$, we are interested in the order the combinations $a_1,\dots,a_N$ appear in $C(10,12)$.  
Denote by $p_n$ the *place*, numbered $1,\dots,N$, in which $a_n$ appears out of $a_1,\dots,a_N$. Define $\displaystyle F(N)=\sum_{n=1}^Np_na_n$.

For example, the combination $a_1=800217387569$ is entered before $a_2=696996536878$. Therefore:
$$
F(2)=1\cdot800217387569 + 2\cdot696996536878 = 2194210461325
$$
You are also given $F(10)=32698850376317$.

Find $F(10^7)$. Give your answer modulo $1234567891$.

### 941. 德布鲁因的密码锁

德布鲁因有一个数字密码锁。锁上有 $k \leq 10$ 个按钮，它们分别被编号为 $0$ 至 $k - 1$。若要打开此锁，那么最后按下的 $n$ 个按钮必须与预设的按钮组合相同。

不幸的是，他忘记了预设的按钮组合。为此，他构造了一个包含了所有长度为 $n$ 的按钮组合的序列。随后，只要顺序按下该序列中的按钮，他就能打开此锁。

考虑所有最短的、包含了所有长度为 $n$ 的按钮组合的序列，记其中字典序最小的一个序列为 $C(k, n)$。例如：$C(3, 2) = $ 0010211220。

按如下规则定义数列 $a_n$：$a_0=0$，且   
$$
a_n=(920461 a_{n-1}+800217387569)\bmod 10^{12} \text{, 对诸 }\  n > 0
$$

我们将诸 $a_n$ 视作一种长度为 $12$ 的按钮组合，若 $a_n$ 在十进制下不足 $12$ 位，则加前导零补齐至 $12$ 位。

给定正整数 $N$，我们对 $a_1,\dots,a_N$ 在 $C(10, 12)$ 中的出现顺序尤其好奇。我们将 $a_1, \cdots, a_N$ 中第一个出现的组合记为第 $1$ 名，由是递推，得到所有组合的名次。记 $a_i$ 的名次为 $p_i$，并记 $\displaystyle F(N)=\sum_{n=1}^Np_na_n$。


例如，在 $C(10, 12)$ 中 $a_1=800217387569$ 比 $a_2=696996536878$ 先出现，于是：
$$
F(2)=1\cdot800217387569 + 2\cdot696996536878 = 2194210461325
$$

你亦已知 $F(10)=32698850376317$。

求 $F(10^7)$ 模 $1234567891$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

