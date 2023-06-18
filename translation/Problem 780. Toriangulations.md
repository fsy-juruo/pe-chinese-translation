### [780. Toriangulations](https://projecteuler.net/problem=780)

For positive real numbers $a,b$, an $a\times b$ **torus** is a rectangle of width $a$ and height $b$, with left and right sides identified, as well as top and bottom sides identified. In other words, when tracing a path on the rectangle, reaching an edge results in "wrapping round" to the corresponding point on the opposite edge.

A *tiling* of a torus is a way to dissect it into equilateral triangles of edge length 1. For example, the following three diagrams illustrate respectively a $1\times \frac{\sqrt{3}}{2}$ torus with two triangles, a $\sqrt{3}\times 1$ torus with four triangles, and an approximately $2.8432\times 2.1322$ torus with fourteen triangles:

<div style="text-align:center;">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-1.png?1678992054" class="dark_img" alt="" height="160">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-2.png?1678992054" class="dark_img" alt="" height="160">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-3.png?1678992054" class="dark_img" alt="" height="160">
</div>

Two tilings of an $a\times b$ torus are called *equivalent* if it is possible to obtain one from the other by continuously moving all triangles so that no gaps appear and no triangles overlap at any stage during the movement. For example, the animation below shows an equivalence between two tilings:

![](https://pe.xiaoyaowudi.com/resources/images/0780_animation.gif?1678992057)


Let $F(n)$ be the total number of non-equivalent tilings of all possible tori with exactly $n$ triangles. For example, $F(6)=8$, with the eight non-equivalent tilings with six triangles listed below:

![](https://pe.xiaoyaowudi.com/resources/images/0780_t6-all.png?1678992054)

Let $G(N)=\sum_{n=1}^N F(n)$. You are given that $G(6)=14$, $G(100)=8090$, and $G(10^5)\equiv 645124048 \pmod{1\,000\,000\,007}$.

Find $G(10^9)$. Give your answer modulo $1\,000\,000\,007$.

### 780. 环面上的三角剖分 [^1]

对于正实数 $a, b$，我们把某个长为 $a$、宽为 $b$ 的矩形的两组对边分别叠合，其形成的图形称为一个 $a \times b$ 的 **环面**。换言之，在这个矩形上移动时，如果移动到某一条边上，就会瞬移到其对边的对应位置。

将某个环面剖分为若干个边长为 1 的等边三角形的方法被称作这个环面的一个 *平铺*。例如，下面三张图片分别阐述了某个 $1\times \frac{\sqrt{3}}{2}$ 的、$\sqrt{3}\times 1$ 的、约为 $2.8432\times 2.1322$ 的环面的某个含 2 、4、14 个三角形的平铺。

<div style="text-align:center;">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-1.png?1678992054" class="dark_img" alt="" height="160">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-2.png?1678992054" class="dark_img" alt="" height="160">
<img src="https://pe.xiaoyaowudi.com/resources/images/0780_sample-small-3.png?1678992054" class="dark_img" alt="" height="160">
</div>

如果我们可以通过不断移动某个平铺中的三角形，且移动过程中没有空隙、没有三角形互相重叠，最终得到另一种平铺的话，则称这两个平铺 *等价*。下面的动图展示了两个等价的平铺之间的转化方法。

![](https://pe.xiaoyaowudi.com/resources/images/0780_animation.gif?1678992057)

记 $F(n)$ 为恰有 $n$ 个等边三角形，且互相不等价的环面平铺的数量。如 $F(6) = 8$，八个互不等价的平铺方法见下图。

![](https://pe.xiaoyaowudi.com/resources/images/0780_t6-all.png?1678992054)

记 $G(N ) = \sum_{n=1}^N F(n)$。已知：$G(6) = 14$、$G(100)=8090$、$G(10^5)\equiv 645124048 \pmod{1\,000\,000\,007}$。

求 $G(10^9)$ 模 $1\,000\,000\,007$ 之值。

[^1]: 原标题是「环面（torus）」和「三角剖分（triangulation）」两词的拼合。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。