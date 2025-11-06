### [764. Asymmetric Diophantine Equation](https://projecteuler.net/problem=764)

Consider the following Diophantine equation:
$$
16x^2+y^4=z^2
$$
where $x$, $y$ and $z$ are positive integers.

Let $S(N) = \displaystyle{\sum(x+y+z)}$ where the sum is over all solutions $(x,y,z)$ such that $1 \leq x,y,z \leq N$ and $\gcd(x,y,z)=1$. 

For $N=100$, there are only two such solutions: $(3,4,20)$ and $(10,3,41)$. So $S(10^2)=81$.

You are also given that $S(10^4)=112851$ (with $26$ solutions), and $S(10^7)\equiv 248876211 \pmod{10^9}$.

Find $S(10^{16})$. Give your answer modulo $10^9$.

### 764. 不对称丢番图方程

考察如下丢番图方程，其中 $x$、$y$、$z$ 均是正整数：

$$
16x^2+y^4=z^2
$$

记 $S(N) = \displaystyle{\sum(x+y+z)}$，其中 $(x, y, z)$ 取遍上述方程所有满足 $1 \leq x,y,z \leq N$ 且 $\gcd(x,y,z)=1$ 的解。

$N = 100$ 时，只有两组解满足要求：$(3,4,20)$ 和 $(10,3,41)$，于是 $S(10^2) = 81$。

你还已知 $S(10^4)=112851$（有 $26$ 组符合要求的解）且 $S(10^7) \equiv 248876211 \pmod{10^9}$。

求 $S(10^{16})$ 模 $10^9$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
