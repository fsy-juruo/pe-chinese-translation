###  [841. Regular Star Polygons](https://projecteuler.net/problem=841)

The regular star polygon $\{p/q\}$, for coprime integers $p,q$ with $p \gt 2q \gt 0$, is a polygon formed from $p$ edges of equal length and equal internal angles, such that tracing the complete polygon wraps $q$ times around the centre. For example, $\{8/3\}$ is illustrated below:

![](https://pe.xiaoyaowudi.com/resources/images/0841_star_polygon_8_3.png?1680515338)

The edges of a regular star polygon intersect one another, dividing the interior into several regions. Define the *alternating shading* of a regular star polygon to be a selection of such regions to shade, such that every piece of every edge has a shaded region on one side and an unshaded region on the other, with the exterior of the polygon unshaded. For example, the above image shows the alternating shading (in green) of $\{8/3\}$.

Let $A(p, q)$ be the area of the alternating shading of $\{p/q\}$, assuming that its inradius is $1$. (The **inradius** of a regular polygon, star or otherwise, is the distance from its centre to the midpoint of any of its edges.) For example, in the diagram above, it can be shown that central shaded octagon has area $8(\sqrt{2}-1)$ and each point's shaded kite has area $2(\sqrt{2}-1)$, giving $A(8,3) = 24(\sqrt{2}-1) \approx 9.9411254970$.

You are also given that $A(130021, 50008)\approx 10.9210371479$, rounded to $10$ digits after the decimal point.

Find $\sum_{n=3}^{34} A(F_{n+1},F_{n-1})$, where $F_j$ is the Fibonacci sequence with $F_1=F_2=1$ (so $A(F_{5+1},F_{5-1}) = A(8,3)$). Give your answer rounded to $10$ digits after the decimal point.

###  841. 规则星形多边形

对于满足 $p, q$ 互质与 $p \gt 2q \gt 0$ 的正整数 $p, q$，我们定义规则星形多边形 $\{p/q\}$ 为一个由 $p$ 条等长的边围成、内角相等、且围绕着某个正多边形的中心“缠绕”了这个多边形 $q$ 圈。[^1] 下图展示了规则星形多边形 $\{8/3\}$。

![](https://pe.xiaoyaowudi.com/resources/images/0841_star_polygon_8_3.png?1680515338)

规则星形多边形的边彼此相交，将其内部划分为一些不同的区域。我们定义某规则星形多边形的 *交替阴影涂色* 为满足如下条件的一种区域染色方案：

* 星形多边形的外部没有阴影。
* 任何一条“短边”（被一条边包含，且不与其他边相交的线段）的两侧的两个区域必须恰好有一个区域有阴影，一个区域没有阴影。

上图呈现了规则星形多边形 $\{8/3\}$ 的交替阴影涂色法（阴影用绿色表示）。

假设规则星形多边形的**内径（inradius）**，即其中心与其任意一条边的中点之距为 $1$。记 $A(p, q)$ 为规则星形多边形 $\{p/q\}$ 的交替阴影涂色法中，有阴影部分区域的面积。例如：在规则星形多边形 $\{8/3\}$ 中，中间的正八边形面积为 $8(\sqrt{2}-1)$，余下的每一个筝形面积为 $2(\sqrt{2}-1)$，从而：$A(8,3) = 24(\sqrt{2}-1) \approx 9.9411254970$。你已知 $A(130021, 50008)$ 在四舍五入至小数点后第 $10$ 位后约为 $10.9210371479$。

求 $\sum_{n=3}^{34} A(F_{n+1},F_{n-1})$，其中 $F_j$ 是第 $j$ 个斐波那契数（此处认为 $F_1=F_2=1$，故 $A(F_{5+1},F_{5-1}) = A(8,3)$）。将你的答案四舍五入至小数点后第 $10$ 位后提交。

[^1]: 参见下方译注对应处。

-----------------------------------

**译注：**

为了方便理解，这里给出规则星形多边形 $\{p/q\}$ 的构造方法。并对 [1] 处的翻译进行解释。

1. 连接点：在单位圆上等距分布 $p$ 个点，顺时针标号为 $1, 2, \cdots, p$。从 $1$ 号点开始，每一次将 $i$ 号点（当前待连边的点）与 $i + q$ 号（大于 $p$ 时对 $p$ 取余）点相连。直至重新连回 $1$ 号点。例如，$p = 8, q = 3$ 时，$i$ 依次为 $1, 4, 7, 2, 5, 8, 3, 6$。

那为什么说是“环绕” $q$ 圈？在下图中仔细观察，每次连边后，该边都会占据 $\frac{2q}{p} \pi$ 的圆心角。重新连回 $1$ 号点时，占据的圆心角总和为 $q \times 2\pi$，相当于“环绕”了 $q$ 圈。

![](https://github.com/fsy-juruo/pe-chinese-translation/blob/master/images/841_regular_star_polygon_with_circum.PNG) 
> 使用了 Alex CHIK 在 GeoGebra 上的演示器。[网址链接](https://www.geogebra.org/material/show/id/tYUSwUxw)

这种方法在 $(p, q) \neq 1$ 时会退化，还有一种方法是，直接对于所有 $i \in \{1, 2, 3, \cdots, p\}$，将 $i$ 号点与 $i + q$ 号（大于 $p$ 时对 $p$ 取余）点相连。

2. 星形化（Stellation）：将正 $p$ 边形的 $p$ 条边顺时针标号为 $1, 2, \cdots p$。每一次延长第 $i$ 条与第 $i + q$ 号（大于 $p$ 时对 $p$ 取余）条边并取其交点，形成的图形即为所求。

顺带一提，$\{p/q\}$ 这种表示规则星形多边形的方法被称为 Schläfli 符号。


