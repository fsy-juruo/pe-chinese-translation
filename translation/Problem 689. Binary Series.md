### [689. Binary Series](https://projecteuler.net/problem=689)

For $0 \le x \lt 1$, define $d_i(x)$ to be the $i$th digit after the binary point of the binary representation of $x$.
For example $d_2(0.25) = 1$, $d_i(0.25) = 0$ for $i \ne 2$.

Let $f(x) = \displaystyle{\sum_{i=1}^{\infty}\frac{d_i(x)}{i^2}}$.

Let $p(a)$ be probability that $f(x) \gt a$, given that $x$ is uniformly distributed between 0 and 1.

Find $p(0.5)$. Give your answer rounded to 8 digits after the decimal point.

### 689. 二进制系列

对于满足 $0 \le x \lt 1$ 的实数 $x$，定义 $d_i(x)$ 为 $x$ 二进制表示下，小数点后第 $i$ 位。
比如说，$d_2(0.25) = 1$，对于 $i \ne 2$，$d_i(0.25) = 0$。

令 $f(x) = \displaystyle{\sum_{i=1}^{\infty}\frac{d_i(x)}{i^2}}$。

令 $p(a)$ 为 $f(x) \gt a$ 的概率，已知 $x$ 在 0 到 1 之间均匀分布。

求 $p(0.5)$。将答案四舍五入至小数点后第 8 位。
