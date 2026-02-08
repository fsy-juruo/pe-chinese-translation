### [704. Factors of Two in Binomial Coefficients](https://projecteuler.net/problem=704)

Define $g(n, m)$ to be the largest integer $k$ such that $2^k$ divides $\binom{n}m$. 
For example, $\binom{12}5 = 792 = 2^3 \cdot 3^2 \cdot 11$, hence $g(12, 5) = 3$. 
Then define $F(n) = \max \{ g(n, m) : 0 \le m \le n \}$. $F(10) = 3$ and $F(100) = 6$.

Let $S(N)$ = $\displaystyle\sum_{n=1}^N{F(n)}$. You are given that $S(100) = 389$ and $S(10^7) = 203222840$.

Find $S(10^{16})$.

### 704. 二项式系数中的因子二

记 $g(n, m)$ 为：满足 $2^k$ 整除 $\binom{n}m$ 的最大的整数 $k$。
例如，$\binom{12}5 = 792 = 2^3 \cdot 3^2 \cdot 11$，因此 $g(12, 5) = 3$。
随后我们定义 $F(n) = \max \{ g(n, m) : 0 \le m \le n \}$，可以验证 $F(10) = 3$、$F(100) = 6$。

记 $S(N)$ = $\displaystyle\sum_{n=1}^N{F(n)}$。你已知 $S(100) = 389$、$S(10^7) = 203222840$。

求 $S(10^{16})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
