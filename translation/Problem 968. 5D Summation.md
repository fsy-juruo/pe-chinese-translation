### [968. 5D Summation](https://projecteuler.net/problem=968)

Define
$$
P(X_{a,b},X_{a,c},X_{a,d},X_{a,e},X_{b,c},X_{b,d},X_{b,e},X_{c,d},X_{c,e},X_{d,e})
$$
as the sum of $2^a3^b5^c7^d11^e$ over all quintuples of non-negative integers $(a, b, c, d, e)$ such that the sum of each two of the five variables is restricted by a given value. In other words, $a+b \le X_{a,b}$, $a+d \le X_{a,d}$, $b+e \le X_{b,e}$ etc.

For example, $P(2,2,2,2,2,2,2,2,2,2)=7120$ and $P(1, 2, 3, 4, 5, 6, 7, 8, 9, 10) \equiv 799809376 \pmod{10^9 + 7}$.

Define a sequence $A$ as follows:

- $A_0 = 1$, $A_1 = 7$;
- $A_n =(7A_{n−1}+A_{n-2}^2) \bmod(10^9+7)$ for $n \ge 2$.

Also define $Q(n) = P(A_{10n}, A_{10n+1}, A_{10n+2}, \dots , A_{10n+9})$.

Find $\displaystyle\sum_{0 \le n \lt 100}Q(n)$. Give your answer modulo $10^9+7$.

### 968. 五维求和

记
$$
P(X_{a,b},X_{a,c},X_{a,d},X_{a,e},X_{b,c},X_{b,d},X_{b,e},X_{c,d},X_{c,e},X_{d,e})
$$
为：所有满足
$$
\forall i, j \in \{a, b, c, d, e\}, i + j \le X_{i, j}
$$
的非负整数五元组 $(a, b, c, d, e)$ 的 $2^a3^b5^c7^d11^e$ 之和。

例如，$P(2,2,2,2,2,2,2,2,2,2)=7120$、$P(1, 2, 3, 4, 5, 6, 7, 8, 9, 10) \equiv 799809376 \pmod{10^9 + 7}$。

按如下规则定义序列 $A$：

- $A_0 = 1$、$A_1 = 7$；
- 对诸 $n \ge 2$，有 $A_n =(7A_{n−1}+A_{n-2}^2) \bmod(10^9+7)$。

另记 $Q(n) = P(A_{10n}, A_{10n+1}, A_{10n+2}, \dots , A_{10n+9})$.

求 $\displaystyle\sum_{0 \le n \lt 100}Q(n)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
