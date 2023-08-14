### [779. Prime Factor and Exponent](https://projecteuler.net/problem=779)

For a positive integer $n \gt 1$, let $p(n)$ be the smallest prime dividing $n$, and let $\alpha(n)$ be its **$p$-adic order**, i.e. the largest integer such that $p(n)^{\alpha(n)}$ divides $n$.

For a positive integer $K$, define the function $f_K(n)$ by:
$$
f_K(n)=\frac{\alpha(n)-1}{(p(n))^K}.
$$

Also define $\overline{f_K}$ by:
$$
\overline{f_K}=\lim_{N \to \infty} \frac{1}{N}\sum_{n=2}^{N} f_K(n).
$$

It can be verified that $\overline{f_1} \approx 0.282419756159$.

Find $\displaystyle \sum_{K=1}^{\infty}\overline{f_K}$. Give your answer rounded to $12$ digits after the decimal point.

### 779. 质因子与其指数

对正整数 $n > 1$，记 $p(n)$ 为 $n$ 的最小质因数，我们称最大的、满足 $p(n)^{\alpha(n)}$ 整除 $n$ 的正整数 $\alpha(n)$ 为 $n$ 的 **$p$-进阶**。

对某正整数 $K$，定义函数 $f_K(n)$ 如下：
$$
f_K(n)=\frac{\alpha(n)-1}{(p(n))^K}.
$$

同时记 $\overline{f_K}$ 如下：
$$
\overline{f_K}=\lim_{N \to \infty} \frac{1}{N}\sum_{n=2}^{N} f_K(n).
$$

我们可以验证 $\overline{f_1} \approx 0.282419756159$。

求 $\displaystyle \sum_{K=1}^{\infty}\overline{f_K}$。将你的答案四舍五入至小数点后第 12 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。