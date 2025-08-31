### [797. Cyclogenic Polynomials](https://projecteuler.net/problem=797)

A *monic polynomial* is a single-variable polynomial in which the coefficient of highest degree is equal to 1.

Define $\mathcal{F}$ to be the set of all monic polynomials with integer coefficients (including the constant polynomial $p(x)=1$). A polynomial $p(x)\in\mathcal{F}$ is *cyclogenic* if there exists $q(x)\in\mathcal{F}$ and a positive integer $n$ such that $p(x)q(x)=x^n-1$. If $n$ is the smallest such positive integer then $p(x)$ is $n$*-cyclogenic*.

Define $P_n(x)$ to be the sum of all $n$-cyclogenic polynomials. For example, there exist ten 6-cyclogenic polynomials (which divide $x^6-1$ and no smaller $x^k-1$):
$$
\begin{align*}
& x^6-1 &  & x^4+x^3-x-1 &  & x^3+2x^2+2x+1 &  & x^2-x+1\\
 & x^5+x^4+x^3+x^2+x+1 &  & x^4-x^3+x-1 &  & x^3-2x^2+2x-1\\
 & x^5-x^4+x^3-x^2+x-1 &  & x^4+x^2+1 &  & x^3+1
\end{align*}
$$
giving
$$
P_6(x)=x^6+2x^5+3x^4+5x^3+2x^2+5x
$$
Also define
$$Q_N(x)=\sum_{n=1}^N P_n(x)$$
It's given that
$Q_{10}(x)=x^{10}+3x^9+3x^8+7x^7+8x^6+14x^5+11x^4+18x^3+12x^2+23x$ and $Q_{10}(2) = 5598$.

Find $Q_{10^7}(2)$. Give your answer modulo $1\,000\,000\,007$.

### 797. 可成圆多项式[^1]

*首 1 多项式*，是最高次数项的系数为 1 的单变元多项式。

记 $\mathcal{F}$ 为所有整系数首 1 多项式的集合（包括常项式 $p(x)=1$）。若多项式 $p(x)\in\mathcal{F}$ 满足：存在多项式 $q(x)\in\mathcal{F}$ 与正整数 $n$ 使得 $p(x)q(x)=x^n-1$ 成立，则称 $p(x)$ 是*可成圆的*多项式。如果上述等式里 $n$ 是最小的可使等式成立的正整数，则称 $p(x)$ 是 $n$*-可成圆的*多项式。


记 $P_n(x)$ 为所有 $n$*-可成圆的*多项式之和。例如，共有 10 个 6-可成圆的多项式（可整除 $x^6-1$，不可整除 $k$ 更小的 $x^k-1$）：
$$
\begin{align*}
& x^6-1 &  & x^4+x^3-x-1 &  & x^3+2x^2+2x+1 &  & x^2-x+1\\
 & x^5+x^4+x^3+x^2+x+1 &  & x^4-x^3+x-1 &  & x^3-2x^2+2x-1\\
 & x^5-x^4+x^3-x^2+x-1 &  & x^4+x^2+1 &  & x^3+1
\end{align*}
$$

从而：

$$
P_6(x)=x^6+2x^5+3x^4+5x^3+2x^2+5x
$$

再记：

$$
Q_N(x)=\sum_{n=1}^N P_n(x)
$$

已知 $Q_{10}(x)=x^{10}+3x^9+3x^8+7x^7+8x^6+14x^5+11x^4+18x^3+12x^2+23x$ 且 $Q_{10}(2) = 5598$。

求 $Q_{10^7}(2)$ 模 $1\,000\,000\,007$ 之值。

[^1]: 标题翻译参照数学中的「分圆多项式 / 割圆多项式 (cyclotomic polynomial)」。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。