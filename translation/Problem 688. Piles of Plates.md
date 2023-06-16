### [688. Piles of Plates](https://projecteuler.net/problem=688)

We stack $n$ plates into $k$ non-empty piles where each pile is a different size. Define $f(n,k)$ to be the maximum number of plates possible in the smallest pile. For example when $n = 10$ and $k = 3$ the piles $2,3,5$ is the best that can be done and so $f(10,3) = 2$. It is impossible to divide 10 into 5 non-empty piles and hence $f(10,5) = 0$. 

Define $F(n)$ to be the sum of $f(n,k)$ for all possible pile sizes $k\ge 1$. For example $F(100) = 275$. 

Further define $S(N) = \displaystyle\sum_{n=1}^N F(n)$. You are given $S(100) = 12656$. 

Find $S(10^{16})$ giving your answer modulo $1\,000\,000\,007$. 

### 688. 几堆盘子

我们将 $n$ 个盘子分成 $k$ 堆，这 $k$ 堆必须非空，且每一堆的盘子数量互不相同。记 $f(n,k)$ 为含有盘子最少的一堆里，最多可以拥有的盘子数量。例如，$n = 10, k = 3$ 时，因为有方案 $(2,3,5)$ 且没有更优方案，从而 $f(10, 3)=2$。因为不可能将 10 个盘子分成非空的，且大小互不相同的 5 堆，从而 $f(10,5) = 0$。

记 $F(n)$ 为对所有可能的 $k (k \geq 1)$，$f(n,k)$ 之和。例如有 $F(100) = 275$。

再记 $S(N) = \displaystyle\sum_{n=1}^N F(n)$。已知：$S(100) = 12656$。

求 $S(10^{16})$ 模 $1\,000\,000\,007$ 之值。 

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。