### [802. Iterated Composition](https://pe.xiaoyaowudi.com/problem=802)

Let $\Bbb R^2$ be the set of pairs of real numbers $(x, y)$. Let $\pi = 3.14159\cdots\ $.

Consider the function $f$ from $\Bbb R^2$ to $\Bbb R^2$ defined by $f(x, y) = (x^2 - x - y^2, 2xy - y + \pi)$, and its $n$-th iterated composition $f^{(n)}(x, y) = f(f(\cdots f(x, y)\cdots))$. For example $f^{(3)}(x, y) = f(f(f(x, y)))$. A pair $(x, y)$ is said to have period $n$ if $n$ is the smallest positive integer such that $f^{(n)}(x, y) = (x, y)$.

Let $P(n)$ denote the sum of $x$-coordinates of all points having period not exceeding $n$.
Interestingly, $P(n)$ is always an integer. For example, $P(1) = 2$, $P(2) = 2$, $P(3) = 4$.

Find $P(10^7)$ and give your answer modulo $1\,020\,340\,567$.

### 802. 迭代复合

记 $\Bbb R^2$ 为所有实数二元组的集合。取 $\pi = 3.14159\cdots\ $。

考虑一个函数 $f: \Bbb R^2 \rightarrow \Bbb R^2$，其转换法则为 $f(x, y) = (x^2 - x - y^2, 2xy - y + \pi)$。记此函数的 $n$ 次复合 $f^{(n)}(x, y) = f(f(\cdots f(x, y)\cdots))$，例如 $f^{(3)}(x, y) = f(f(f(x, y)))$。如果某二元组 $(x, y)$ 满足 $f^{(n)}(x, y) = (x, y)$，则记满足此等式的最小正整数 $n$ 为该二元组的周期。

记 $P(n)$ 为满足下述条件的实数之和：以该实数为 $x$ 坐标的所有点的周期均不超过 $n$。有意思的是，$P(n)$ 一直是整数。如 $P(1) = 2$, $P(2) = 2$, $P(3) = 4$。

求 $P(10^7)$ 模 $1\,020\,340\,567$ 之值。