### [769. Binary Quadratic Form II](https://projecteuler.net/problem=769)

Consider the following binary quadratic form:
$$
\begin{align}
f(x,y)=x^2+5xy+3y^2
\end{align}
$$
A positive integer $q$ has a primitive representation if there exist positive integers $x$ and $y$ such that $q = f(x,y)$ and $\gcd(x,y)=1$.

We are interested in primitive representations of perfect squares. For example:  
$17^2=f(1,9)$  
$87^2=f(13,40) = f(46,19)$

Define $C(N)$ as the total number of primitive representations of $z^2$ for $0 < z \leq N$.  
Multiple representations are counted separately, so for example $z=87$ is counted twice.

You are given $C(10^3)=142$ and $C(10^{6})=142463$

Find $C(10^{14})$.

### 769. 二元二次表示法 II

考虑如下的二元二次表示法：
$$
\begin{align}
f(x,y)=x^2+5xy+3y^2
\end{align}
$$

若存在正整数 $x, y$ 使得 $q = f(x, y)$ 且 $\gcd(x, y) = 1$，则称正整数 $q$ 存在本原表示。

我们对完全平方数的本原表示很感兴趣，例如：  
$17^2=f(1,9)$  
$87^2=f(13,40) = f(46,19)$

记 $C(N)$ 为所有在 $[1, N^2]$ 内的完全平方数的本原表示数量的总和。如 $C(10^3)=142$、$C(10^{6})=142463$。不同的表示方法计算多次，如 $87^2$ 的两种本原表示应被计为 2 次。

求 $C(10^{14})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。