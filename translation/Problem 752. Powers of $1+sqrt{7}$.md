### [752. Powers of $1 + \sqrt{7}$](https://projecteuler.net/problem=752)

When $(1+\sqrt 7)$ is raised to an integral power, $n$, we always get a number of the form $(a+b\sqrt 7)$.  
We write $(1+\sqrt 7)^n = \alpha(n) + \beta(n)\sqrt 7$.

For a given number $x$ we define $g(x)$ to be the smallest positive integer $n$ such that:
$$
\begin{align}
\alpha(n) &\equiv 1 \pmod x\qquad \text{and }\\
\beta(n) &\equiv 0 \pmod x
\end{align}
$$
and $g(x) = 0$ if there is no such value of $n$. For example, $g(3) = 0$, $g(5) = 12$.

Further define
$$
G(N) = \sum_{x=2}^N g(x)
$$
You are given $G(10^2) = 28891$ and $G(10^3)  = 13131583$.

Find $G(10^6)$.

### 752. $1 + \sqrt{7}$ 的幂

对任意正整数 $n$，$(1 + \sqrt{7})$ 的 $n$ 次幂一定形如 $(a + b \sqrt{7})$。  
我们记 $(1+\sqrt 7)^n = \alpha(n) + \beta(n)\sqrt 7$（其中 $\alpha(n), \beta(n)$ 是整数）。

给定 $x$，我们定义 $g(x)$ 为满足如下条件的最小正整数 $n$：

$$
\begin{align}
\alpha(n) &\equiv 1 \pmod x\qquad \text{and }\\
\beta(n) &\equiv 0 \pmod x
\end{align}
$$

若没有满足条件的正整数，则置 $g(x) = 0$。例如有 $g(3) = 0$、$g(5) = 12$。

进一步定义：
$$
G(N) = \sum_{x=2}^N g(x)
$$

已知 $G(10^2) = 28891$、$G(10^3)  = 13131583$。

求 $G(10^6)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
