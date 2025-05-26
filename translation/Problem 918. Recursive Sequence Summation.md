### [918. Recursive Sequence Summation](https://projecteuler.net/problem=918)

The sequence $a_n$ is defined by $a_1=1$, and then recursively for $n\geq1$:
$$
\begin{align*}
a_{2n}  &= 2a_n\\
a_{2n+1} &= a_n-3a_{n+1}
\end{align*}
$$

The first ten terms are $1, 2, -5, 4, 17, -10, -17, 8, -47, 34$.  
Define $\displaystyle S(N) = \sum_{n=1}^N a_n$. You are given $S(10) = -13$  
Find $S(10^{12})$.

### 918. 递归数列求和

我们按如下规则定义数列 $\{a_n\}$：$a_1 = 1$，并对 $n \geq 1$ 递归定义：

$$
\begin{align*}
a_{2n}  &= 2a_n\\
a_{2n+1} &= a_n-3a_{n+1}
\end{align*}
$$

该数列的前 $10$ 项是 $1, 2, -5, 4, 17, -10, -17, 8, -47, 34$。

记 $\displaystyle S(N) = \sum_{n=1}^N a_n$，已知 $S(10) = -13$。

求 $S(10^{12})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。