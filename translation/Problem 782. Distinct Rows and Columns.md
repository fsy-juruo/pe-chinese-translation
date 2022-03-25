### 782. Distinct Rows and Columns

The *complexity* of an $n\times n$ binary matrix is the number of distinct rows and columns.

For example, consider the $3\times 3$ matrices
$$
\mathbf{A} = 
\begin{pmatrix}
1 \quad 0 \quad 1 \\
0 \quad 0 \quad 0 \\
1 \quad 0 \quad 1 \\
\end{pmatrix}

\quad 
\mathbf{B} = 
\begin{pmatrix}
0 \quad 0 \quad 0 \\
0 \quad 0 \quad 0 \\
1 \quad 1 \quad 1 \\
\end{pmatrix}
$$
$\mathbf{A}$ has complexity 2 because the set of rows and columns is $\{000,101\}$.
$\mathbf{B}$ has complexity 3 because the set of rows and columns is $\{000,001,111\}$.

For $0 \le k \le n^2$, let $c(n, k)$ be the **minimum** complexity of an $n\times n$ binary matrix with exactly $k$ ones.

Let
$$C(n) = \sum_{k=0}^{n^2} c(n, k)$$
For example, $C(2) = c(2, 0) + c(2, 1) + c(2, 2) + c(2, 3) + c(2, 4) = 1 + 2 + 2 + 2 + 1 = 8$.
You are given $C(5) = 64$, $C(10) = 274$ and $C(20) = 1150$.

Find $C(10^4)$.

### 782. 不同的行与列

对于任意 $n \times n$ 二元 01 矩阵，我们定义其*复杂度*为其每一行，每一列所组成的不同二进制串的数量。

举个例子，考虑如下两个 $3 \times 3$ 01 矩阵：
$$
\mathbf{A} = 
\begin{pmatrix}
1 \quad 0 \quad 1 \\
0 \quad 0 \quad 0 \\
1 \quad 0 \quad 1 \\
\end{pmatrix}

\quad 
\mathbf{B} = 
\begin{pmatrix}
0 \quad 0 \quad 0 \\
0 \quad 0 \quad 0 \\
1 \quad 1 \quad 1 \\
\end{pmatrix}
$$
$\mathbf{A}$ 的复杂度为 2，不同二进制串的集合为 $\{000,101\}$。
$\mathbf{B}$ 的复杂度为 3，不同二进制串的集合为 $\{000,001,111\}$。

对于 $0 \le k \le n^2$，令  $c(n, k)$ 为所有恰好含有 $k$ 个 1 的 $n \times n$ 01 矩阵中，复杂度的**最小值**。

再令：
$$C(n) = \sum_{k=0}^{n^2} c(n, k)$$
举个例子，$C(2) = c(2, 0) + c(2, 1) + c(2, 2) + c(2, 3) + c(2, 4) = 1 + 2 + 2 + 2 + 1 = 8$。已知 $C(5) = 64$，$C(10) = 274$，$C(20) = 1150$。

求 $C(10^4)$。