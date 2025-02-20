### [681. Maximal Area](https://projecteuler.net/problem=681)

Given positive integers $a \le b \le c \le d$, it may be possible to form quadrilaterals with edge lengths $a,b,c,d$ (in any order). When this is the case, let $M(a,b,c,d)$ denote the maximal area of such a quadrilateral. For example, $M(2,2,3,3)=6$, attained e.g. by a $2\times 3$ rectangle.

Let $SP(n)$ be the sum of $a+b+c+d$ over all choices $a \le b \le c \le d$ for which $M(a,b,c,d)$ is a positive integer not exceeding $n$.
$SP(10)=186$ and $SP(100)=23238$.

Find $SP(1\,000\,000)$.

### 681. 最大化面积

给定正整数 $a \le b \le c \le d$，此时，可能存在边长为 $a,b,c,d$ （顺序任意）的四边形，此时记 $M(a,b,c,d)$ 为此类四边形面积的最大值。例如 $M(2,2,3,3)=6$，这个值在形成的四边形为 $2 \times 3$ 的矩形时取到。

记 $SP(n)$ 为所有满足以下条件的四元组 $(a, b, c, d)$ 的 $a + b + c + d$ 之和：$M(a, b, c, d)$ 是 $\leq n$ 的正整数且 $a \leq b \leq c \leq d$。已知：$SP(10)=186$ 且 $SP(100)=23238$。

求 $SP(1\,000\,000)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。