### [795. Alternating GCD Sum](https://pe.xiaoyaowudi.com/problem=795)


For a positive integer $n$, the function $g(n)$ is defined as

$$
\displaystyle g(n)=\sum_{i=1}^{n} (-1)^i \gcd \left(n,i^2\right)
$$

For example, $g(4) = -\gcd \left(4,1^2\right) + \gcd \left(4,2^2\right) - \gcd \left(4,3^2\right) + \gcd \left(4,4^2\right) = -1+4-1+4=6$.
You are also given $g(1234)=1233$.

Let $\displaystyle G(N) = \sum_{n=1}^N g(n)$. You are given $G(1234) = 2194708$.

Find $G(12345678)$.

### 795. 交错最大公因数求和

对于正整数 $n$，记函数 $g(n)$ 如下：

$$
\displaystyle g(n)=\sum_{i=1}^{n} (-1)^i \gcd \left(n,i^2\right)
$$

如 $g(4) = -\gcd \left(4,1^2\right) + \gcd \left(4,2^2\right) - \gcd \left(4,3^2\right) + \gcd \left(4,4^2\right) = -1+4-1+4=6$，同理 $g(1234)=1233$。

令 $\displaystyle G(N) = \sum_{n=1}^N g(n)$，已知 $G(1234) = 2194708$。

求 $G(12345678)$。