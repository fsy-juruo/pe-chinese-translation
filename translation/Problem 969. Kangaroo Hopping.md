### [969. Kangaroo Hopping](https://projecteuler.net/problem=969)

Starting at zero, a kangaroo hops along the real number line in the positive direction. Each successive hop takes the kangaroo forward a uniformly random distance between $0$ and $1$. Let $H(n)$ be the expected number of hops needed for the kangaroo to pass $n$ on the real line.

If we write $\alpha = H(1)$, then for all positive integers $n$, $H(n)$ can be expressed as a polynomial function of $\alpha$ with rational coefficients. For example $H(3)=\alpha^3-2\alpha^2+\frac{1}{2}\alpha$. Define $S(n)$ to be the sum of all **integer** coefficients in this polynomial form of $H(n)$. Therefore $S(1)=1$ and $S(3)=1+(-2)=-1$.  
You are also given $\displaystyle \sum_{n=1}^{10} S(n)=43$.  
Find $\displaystyle\sum_{n=1}^{10^{18}} S(n)$. Give your answer modulo $10^9+7$.

### 969. 袋鼠的跳跃

一只袋鼠正以一数轴的原点为起点，沿着数轴的正半轴方向跳跃。这只袋鼠每次跳跃的距离服从 $[0, 1]$ 上的均匀分布。记 $H(n)$ 为：袋鼠经过数轴上代表 $n$ 的点时，跳跃次数的期望。

若记 $\alpha = H(1)$，那么对诸正整数 $n$，$H(n)$ 可以被写作 $\alpha$ 的多项式，且该多项式的各项系数都是有理数。例如，$H(3)=\alpha^3-2\alpha^2+\frac{1}{2}\alpha$。记 $S(n)$ 为 $H(n)$ 中所有 **整数** 系数之和，从而有 $S(1)=1$、$S(3)=1+(-2)=-1$。

亦已知 $\displaystyle \sum_{n=1}^{10} S(n)=43$。

求 $\displaystyle\sum_{n=1}^{10^{18}} S(n)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
