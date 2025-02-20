### [880. Nested Radicals](https://projecteuler.net/problem=880)

$(x,y)$ is called a *nested radical pair* if $x$ and $y$ are non-zero integers such that $\dfrac{x}{y}$ is not a cube of a rational number, and there exist integers $a$, $b$ and $c$ such that:

$$
\sqrt{\sqrt[3]{x}+\sqrt[3]{y}}=\sqrt[3]{a}+\sqrt[3]{b}+\sqrt[3]{c}
$$

For example, both $(-4,125)$ and $(5,5324)$ are nested radical pairs:

$$
\begin{align*}
\begin{split}
\sqrt{\sqrt[3]{-4}+\sqrt[3]{125}} = \sqrt[3]{-1}+\sqrt[3]{2}+\sqrt[3]{4}\\
\sqrt{\sqrt[3]{5}+\sqrt[3]{5324}} = \sqrt[3]{-2}+\sqrt[3]{20}+\sqrt[3]{25}\\
\end{split}
\end{align*}
$$

Let $H(N)$ be the sum of $|x|+|y|$ for all the nested radical pairs $(x, y)$ where $|x| \leq |y|\leq N$. 
For example, $H(10^3)=2535$.

Find $H(10^{15})$. Give your answer modulo $1031^3+2$.

### 880. 嵌套根式

若非零整数 $x, y$ 满足：$\dfrac{x}{y}$ 不是某有理数的立方，且存在正整数 $a$、$b$、$c$ 使得：

$$
\sqrt{\sqrt[3]{x}+\sqrt[3]{y}}=\sqrt[3]{a}+\sqrt[3]{b}+\sqrt[3]{c}
$$

则称 $(x, y)$ 是一个 *嵌套根式对*。例如，因为如下等式成立，所以 $(-4,125)$ 和 $(5,5324)$ 都是嵌套根式对。

$$
\begin{align*}
\begin{split}
\sqrt{\sqrt[3]{-4}+\sqrt[3]{125}} = \sqrt[3]{-1}+\sqrt[3]{2}+\sqrt[3]{4}\\
\sqrt{\sqrt[3]{5}+\sqrt[3]{5324}} = \sqrt[3]{-2}+\sqrt[3]{20}+\sqrt[3]{25}\\
\end{split}
\end{align*}
$$

记 $H(N)$ 为所有满足 $|x| \leq |y|\leq N$ 的嵌套根式对 $(x, y)$ 的 $|x|+|y|$ 之和。已知 $H(10^3)=2535$。

求 $H(10^{15})$ 模 $(1031^3+2)$ 之值。


---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。