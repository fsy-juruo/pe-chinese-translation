### [892. Zebra Circles](https://projecteuler.net/problem=863)

Consider a circle where $2n$ distinct points have been marked on its circumference.

A <i>cutting</i> $C$ consists of connecting the $2n$ points with $n$ line segments, so that no two line segments intersect, including on their end points. The $n$ line segments then cut the circle into $n + 1$ pieces.
Each piece is painted either black or white, so that adjacent pieces are opposite colours.
Let $d(C)$ be the absolute difference between the numbers of black and white pieces under the cutting $C$.

Let $D(n)$ be the sum of $d(C)$ over all different cuttings $C$.
For example, there are five different cuttings with $n = 3$.

<div style="text-align:center;">
<img src="resources/images/0892_Zebra.png?1714876283" alt="0892_Zebra.png"></div>

The upper three cuttings all have $d = 0$ because there are two black and two white pieces; the lower two cuttings both have $d = 2$ because there are three black and one white pieces.
Therefore $D(3) = 0 + 0 + 0 + 2 + 2 = 4$. 
You are also given $D(100) \equiv 1172122931\pmod{1234567891}$.

Find $\displaystyle \sum_{n=1}^{10^7} D(n)$. Give your answer modulo $1234567891$.

### 892. 黑白交替的圆

我们在某圆周上任取 $2n$ 个互不重合的点。我们将这些点用 $n$ 条互不相交、且不共端点的线段相连，并称这是这个圆周的一个 *切分*。

此时，圆周内部被这 $n$ 条直线割成了 $n + 1$ 个部分。我们接下来将每个部分黑白染色，且在涂色的过程中保证相邻的部分颜色不同。我们记 $d(C)$ 为：对于切分 $C$，黑色部分的数量和白色部分的数量之差的绝对值。再记 $D(n)$ 为：对所有不同的切分 $C$，其 $d(C)$ 之和。

例如 $n = 3$ 时，有 $5$ 种不同的切分，如下图所示。图片上侧的三种切分法的 $d$ 值为 0，下侧的两种切分法的 $d$ 值为 2。所以 $D(3) = 4$。已知：$D(100) \equiv 1172122931\pmod{1234567891}$。

<div style="text-align:center;">
<img src="resources/images/0892_Zebra.png?1714876283" alt="0892_Zebra.png"></div>

求 $\displaystyle \sum_{n=1}^{10^7} D(n)$ 模 $1234567891$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。