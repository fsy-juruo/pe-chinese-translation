### [842. Irregular Star Polygons](https://projecteuler.net/problem=842)

Given $n$ equally spaced points on a circle, we define an *$n$-star polygon* as an $n$-gon having those $n$ points as vertices. Two $n$-star polygons differing by a rotation/reflection are considered **different**.

For example, there are twelve $5$-star polygons shown below.

![](images/0842_5-agons.jpg?1680461480)

For an $n$-star polygon $S$, let $I(S)$ be the number of its self intersection points.
Let $T(n)$ be the sum of $I(S)$ over all $n$-star polygons $S$.
For the example above $T(5) = 20$ because in total there are $20$ self intersection points.

Some star polygons may have intersection points made from more than two lines. These are only counted once. For example, $S$, shown below is one of the sixty $6$-star polygons. This one has $I(S) = 4$.

![](images/0842_6-agon.jpg?1680461493)

You are also given that $T(8) = 14640$.

Find $\displaystyle \sum_{n = 3}^{60}T(n)$. Give your answer modulo $(10^9 + 7)$.

### 842. 不规则星形多边形

在圆上均匀分布 $n$ 个点，我们定义 *星形 $n$ 边形* 为以这 $n$ 个点为顶点的 $n$ 边形。**经旋转、反转后一致的多边形被认为是不同的。**

下图是 12 个星形 $5$ 边形。

![](images/0842_5-agons.jpg?1680461480)

对于一个星形 $n$ 边形 $S$，记 $I(S)$ 为该 $n$ 边形自相交点的个数。记 $T(n)$ 为所有星形 $n$ 边形的 $I(S)$ 之和。已知：$T(5) = 20$。

需要注意的是，如果有多于两条边同时交于一点，这个自相交点应该只被计数 1 次。如下图，对于这个星形六边形 $S$，$I(S) = 4$。

![](images/0842_6-agon.jpg?1680461493)

又已知：$T(8) = 14640$。

求 $\displaystyle \sum_{n = 3}^{60}T(n)$ 模 $(10^9 + 7)$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。