### [805. Shifted Multiples](https://pe.xiaoyaowudi.com/problem=805)

For a positive integer $n$, let $s(n)$ be the integer obtained by shifting the leftmost digit of the decimal representation of $n$ to the rightmost position.
For example, $s(142857)=428571$ and $s(10)=1$.

For a positive rational number $r$, we define $N(r)$ as the smallest positive integer $n$ such that $s(n)=r\cdot n$.
If no such integer exists, then $N(r)$ is defined as zero.
For example, $N(3)=142857$, $N(\tfrac 1{10})=10$ and $N(2) = 0$.

Let $T(M)$ be the sum of $N(u^3/v^3)$ where $(u,v)$ ranges over all ordered pairs of coprime positive integers not exceeding $M$.
For example, $T(3)\equiv 262429173 \pmod {1\,000\,000\,007}$.

Find $T(200)$. Give your answer modulo $1\,000\,000\,007$.

### 805. 平移中的倍数关系

对于正整数 $n$，将其十进制表示中的最左侧的一位移至最右侧，可以得到一个新的正整数，将其记为 $s(n)$。如 $s(142857)=428571$, $s(10)=1$。

对于正有理数 $r$，记 $N(r)$ 为满足 $s(n) = r \cdot n$ 的最小正整数 $n$。如不存在这样的正整数，则记 $N(r) = 0$。如 $N(3)=142857$, $N(\tfrac 1{10})=10$, $N(2) = 0$。

令 $T(M)$ 为所有 $N(u^3/v^3)$ 之和，其中 $(u,v)$ 取遍所有满足 $1 \leq u, v \leq M$，且 $u$, $v$ 互质的二元组。可知 $T(3)\equiv 262429173 \pmod {1\,000\,000\,007}$。

求 $T(200)$ 模 $1\,000\,000\,007$ 之值。