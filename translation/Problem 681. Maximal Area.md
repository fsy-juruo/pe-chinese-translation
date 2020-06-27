### [681. Maximal Area](https://projecteuler.net/problem=681)

Given positive integers $a \le b \le c \le d$, it may be possible to form quadrilaterals with edge lengths $a,b,c,d$ (in any order). When this is the case, let $M(a,b,c,d)$ denote the maximal area of such a quadrilateral. For example, $M(2,2,3,3)=6$, attained e.g. by a $2\times 3$ rectangle.

Let $SP(n)$ be the sum of $a+b+c+d$ over all choices $a \le b \le c \le d$ for which $M(a,b,c,d)$ is a positive integer not exceeding $n$.
$SP(10)=186$ and $SP(100)=23238$.

Find $SP(1\,000\,000)$.

### 681. 最大化面积

给定正整数 $a \le b \le c \le d$，这可能可以形成以 $a,b,c,d$ （顺序任意）为边长的四边形。如果可以形成四边形的话，令 $M(a,b,c,d)$ 为能形成的四边形中面积的最大值。例如，$M(2,2,3,3)=6$，因为这四条边可以围成一个 $2 \times 3$ 的矩形。

令 $SP(n)$ 为所有满足 $M(a, b, c, d) \leq n$ 且 $a \leq b \leq c \leq d$ 的四元组的四个元素之和的和。已知$SP(10)=186$ 且 $SP(100)=23238$。

求 $SP(1\,000\,000)$。

