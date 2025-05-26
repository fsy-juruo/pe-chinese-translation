### [890. Binary Partitions](https://projecteuler.net/problem=890)

Let $p(n)$ be the number of ways to write $n$ as the sum of powers of two, ignoring order.

For example, $p(7) = 6$, the partitions being
$$
\begin{align}
7 & = 1+1+1+1+1+1+1 \\
& =1+1+1+1+1+2 \\
& =1+1+1+2+2 \\
& =1+1+1+4 \\
& =1+2+2+2 \\
& =1+2+4
\end{align}
$$
You are also given $p(7^7) \equiv 144548435 \pmod {10^9+7}$.

Find $p(7^{777})$. Give your answer modulo $10^9 + 7$.

### 890. 二进制拆分

记 $p(n)$ 为：不考虑顺序，将 $n$ 拆分为若干个 $2$ 的幂的和的方案数。

例如 $p(7) = 6$，所有可能的拆分方案如下：

$$
\begin{align}
7 & = 1+1+1+1+1+1+1 \\
& =1+1+1+1+1+2 \\
& =1+1+1+2+2 \\
& =1+1+1+4 \\
& =1+2+2+2 \\
& =1+2+4
\end{align}
$$

你亦已知 $p(7^7) \equiv 144548435 \pmod {10^9+7}$。

求 $p(7^{777})$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

