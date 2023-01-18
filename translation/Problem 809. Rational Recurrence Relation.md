### [809. Rational Recurrence Relation](https://pe.xiaoyaowudi.com/problem=809)

The following is a function defined for all positive rational values of $x$.

$$
f(x)=\begin{cases} x  & x\text{ is integral}\\
f(\frac 1{1-x})	& x \lt 1\\
f\Big(\frac 1{\lceil x\rceil -x}-1+f(x-1)\Big)	& \text{otherwise}\end{cases}
$$

For example, $f(3/2)=3$, $f(1/6) = 65533$ and $f(13/10) = 7625597484985$.

Find $f(22/7)$. Give your answer modulo $10^{15}$.

### 809. 有理数上的递归关系

对于所有正实数 $x$ 定义如下函数：

$$
f(x)=\begin{cases} x  & x\text{ is integral}\\
f(\frac 1{1-x})	& x \lt 1\\
f\Big(\frac 1{\lceil x\rceil -x}-1+f(x-1)\Big)	& \text{otherwise}\end{cases}
$$

例如 $f(3/2)=3$，$f(1/6) = 65533$ 且 $f(13/10) = 7625597484985$。

求 $f(22/7)$ 模 $10^{15}$ 之值。