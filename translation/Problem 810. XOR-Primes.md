### [810. XOR-Primes](https://projecteuler.net/problem=810)

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

An *XOR-prime* is an integer $n$ greater than $1$ that is not an XOR-product of two integers greater than $1$. The above example shows that $9$ is not an XOR-prime. Similarly, $5 = 3 \otimes 3$ is not an XOR-prime. The first few XOR-primes are $2, 3, 7, 11, 13, ...$ and the 10th XOR-prime is $41$.

Find the $5\,000\,000$th XOR-prime.

### 810. 异或质数

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

定义 *异或质数* 为大于 $1$ 且不能写成两个大于 $1$ 的正整数之异或乘积的整数。故由上即知 $9$ 不是异或质数。较小的一些异或质数为 $2, 3, 7, 11, 13, ...$，第 10 个异或质数为 $41$。

求第 $5\,000\,000$ 个异或质数。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

