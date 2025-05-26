### [946. Continued Fraction Fraction](https://projecteuler.net/problem=946)

Given the representation of a continued fraction
$$
a_0+ \cfrac 1{a_1+ \cfrac 1{a_2+\cfrac 1{a_3+\ddots }}}= [a_0;a_1,a_2,a_3,\ldots]
$$

$\alpha$ is a real number with continued fraction representation:
$\alpha = [2;1,1,2,1,1,1,2,1,1,1,1,1,2,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,1,1,1,1,2,\ldots]$  
where the number of $1$'s between each of the $2$'s are consecutive prime numbers.

$\beta$ is another real number defined as
$$
\beta = \frac{2\alpha+3}{3\alpha+2}
$$

The first ten coefficients of the continued fraction of $\beta$ are $[0;1,5,6,16,9,1,10,16,11]$ with sum $75$.

Find the sum of the first $10^8$ coefficients of the continued fraction of $\beta$.

### 946. 由连分数构成的分数

已知我们可以用连分数的表示形式表示一个实数：
$$
[a_0;a_1,a_2,a_3,\ldots] = a_0+ \cfrac 1{a_1+ \cfrac 1{a_2+\cfrac 1{a_3+\ddots }}}
$$

实数 $\alpha$ 的连分数表示为：
$$
\alpha = [2;1,1,2,1,1,1,2,1,1,1,1,1,2,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,1,1,1,1,2,\ldots]
$$
其中，每两个 $2$ 之间的 $1$ 的个数是连续的素数。

$\beta$ 是另一个实数，定义为：
$$
\beta = \frac{2\alpha+3}{3\alpha+2}
$$

$\beta$ 的连分数表示的前十项为 $[0;1,5,6,16,9,1,10,16,11]$，其和为 $75$。

求 $\beta$ 的连分数表示的前 $10^8$ 项之和。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。