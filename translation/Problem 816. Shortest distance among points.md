### [816. Shortest distance among points](https://pe.xiaoyaowudi.com/problem=816)

We create an array of points $P_n$ in a two dimensional plane using the following random number generator:

$s_0=290797$
$s_{n+1}={s_n}^2 \bmod 50515093$

$P_n=(s_{2n},s_{2n+1})$

Let $d(k)$  be the shortest distance of any two (distinct) points among $P_0, \cdots, P_{k - 1}$.
E.g. $d(14)=546446.466846479$

Find $d(2000000)$. Give your answer rounded to 9 places after the decimal point.

### 816. 平面点对最短距离

在某二维平面中，我们通过如下方式随机生成一组点列 $P_n$：

$s_0=290797$
$s_{n+1}={s_n}^2 \bmod 50515093$

$P_n=(s_{2n},s_{2n+1})$

记 $d(k)$ 为 $P_0, \cdots, P_{k - 1}$ 中互异点对的最短距离。如 $d(14)=546446.466846479$。

求 $d(2000000)$。将你的答案四舍五入至小数点后第 9 位。
