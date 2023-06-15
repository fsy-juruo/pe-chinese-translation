### [717. Summation of a Modular Formula](https://projecteuler.net/problem=717)

For an odd prime $p$, define $f(p) = \left\lfloor\frac{2^{(2^p)}}{p}\right\rfloor\bmod{2^p}$
For example, when $p=3$, $\lfloor 2^8/3\rfloor = 85 \equiv 5 \pmod 8$ and so $f(3) = 5$.

Further define $g(p) = f(p)\bmod p$. You are given $g(31) = 17$.

Now define $G(N)$ to be the summation of $g(p)$ for all odd primes less than $N$.
You are given $G(100) = 474$ and $G(10^4) = 2819236$.

Find $G(10^7)$.

### 717. 模意义函数值求和

对于奇质数 $p$，记 $f(p) = \left\lfloor\frac{2^{(2^p)}}{p}\right\rfloor\bmod{2^p}$。例如当 $p=3$ 时，$\lfloor 2^8/3\rfloor = 85 \equiv 5 \pmod 8$，因而 $f(3) = 5$。

再记 $g(p) = f(p)\bmod p$。已知：$g(31) = 17$。

再记 $G(N)$ 为对于所有小于 $N$ 的奇质数 $p$，$g(p)$ 的和。已知 $G(100) = 474$ 且 $G(10^4) = 2819236$。

求 $G(10^7)$。
