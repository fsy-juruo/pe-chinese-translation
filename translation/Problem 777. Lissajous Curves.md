### [777. Lissajous Curves](https://projecteuler.net/problem=777)

For coprime positive integers $a$ and $b$, let $C_{a,b}$ be the curve defined by:
$$
\begin{align}
x &= \cos \left(at\right) \\
y &= \cos \left(b\left(t-\frac{\pi}{10}\right)\right)
\end{align}
$$

where $t$ varies between 0 and $2\pi$.

For example, the images below show $C_{2,5}$ (left) and $C_{7,4}$ (right):

![](https://pe.xiaoyaowudi.com/project/images/p777_lissajous-pair-25-74.png)

Define $d(a,b) = \sum (x^2 + y^2)$, where the sum is over all points (x, y) at which $C_{a,b}$ crosses itself.

For example, in the case of $C_{2,5}$ illustrated above, the curve crosses itself at two points: (0.31, 0) and (-0.81, 0), rounding coordinates to two decimal places, yielding $d(2, 5)=0.75$. Some other examples are $d(2,3)=4.5$, $d(7,4)=39.5$, $d(7,5)=52$, and $d(10,7)=23.25$.

Let $s(m) = \sum d(a,b)$, where this sum is over all pairs of coprime integers $a,b$ with $2\le a\le m$ and $2\le b\le m$.
You are given that $s(10) = 1602.5$ and $s(100) = 24256505$.

Find $s(10^6)$. Give your answer in scientific notation rounded to 10 significant digits; for example $s(100)$ would be given as 2.425650500e7.

### 777. 利萨茹曲线

对于互质的两个正整数 $a$、$b$，定义曲线 $C_{a, b}$ 为满足下述参数方程的曲线，其中 $t$ 取遍 $[0, 2 \pi]$：
$$
\begin{align}
x &= \cos \left(at\right) \\
y &= \cos \left(b\left(t-\frac{\pi}{10}\right)\right)
\end{align}
$$

例如，下图左、右两侧分别展示了曲线 $C_{2,5}$ 和 $C_{7, 4}$：

![](https://pe.xiaoyaowudi.com/project/images/p777_lissajous-pair-25-74.png)

记 $d(a, b)$ 为：$C_{a, b}$ 中所有自相交的点 $(x, y)$ 到原点距离的平方的和。即 $d(a, b) = \sum (x^2 + y^2)$。

观察左图，$C_{2, 5}$ 有两个自相交点：$(0.31, 0)$ 和 $(-0.81, 0)$（所有坐标四舍五入到小数点后两位），从而 $d(2, 5) = 0.75$。已知：$d(2, 3) = 4.5$、$d(7, 4) = 39.5$、$d(7, 5) = 52$ 且 $d(10, 7) = 23.25$。

记 $s(m) = \displaystyle\sum_{\substack{2 \leq a, b \leq m \\ a, b \; 互质}} d(a, b)$。已知 $s(10) = 1602.5$、$s(100) = 24256505$。

求 $s(10^6)$。将你的答案用科学记数法表示，并把小数部分四舍五入至第 10 位有效数字。如 $s(100)$ 应被表示为 2.425650500e7。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。