### [894. Spiral of Circles](https://projecteuler.net/problem=894)

Consider a unit circle $C_0$ on the plane that does not enclose the origin. For $k\ge 1$, a circle $C_k$ is created by scaling and rotating $C_{k - 1}$ <b>with respect to the origin</b>. That is, both the radius and the distance to the origin are scaled by the same factor, and the centre of rotation is the origin. The scaling factor is positive and strictly less than one. Both it and the rotation angle remain constant for each $k$.

It is given that $C_0$ is externally tangent to $C_1$, $C_7$ and $C_8$, as shown in the diagram below, and no two circles overlap.

<div style="text-align:center;"><img src="resources/images/0894_circle_spiral.jpg?1714305246" alt="0894_circle_spiral.jpg"></div>

Find the total area of all the circular triangles. Give your answer rounded to $10$ places after the decimal point.

### 894. 圆的螺旋

在某平面内，我们任取一个不包围原点的单位圆 $C_0$，并按如下过程作出一系列的圆：对 $k \geq 1$，我们先把 $C_{k - 1}$ 进行缩放，将其半径、圆心到原点的距离均变为原来的 $t$ 倍 ($t < 1$)；随后将该圆旋转某固定角度 $\theta$，得到新圆 $C_k$。

现已知存在某 $(t, \theta)$，使得在这组参数下生成的一系列圆中，所有圆两两不相交，且 $C_0$ 和 $C_1, C_7, C_8$ 外切。最终的图形如下图所示。

<div style="text-align:center;"><img src="resources/images/0894_circle_spiral.jpg?1714305246" alt="0894_circle_spiral.jpg"></div>

求出上图中，所有绿色的弧形三角形的面积之和，将你的答案四舍五入至小数点后第 10 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。