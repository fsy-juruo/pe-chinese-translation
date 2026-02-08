### [980. The Quaternion Group I](https://projecteuler.net/problem=980)

Starting from an empty string, we want to build a string with letters "x", "y", "z". At each step, one of the following operations is performed:

- insert two consecutive identical letters "xx", "yy" or "zz" anywhere into the string;
- replace one letter in the string with two consecutive letters, according to the rule: "x" $\to$ "yz", "y" $\to$ "zx", "z" $\to$ "xy";
- exchange two consecutive **different** letters in the string, e.g. "xy" $\to$ "yx", "zx" $\to$ "xz", etc.

A string is called *neutral* if it is possible to produce the string from the empty string after an **even** number of steps.

We define a sequence $(a_n)_{n \ge 0}$: $a_0=88\,888\,888$ and $a_n=(8888\cdot a_{n-1})\bmod 888\,888\,883$ for $n \gt 0$.

Let $b_n = a_n \bmod 3$. For each $i \ge 0$, a string $c(i)$ of length $50$ is defined by translating the finite sequence $b_{50i},b_{50i+1},\dots,b_{50i+49}$ via the rule: $0 \to$ "x", $1 \to$ "y", $2 \to$ "z".

Let $F(N)$ be the number of ordered pairs $(i, j)$ with $0 \le i, j \lt N$ such that the concatenated string $c(i)c(j)$ is neutral.  
For example, $F(10) = 13$ and $F(100) = 1224$.

Find $F(10^6)$.

### 980. 四元群 1

从一个空串开始，我们希望构造一个仅含字母 'x'、'y'、'z' 的字符串。构造的每一步中，你只能进行如下操作之一：

- 在这个字符串中的任意处插入两个连续且相同的字符 "xx"、"yy" 或 "zz"。
- 依照如下规则，把字符串中的一个字符替换成两个连续字符："x" $\to$ "yz"、"y" $\to$ "zx"、"z" $\to$ "xy"。
- 交换字符串中两个连续且 **不同** 的字符。例如："xy" $\to$ "yx"、"zx" $\to$ "xz" 等。

若能够从空串开始，经 **偶数** 次操作后得到某个字符串，则称这个字符串是 *中性的*。

我们根据如下递推定义数列 $(a_n)_{n \ge 0}$：$a_0=88\,888\,888$，且对诸 $n \gt 0$ 都有 $a_n=(8888\cdot a_{n-1})\bmod 888\,888\,883$。

令 $b_n = a_n \bmod 3$，对诸 $i \ge 0$，我们按如下规则将有限数列 $b_{50i},b_{50i+1},\dots,b_{50i+49}$ 映射为一个长度为 $50$ 的字符串 $c(i)$：$0 \to$ "x"、$1 \to$ "y"、$2 \to$ "z"。

记 $F(N)$ 为满足以下条件的有序对 $(i, j)$ 的个数：$0 \le i, j \lt N$ 且 $c(i)$ 与 $c(j)$ 的拼接是中性的。例如 $F(10) = 13$、$F(100) = 1224$。

求 $F(10^6)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
