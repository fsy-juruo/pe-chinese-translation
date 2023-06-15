### [693. Finite Sequence Generator](https://projecteuler.net/problem=693)

Two positive integers $x$ and $y$ ($x > y$) can generate a sequence in the following manner:

- $a_x = y$ is the first term,
- $a_{z+1} = a_z^2 \bmod z$ for $z = x, x+1,x+2,\ldots$ and
- the generation stops when a term becomes 0 or 1.

The number of terms in this sequence is denoted $l(x,y)$.

For example, with $x = 5$ and $y = 3$, we get $a_5 = 3$, $a_6 = 3^2 \bmod 5 = 4$, $a_7 = 4^2\bmod 6 = 4$, etc. Giving the sequence of 29 terms:
$3,4,4,2,4,7,9,4,4,3,9,6,4,16,4,16,16,4,16,3,9,6,10,19,25,16,16,8,0$
Hence $l(5,3) = 29$.

$g(x)$ is defined  to be the maximum value of $l(x,y)$ for $y < x$. For example, $g(5) = 29$.

Further, define $f(n)$ to be the maximum value of $g(x)$ for $x \le n$. For example, $f(100) = 145$ and $f(10\,000) = 8824$.

Find $f(3\,000\,000)$.

### 693. 有限序列生成器

我们可以使用两个正整数 $x$、$y$（$x > y$），通过以下方式生成一个序列：

- $a_x = y$。
- 当正整数 $z > x$ 时，$a_{z+1} = a_z^2 \bmod z$。
- 当其中一项为 0 或 1 时，停止生成。

记 $l(x, y)$ 为这个序列的项数。

例如：$x = 5$、$y = 3$ 时，可以得到 $a_5 = 3$，$a_6 = 3^2 \bmod 5 = 4$，$a_7 = 4^2\bmod 6 = 4$，如此往复，可以得到这个序列的 29 个项：
$3,4,4,2,4,7,9,4,4,3,9,6,4,16,4,16,16,4,16,3,9,6,10,19,25,16,16,8,0$，故 $l(5,3) = 29$。

记 $g(x)$ 为对于所有 $y < x$，$l(x,y)$ 的最大值。已知：$g(5) = 29$。

记 $f(n)$ 为对于所有 $x \le n$，$g(x)$ 的最大值。已知：$f(100) = 145$ 且 $f(10\,000) = 8824$。

求 $f(3\,000\,000)$。
