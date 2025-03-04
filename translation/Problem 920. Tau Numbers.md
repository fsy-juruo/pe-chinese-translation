### [920. Tau Numbers](https://projecteuler.net/problem=920)

For a positive integer $n$ we define $\tau(n)$ to be the count of the divisors of $n$. For example, the divisors of $12$ are $\{1,2,3,4,6,12\}$ and so $\tau(12) = 6$.

A positive integer $n$ is a **tau number** if it is divisible by $\tau(n)$. For example $\tau(12)=6$ and $6$ divides $12$ so $12$ is a tau number.

Let $m(k)$ be the smallest tau number $x$ such that $\tau(x) = k$. For example, $m(8) = 24$, $m(12)=60$ and $m(16)=384$.

Further define $M(n)$ to be the sum of all $m(k)$ whose values do not exceed $10^n$. You are given $M(3) = 3189$.

Find $M(16)$.

### 920. $\tau$ 数

对正整数 $n$，我们记 $\tau(n)$ 为 $n$ 的正约数的个数。例如 $12$ 的所有因数是 $\{1,2,3,4,6,12\}$，于是 $\tau(12) = 6$。

若正整数 $n$ 满足 $\tau(n)$ 整除 $n$，则称 $n$ 是一个 **$\mathbf{\tau}$-数**。例如，$\tau(12) = 6$ 整除 $12$，所以 $12$ 是一个 $\tau$ 数。

记 $m(k)$ 为最小的，满足 $\tau(x) = k$ 的 $\tau$-数 $x$。已知 $m(8) = 24$、$m(12) = 60$、$m(16) = 384$。

再记 $M(n) = \sum_{k=1}^{10^n} m(k)$，已知 $M(3) = 3189$。

求 $M(16)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

