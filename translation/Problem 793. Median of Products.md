### [793. Median of Products](https://projecteuler.net/problem=793)

Let $S_i$ be an integer sequence produced with the following pseudo-random number generator:

* $S_0 = 290797$
* $S_{i+1} = S_i ^2 \bmod 50515093$

Let $M(n)$ be the median of the pairwise products $ S_i S_j $ for $0 \le i \lt j \lt n$.

You are given $M(3) = 3878983057768$ and $M(103) = 492700616748525$.

Find $M(1\,000\,003)$.

### 793. 乘积的中位数

我们通过如下伪随机数生成器生成一个整数数列 $\{S_i\}$：

* $S_0 = 290797$
* $S_{i+1} = S_i ^2 \bmod 50515093$

记 $M(n)$ 为所有满足 $0 \le i \lt j \lt n$ 的 $S_i S_j$ 的中位数。已知 $M(3) = 3878983057768$、$M(103) = 492700616748525$。

求 $M(1\,000\,003)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。