### [694. Cube-full Divisors](https://projecteuler.net/problem=694)

A positive integer $n$ is considered *cube-full*, if for every prime $p$ that divides $n$, so does $p^3$. Note that $1$ is considered cube-full.

Let $s(n)$ be the function that counts the number of cube-full divisors of $n$. For example, $1$, $8$ and $16$ are the three cube-full divisors of $16$. Therefore, $s(16)=3$.

Let $S(n)$ represent the summatory function of $s(n)$, that is $S(n)=\displaystyle\sum_{i=1}^n s(i)$.

You are given $S(16) =  19$, $S(100) = 126$ and $S(10000) = 13344$.

Find $S(10^{18})$.

### 694. 满立方约数

对于一个正整数 $n$，如果对于 $n$ 的每个质因子 $p$，都有 $p^3$ 是 $n$ 的约数，就称这个正整数 $n$ 是*满立方数*。注意，$1$ 也是满立方数。

记 $s(n)$ 为 $n$ 的满立方约数的个数。例如，$1$、$8$ 和 $16$ 是 $16$ 的三个满立方约数。从而 $s(16)=3$。

记 $S(n)$ 为 $s(n)$ 的前缀和函数，即 $S(n)=\displaystyle\sum_{i=1}^n s(i)$。已知 $S(16) =  19$、$S(100) = 126$ 且 $S(10000) = 13344$。

求 $S(10^{18})$。

