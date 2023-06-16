### [675. $2^{\omega(n)}$](https://projecteuler.net/problem=675)

Let $\omega(n)$ denote the number of distinct prime divisors of a positive integer $n$. So $\omega(1) = 0$ and $\omega(360) = \omega(2^{3} \times 3^{2} \times 5) = 3$.

Let $S(n)$ be $ \Sigma_{d | n} 2^{\omega(d)} $.

E.g. $S(6) = 2^{\omega(1)}+2^{\omega(2)}+2^{\omega(3)}+2^{\omega(6)} = 2^0+2^1+2^1+2^2 = 9$.

Let $F(n)=\Sigma_{i=2}^n S(i!)$. $F(10)=4821.$

Find $F(10,000,000)$. Give your answer modulo $1,000,000,087$.

### 675. $2^{\omega(n)}$

记 $\omega(n)$ 为正整数 $n$ 本质不同的质因子个数。因此 $\omega(1) = 0$ 且 $\omega(360) = \omega(2^{3} \times 3^{2} \times 5) = 3$。

记 $S(n) =  \sum_{d|n} 2^{\omega(d)}$。例如 $S(6) = 2^{\omega(1)}+2^{\omega(2)}+2^{\omega(3)}+2^{\omega(6)} = 2^0+2^1+2^1+2^2 = 9$。

再记 $F(n)=\sum_{i=2}^n S(i!)$。如 $F(10)=4821$。

求出 $F(10,000,000)$ 模 $1,000,000,087$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

