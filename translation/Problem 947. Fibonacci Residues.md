### [947. Fibonacci Residues](https://projecteuler.net/problem=947)

The $(a,b,m)$-sequence, where $0 \leq a,b \lt m$, is defined as

$$
\begin{align*}
g(0) &= a\\
g(1) &= b\\
g(n) &= \big(g(n-1) + g(n-2)\big) \bmod m
\end{align*}
$$

All $(a,b,m)$-sequences are periodic with period denoted by $p(a,b,m)$.  
The first few terms of the $(0,1,8)$-sequence are $(0,1,1,2,3,5,0,5,5,2,7,1,0,1,1,2,\ldots )$ and so $p(0,1,8)=12$.

Let $\displaystyle s(m)=\sum_{a=0}^{m-1}\sum_{b=0}^{m-1} p(a,b,m)^2$. For example, $s(3)=513$ and $s(10)=225820$.

Define $\displaystyle S(M)=\sum_{m=1}^{M}s(m)$. You are given, $S(3)=542$ and $S(10)=310897$.

Find $S(10^6)$. Give your answer modulo $999\,999\,893$.


### 947. 斐波那契余数

对满足 $0 \leq a, b < m$ 的整数 $a, b, m$，定义 $(a, b, m)$-序列如下： 

$$
\begin{align*}
g(0) &= a\\
g(1) &= b\\
g(n) &= \big(g(n-1) + g(n-2)\big) \bmod m
\end{align*}
$$

所有 $(a, b, m)$-序列都是周期数列，记其周期为 $p(a, b, m)$。例如，$(0, 1, 8)$-序列的前若干项是 $(0,1,1,2,3,5,0,5,5,2,7,1,0,1,1,2,\ldots )$，于是 $p(0, 1, 8) = 12$。

记 $\displaystyle s(m)=\sum_{a=0}^{m-1}\sum_{b=0}^{m-1} p(a,b,m)^2$，例如，$s(3)=513$、$s(10)=225820$。

记 $\displaystyle S(M)=\sum_{m=1}^{M}s(m)$。已知 $S(3)=542$、$S(10)=310897$。

求 $S(10^6)$ 模 $999\,999\,893$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。