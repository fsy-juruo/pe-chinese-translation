### [837. Amidakuji](https://projecteuler.net/problem=845)

[Amidakuji](https://en.wikipedia.org/wiki/Amidakuji) (Japanese: 阿弥陀籤) is a method for producing a random permutation of a set of objects.

In the beginning, a number of parallel vertical lines are drawn, one for each object. Then a specified number of horizontal rungs are added, each lower than any previous rungs. Each rung is drawn as a line segment spanning a randomly select pair of adjacent vertical lines.

For example, the following diagram depicts an Amidakuji with three objects ($A$, $B$, $C$) and six rungs:

![](https://pe.xiaoyaowudi.com/resources/images/0837_amidakuji.png?1678992054)

The coloured lines in the diagram illustrate how to form the permutation. For each object, starting from the top of its vertical line, trace downwards but follow any rung encountered along the way, and record which vertical we end up on. In this example, the resulting permutation happens to be the identity: $A\mapsto A$, $B\mapsto B$, $C\mapsto C$.

Let $a(m, n)$ be the number of different three-object Amidakujis that have $m$ rungs between $A$ and $B$, and $n$ rungs between $B$ and $C$, and whose outcome is the identity permutation. For example, $a(3, 3) = 2$, because the Amidakuji shown above and its mirror image are the only ones with the required property.

You are also given that $a(123, 321) \equiv 172633303 \pmod{1234567891}$.

Find $a(123456789, 987654321)$. Give your answer modulo $1234567891$.

### 837. 阿弥陀签

[阿弥陀签](https://en.wikipedia.org/wiki/Amidakuji)（亦称为画鬼脚）是为一组物体产生一个随机排列的方法。

开始时，我们绘制一组相互平行的竖直线，每个物体都对应一条竖直线。然后我们绘制若干水平线段来连接某一组相邻的竖直线。每一条水平线段都要严格低于其上方的线段。

例如，下面这张图描述了一张阿弥陀签。这张阿弥陀签共有三条分别代表物体 $A, B, C$ 的竖直线和六条水平线。

![](https://pe.xiaoyaowudi.com/resources/images/0837_amidakuji.png?1678992054)

上图中，红、绿、蓝色的线条阐释了产生排列的方法：对于某个物体，我们从代表它的那条竖直线的顶端开始沿绘制的线下行。一旦遇到横线，就沿横线方向继续行进。最终记录下我们最终所处的那条竖直线。在此例中，最终产生的排列碰巧就是原排列：$A\mapsto A$、$B\mapsto B$、$C\mapsto C$。

记 $a(m, n)$ 为满足如下条件的不同的阿弥陀签的数量：共有三条分别代表物体 $A, B, C$ 的竖直线，$A$、$B$ 之间的竖直线有 $m$ 条水平线，$B$、$C$ 之间的竖直线有 $n$ 条水平线且其最终产生的排列就是缘排列。已知：$a(3, 3) = 2$。这两个阿弥陀签分别是上图中的阿弥陀签与其镜像。亦已知：$a(123, 321) \equiv 172633303 \pmod{1234567891}$。

求 $a(123456789, 987654321)$ 模 $1234567891$ 之值。