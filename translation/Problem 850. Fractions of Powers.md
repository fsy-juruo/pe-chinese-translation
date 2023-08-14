### [850. Fractions of Powers](https://projecteuler.net/problem=850)

Any positive real number $x$ can be decomposed into integer and fractional parts $\lfloor x \rfloor + \{x\}$, where $\lfloor x \rfloor$ (the floor function) is an integer, and $0\le \{x\} < 1$.

For positive integers $k$ and $n$, define the function
$$
\begin{align}
f_k(n) = \sum_{i=1}^{n}\left\{ \frac{i^k}{n} \right\}
\end{align}
$$
For example, $f_5(10)=4.5$ and $f_7(1234)=616.5$.

Let
$$
\begin{align}
S(N) = \sum_{\substack{k=1 \\ k\text{ odd}}}^{N} \sum_{n=1}^{N}  f_k(n)
\end{align}
$$
You are given that $S(10)=100.5$ and $S(10^3)=123687804$.

Find $\lfloor S(33557799775533) \rfloor$. Give your answer modulo 977676779.

### 850. 幂的小数部分

任何实数 $x$ 均可以表示成 $\lfloor x \rfloor + \{x\}$ 的形式，其中 $\lfloor x \rfloor$ 表示不超过 $x$ 的最大整数，$\{x\}$ 表示 $x$ 的小数部分 $(0 \leq \{x\} < 1)$。

对于正整数 $k$、$n$，定义函数 $f_k(n)$ 如下：
$$
f_k(n) = \sum_{i=1}^{n} \left\{ \dfrac{i^k}{n} \right\}
$$

已知 $f_5(10) = 4.5$ 且 $f_7(1234) = 616.5$。

再记
$$
S(N) = \sum_{\substack{k=1 \\ k 为奇数}}^{N} \sum_{n=1}^{N} f_k(n)
$$
已知 $S(10) = 100.5$ 且 $S(10^3) = 123687804$。

求 $\lfloor S(33557799775533) \rfloor$ 模 $977676779$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。