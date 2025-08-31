### [878. XOR-Equation B](https://projecteuler.net/problem=878)

We use $x\oplus y$ for the bitwise XOR of $x$ and $y$.  
Define the *XOR-product* of $x$ and $y$, denoted by $x \otimes y$, similar to a long multiplication in base $2$, except that the intermediate results are XORed instead of the usual integer addition.  

For example, $7 \otimes 3 = 9$, or in base $2$, $111_2 \otimes 11_2 = 1001_2$:

$$
\begin{align*}
\phantom{\otimes 111} 111_2 \\
\otimes \phantom{1111} 11_2 \\
\hline
\phantom{\otimes 111} 111_2 \\
\oplus \phantom{11} 111_2  \phantom{9} \\
\hline
\phantom{\otimes 11} 1001_2 \\
\end{align*}
$$

We consider the equation:

$$
\begin{align}
(a \otimes a) \oplus (2 \otimes a \otimes b) \oplus (b \otimes b) = k.
\end{align}
$$

For example, $(a, b) = (3, 6)$ is a solution to this equation for $k=5$.

Let $G(N,m)$ be the number of solutions to those equations with $k \le m$ and $0 \le a \le b \le N$.

You are given $G(1000,100)=398$.

Find $G(10^{17},1\,000\,000).$

### 878. 异或方程 2

我们记 $x\oplus y$ 为 $x$ 与 $y$ 按位异或的结果。

我们定义 $x$ 与 $y$ 的 *异或乘积* $x \otimes y$ 如下：在列竖式进行二进制乘法时，其他步骤不变，只在最后得出结果时，将算出的每一列中的数字进行异或，而非原来的二进制加法。

例如，$7 \otimes 3 = 9$。或将此等式表示为二进制为 $111_2 \otimes 11_2 = 1001_2$。其计算过程如下：
$$
\begin{align*}
\phantom{\otimes 111} 111_2 \\
\otimes \phantom{1111} 11_2 \\
\hline
\phantom{\otimes 111} 111_2 \\
\oplus \phantom{11} 111_2  \phantom{9} \\
\hline
\phantom{\otimes 11} 1001_2 \\
\end{align*}
$$

考虑方程：

$$
\begin{align}
(a \otimes a) \oplus (2 \otimes a \otimes b) \oplus (b \otimes b) = k
\end{align}
$$

例如，$k=5$ 时，$(a, b) = (3, 6)$ 是原方程的一组解。

记 $G(N,m)$ 为该方程满足 $k \le m$、$0 \le a \le b \le N$ 的解的数量。已知 $G(1000,100)=398$。

求 $G(10^{17},1\,000\,000)$。


---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

