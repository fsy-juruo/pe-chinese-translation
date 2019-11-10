### 688. Piles of Plates

We stack $n$ plates into $k$ non-empty piles where each pile is a different size. Define $f(n,k)$ to be the maximum number of plates possible in the smallest pile. For example when $n = 10$ and $k = 3$ the piles $2,3,5$ is the best that can be done and so $f(10,3) = 2$. It is impossible to divide 10 into 5 non-empty piles and hence $f(10,5) = 0$. 

Define $F(n)$ to be the sum of $f(n,k)$ for all possible pile sizes $k\ge 1$. For example $F(100) = 275$. 

Further define $S(N) = \displaystyle\sum_{n=1}^N F(n)$. You are given $S(100) = 12656$. 

Find $S(10^{16})$ giving your answer modulo $1\,000\,000\,007$. 



### 688. 几堆盘子

我们将 $n$ 个盘子堆成非空的，且大小互不相同的 $k$ 堆。定义 $f(n,k)$ 为含有盘子最少的一堆里，最多可以拥有的盘子数量。比如说，对于 $n = 10, k = 3$，因为有方案 $(2,3,5)$ 且没有更优方案，所以 $f(10, 3)=2$。因为不可能将 10 个盘子分成非空的，且大小互不相同的 5 堆，所以 $f(10,5) = 0$.。

定义 $F(n)$ 为对于所有可能的 $k (k \geq 1)$，$f(n,k)$ 之和。比如说 $F(100) = 275$。

再定义 $S(N) = \displaystyle\sum_{n=1}^N F(n)$，已知 $S(100) = 12656$。

求 $S(10^{16})$ 模 $1\,000\,000\,007$。 

