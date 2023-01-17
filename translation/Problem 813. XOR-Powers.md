### [813. XOR-Powers](https://pe.xiaoyaowudi.com/problem=813)

We use $x\oplus y$ to be the bitwise XOR of $x$ and $y$.

Define the *XOR-product* of $x$ and $y$, denoted by $x \otimes y$, similar to a long multiplication in base $2$, except that the intermediate results are XORed instead of the usual integer addition.

For example, $11 \otimes 11 = 69$, or in base $2$, $1011_2 \otimes 1011_2 = 1000101_2$:
$$
\begin{align*}
\phantom{\otimes 1111} 1011_2 \\
\otimes \phantom{1111} 1011_2 \\
\hline
\phantom{\otimes 1111} 1011_2 \\
\phantom{\otimes 111} 1011_2 \phantom{9} \\
\oplus \phantom{1} 1011_2  \phantom{999} \\
\hline
\phantom{\otimes 11} 1000101_2 \\
\end{align*}
$$
Further we define $P(n) = 11^{\otimes n} = \overbrace{11\otimes 11\otimes \ldots \otimes 11}^n$. For example $P(2)=69$.

Find $P(8^{12}\cdot 12^8)$. Give your answer modulo $10^9+7$.

### 813. 异或幂

我们记 $x\oplus y$ 为 $x$ 与 $y$ 按位异或的结果。

我们定义 $x$ 与 $y$ 的 *异或乘积* $x \otimes y$ 如下：在列竖式进行乘法时，其他步骤不变，只在最后得出结果时，将算出的每一列中的数字进行异或，而非原来的二进制加法。

例如，$11 \otimes 11 = 69$。或将此等式表示为二进制，$1011_2 \otimes 1011_2 = 1000101_2$。计算过程如下：
$$
\begin{align*}
\phantom{\otimes 1111} 1011_2 \\
\otimes \phantom{1111} 1011_2 \\
\hline
\phantom{\otimes 1111} 1011_2 \\
\phantom{\otimes 111} 1011_2 \phantom{9} \\
\oplus \phantom{1} 1011_2  \phantom{999} \\
\hline
\phantom{\otimes 11} 1000101_2 \\
\end{align*}
$$
我们进一步记 $P(n) = 11^{\otimes n} = \overbrace{11\otimes 11\otimes \ldots \otimes 11}^n$。例如 $P(2)=69$。

试求 $P(8^{12}\cdot 12^8)$ 模 $(10^9+7)$。
