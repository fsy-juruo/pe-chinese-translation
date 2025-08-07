### [877. XOR-Equation A](https://projecteuler.net/problem=877)


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
(a \otimes a) \oplus (2 \otimes a \otimes b) \oplus (b \otimes b) = 5
\end{align}
$$

For example, $(a, b) = (3, 6)$ is a solution.

Let $X(N)$ be the XOR of the $b$ values for all solutions to this equation satisfying $0 \le a \le b \le N$.  
You are given $X(10)=5$.

Find $X(10^{18})$.

### 877. 异或方程 A

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
(a \otimes a) \oplus (2 \otimes a \otimes b) \oplus (b \otimes b) = 5
\end{align}
$$

例如，$(a, b) = (3, 6)$ 是如上方程的一组解。

考虑该方程所有满足 $0 \le a \le b \le N$ 的解，并将这些解的 $b$ 值的异或和记作 $X(N)$。已知：$X(10)=5$。

求 $X(10^{18})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。