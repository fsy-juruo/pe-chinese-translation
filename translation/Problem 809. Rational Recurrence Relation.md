### [809. Rational Recurrence Relation](https://projecteuler.net/problem=809)

The following is a function defined for all positive rational values of $x$.

$$
f(x)=\begin{cases} x  & x\text{ is integral}\\
f(\frac 1{1-x})	& x \lt 1\\
f\Big(\frac 1{\lceil x\rceil -x}-1+f(x-1)\Big)	& \text{otherwise}\end{cases}
$$

For example, $f(3/2)=3$, $f(1/6) = 65533$ and $f(13/10) = 7625597484985$.

Find $f(22/7)$. Give your answer modulo $10^{15}$.

### 809. 有理数上的递归关系

定义如下函数，其定义域为全体正实数：

$$
f(x)=\begin{cases} x  & x\text{ 是整数.}\\
f(\frac 1{1-x})	& x \lt 1\\
f\Big(\frac 1{\lceil x\rceil -x}-1+f(x-1)\Big)	& \text{其他情况.}\end{cases}
$$

例如 $f(3/2)=3$、$f(1/6) = 65533$ 且 $f(13/10) = 7625597484985$。

求 $f(22/7)$ 模 $10^{15}$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。