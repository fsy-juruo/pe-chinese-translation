### [792. Too Many Twos](https://pe.xiaoyaowudi.com/problem=792)

We define $\nu_2(n)$ to be the largest integer $r$ such that $2^r$ divides $n$. For example, $\nu_2(24) = 3$.

Define $\displaystyle S(n)  = \sum_{k = 1}^n (-2)^k\binom{2k}k$ and $u(n) = \nu_2\Big(3S(n)+4\Big)$.

For example, when $n = 4$ then $S(4) = 980$ and $3S(4) + 4 = 2944 = 2^7 \cdot 23$, hence $u(4) = 7$.
You are also given $u(20) = 24$.

Also define $\displaystyle U(N) = \sum_{n = 1}^N u(n^3)$. You are given $U(5) = 241$.

Find $U(10^4)$.

### 792. 太多 2 了

记 $\nu_2(n)$ 为最大的，满足 $2^r$ 整除 $n$ 的整数 $r$。例如 $\nu_2(24) = 3$。

记 $\displaystyle S(n)  = \sum_{k = 1}^n (-2)^k\binom{2k}k$，再记 $u(n) = \nu_2\Big(3S(n)+4\Big)$。

例如，$n = 4$ 时，$S(4) = 980$, $3S(4) + 4 = 2944 = 2^7 \cdot 23$。故 $u(4) = 7$。你已知 $u(20) = 24$。

进一步记 $\displaystyle U(N) = \sum_{n = 1}^N u(n^3)$。已知 $U(5) = 241$。

求 $U(10^4)$。
