### [811. Bitwise Recursion](https://pe.xiaoyaowudi.com/problem=811)

Let $b(n)$ be the largest power of 2 that divides $n$. For example $b(24) = 8$.

Define the recursive function:
$$
\begin{align*}
\begin{split}
A(0) &= 1\\
A(2n) &= 3A(n) + 5A\big(2n - b(n)\big)  \qquad n \gt 0\\
A(2n+1) &= A(n)
\end{split}
\end{align*}
$$
and let $H(t,r) = A\big((2^t+1)^r\big)$.

You are given $H(3,2) = A(81) = 636056$.

Find $H(10^{14}+31,62)$. Give your answer modulo $1\,000\,062\,031$. 

### 811. 逐位递归

记 $b(n)$ 为能整除 $n$ 的最大的 2 的幂，如 $b(24) = 8$。

定义如下递归函数：
$$
\begin{align*}
\begin{split}
A(0) &= 1\\
A(2n) &= 3A(n) + 5A\big(2n - b(n)\big)  \qquad n \gt 0\\
A(2n+1) &= A(n)
\end{split}
\end{align*}
$$
并记 $H(t,r) = A\big((2^t+1)^r\big)$。

已知 $H(3,2) = A(81) = 636056$。

求 $H(10^{14}+31,62)$ 模 $1\,000\,062\,031$ 之值。
