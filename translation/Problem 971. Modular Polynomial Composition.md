### [971. Modular Polynomial Composition](https://projecteuler.net/problem=971)

Let $p$ be a prime of the form $5k-4$ and define $f_p(x) = \left(x^k+x\right) \bmod p$.

Let $C(p)$ be the number of values $0 \le x \lt p$ such that $f_p^{(m)}(x) = x$ for some positive integer $m$, that is, $x$ can be obtained by iteratively applying $f_p$ on itself starting at $x$.

For example, $C(11) = 7$, due to $x = 0, 1, 2, 3, 8, 9, 10$.

Let $S(N)$ be the sum of $C(p)$ for all primes of the form $5k-4$ not exceeding $N$. For example $S(100) = 127$.

Find $S(10^8)$.

### 971. 模意义下多项式复合

取一 $5k - 4$ 型质数 $p$，并定义 $f_p(x) = (x^k + x) \bmod p$。

记 $C(p)$ 为满足如下条件的 $x$ 的个数：$0 \le x \lt p$，且存在正整数 $m$ 使得 $f_p^{(m)}(x) = x$（也就是说，从 $x$ 出发反复迭代应用 $f_p$，最终能回到 $x$）。

例如 $C(11) = 7$，因满足条件的 $x$ 有 $0, 1, 2, 3, 8, 9, 10$。

记 $S(N)$ 为所有 $C(p)$ 之和，其中 $p$ 取遍 $\leq N$ 的 $5k-4$ 型质数。例如 $S(100) = 127$。

求 $S(10^8)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。