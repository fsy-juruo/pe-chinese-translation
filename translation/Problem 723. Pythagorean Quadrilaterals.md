### [723. Pythagorean Quadrilaterals](https://projecteuler.net/problem=723)

A pythagorean triangle with catheti $a$ and $b$ and hypotenuse $c$ is characterized by the well-known equation $a^2+b^2=c^2$. However, this can also be formulated differently:

When inscribed into a circle with radius $r$, a triangle with sides $a$, $b$ and $c$ is pythagorean, if and only if $a^2+b^2+c^2=8\, r^2$.

Analogously, we call a quadrilateral $ABCD$ with sides $a$, $b$, $c$ and $d$, inscribed in a circle with radius $r$, a *pythagorean quadrilateral*, if $a^2+b^2+c^2+d^2=8\, r^2$. 

We further call a pythagorean quadrilateral a *pythagorean lattice grid quadrilateral*, if all four vertices are lattice grid points with the same distance $r$ from the origin $O$ (which then happens to be the centre of the circumcircle).

Let $f(r)$ be the number of different pythagorean lattice grid quadrilaterals for which the radius of the circumcircle is $r$. For example $f(1)=1$, $f(\sqrt 2)=1$, $f(\sqrt 5)=38$ and $f(5)=167$.

Two of the pythagorean lattice grid  quadrilaterals with $r=\sqrt 5$ are illustrated below:

![](https://pe.xiaoyaowudi.com/resources/images/0723_1.png?1678992054)

![](https://pe.xiaoyaowudi.com/resources/images/0723_2.png?1678992054)

Let $\displaystyle S(n)=\sum_{d \vert n} f(\sqrt d)$. For example, $S(325)=S(5^2 \cdot 13)=f(1)+f(\sqrt 5)+f(5)+f(\sqrt {13})+f(\sqrt{65})+f(5\sqrt{13})=2370$ and $S(1105)=S(5\cdot 13 \cdot 17)=5535$.

Find $S(1411033124176203125)=S(5^6 \cdot 13^3 \cdot 17^2 \cdot 29 \cdot 37 \cdot 41 \cdot 53 \cdot 61)$.

### 723. 毕达哥拉斯四边形

以 $a$，$b$ 为直角边，$c$ 为斜边的直角三角形有一个鲜明的特征：符合大名鼎鼎的勾股定理 $a^2+b^2=c^2$。然而，勾股定理还有另一种表述的方法：若一个三角形边长分别为 $a$、$b$、$c$，且这个三角形内接于一个半径为 $r$ 的圆，那么当且仅当 $a^2+b^2+c^2=8\,r^2$ 时，这个三角形是直角三角形。

类似的，若一个四边形边长分别为 $a$、$b$、$c$、$d$，且这个四边形内接于一个半径为 $r$ 的圆。若 $a^2+b^2+c^2+d^2=8\,r^2$，我们就称这个四边形为*毕达哥拉斯四边形*。进一步地，以该圆外心为原点，建立平面直角坐标系。定义*毕达哥拉斯格点四边形*为四个点均为格点的毕达哥拉斯四边形。

记 $f(r)$ 为外接圆半径为 $r$ 时，不同的毕达哥拉斯格点四边形的个数。已知：$f(1)=1$、$f(\sqrt 2)=1$、$f(\sqrt 5)=38$ 且 $f(5)=167$。

下图是两个外接圆半径为 $\sqrt 5$ 时的毕达哥拉斯格点四边形。

![](https://pe.xiaoyaowudi.com/resources/images/0723_1.png?1678992054)

![](https://pe.xiaoyaowudi.com/resources/images/0723_2.png?1678992054)

记 $\displaystyle S(n)=\sum_{d \vert n} f(\sqrt d)$。已知： $S(325)=S(5^2 \cdot 13)=f(1)+f(\sqrt 5)+f(5)+f(\sqrt {13})+f(\sqrt{65})+f(5\sqrt{13})=2370$ 且 $S(1105)=S(5\cdot 13 \cdot 17)=5535$。

求 $S(1411033124176203125)=S(5^6 \cdot 13^3 \cdot 17^2 \cdot 29 \cdot 37 \cdot 41 \cdot 53 \cdot 61)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。