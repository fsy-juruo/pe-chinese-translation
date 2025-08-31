### [861. Products of Bi-Unitary Divisors](https://projecteuler.net/problem=863)

A *unitary divisor* of a positive integer $n$ is a divisor $d$ of $n$ such that $\gcd\left(d,\frac{n}{d}\right)=1$.

A *bi-unitary divisor* of $n$ is a divisor $d$ for which $1$ is the only unitary divisor of $d$ that is also a unitary divisor of $\frac{n}{d}$.

For example, $2$ is a bi-unitary divisor of $8$, because the unitary divisors of $2$ are $\{1,2\}$, and the unitary divisors of $8/2$ are $\{1,4\}$, with $1$ being the only unitary divisor in common.

The bi-unitary divisors of $240$ are $\{1,2,3,5,6,8,10,15,16,24,30,40,48,80,120,240\}$.

Let $P(n)$ be the product of all bi-unitary divisors of $n$. Define $Q_k(N)$ as the number of positive integers $1 \lt n \leq N$ such that $P(n)=n^k$. For example, $Q_2\left(10^2\right)=51$ and $Q_6\left(10^6\right)=6189$.

Find $\sum_{k=2}^{10}Q_k\left(10^{12}\right)$.

### 861. 双单元因数的乘积

若正整数 $n$ 的某个因数 $d$ 满足 $\gcd(d, \frac{n}{d}) = 1$，则称 $d$ 是 $n$ 的一个 *单元因数*。

若正整数 $n$ 的某个因数 $d$ 满足：只有 $1$ 既是 $d$ 的单元因数、又是 $\frac{n}{d}$ 的单元因数，则称 $d$ 是 $n$ 的一个 *双单元因数*。

例如，$n = 8, d = 2$ 时，$2$ 的单元因数有 $1, 2$，$8/2$ 的单元因数有 $1, 4$，二者共有的单元因数只有 $1$。所以 $2$ 是 $8$ 的一个双单元因数。

$240$ 的双单元因数有 $1,2,3,5,6,8,10,15,16,24,30,40,48,80,120,240$。

记 $P(n)$ 为 $n$ 全体双单元因数的乘积，再记 $Q_k(n)$ 为 $1 < n \leq N$ 的正整数中，满足 $P(n) = n^k$ 的正整数的个数。已知：$Q_2\left(10^2\right)=51$、$Q_6\left(10^6\right)=6189$。

求 $\sum_{k=2}^{10}Q_k\left(10^{12}\right)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。