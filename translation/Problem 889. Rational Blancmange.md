### [889. Rational Blancmange](https://projecteuler.net/problem=889)

Recall the blancmange function from [Problem 226](https://projecteuler.net/problem=226): $T(x) = \sum\limits_{n = 0}^\infty\dfrac{s(2^nx)}{2^n}$, where $s(x)$ is the distance from $x$ to the nearest integer.

For positive integers $k, t, r$, we write 
$$
F(k, t, r) = (2^{2k} - 1)T\left(\frac{(2^t + 1)^r}{2^k + 1}\right).
$$
It can be shown that $F(k, t, r)$ is always an integer.  
For example, $F(3, 1, 1) = 42$, $F(13, 3, 3) = 23093880$ and $F(103, 13, 6) \equiv 878922518\pmod {1\,000\,062\,031}$.

Find $F(10^{18} + 31, 10^{14} + 31, 62)$. Give your answer modulo $1\,000\,062\,031$.

### 889. 有理数上的奶冻函数

考虑 [第 226 题](https://fsy-juruo.github.io/pe-chinese-translation/problems/226.html) 中提及的奶冻函数：$T(x) = \sum\limits_{n = 0}^\infty\dfrac{s(2^nx)}{2^n}$，其中 $s(x)$ 指的是 $x$ 到离它最近的整数的距离。

对正整数 $k, t, r$，记
$$
F(k, t, r) = (2^{2k} - 1)T\left(\frac{(2^t + 1)^r}{2^k + 1}\right).
$$
可以证明 $F(k, t, r)$ 始终是整数。例如，$F(3, 1, 1) = 42$、$F(13, 3, 3) = 23093880$、$F(103, 13, 6) \equiv 878922518\pmod {1\,000\,062\,031}$。

求 $F(10^{18} + 31, 10^{14} + 31, 62)$ 模 $1\,000\,062\,031$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

