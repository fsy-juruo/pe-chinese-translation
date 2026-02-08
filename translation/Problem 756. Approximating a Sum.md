### [756. Approximating a Sum](https://projecteuler.net/problem=756)

Consider a function $f(k)$ defined for all positive integers $k>0$. Let $S$ be the sum of the first $n$ values of $f$. That is,
$$
S=f(1)+f(2)+f(3)+\cdots+f(n)=\sum_{k=1}^n f(k).
$$

In this problem, we employ randomness to approximate this sum. That is, we choose a random, uniformly distributed, $m$-tuple of positive integers $(X_1,X_2,X_3,\cdots,X_m)$ such that $0=X_0 \lt X_1 \lt X_2 \lt \cdots \lt X_m \leq n$ and calculate a modified sum $S^*$ as follows.
$$
S^* = \sum_{i=1}^m f(X_i)(X_i-X_{i-1})
$$

We now define the error of this approximation to be $\Delta=S-S^*$.

Let $\mathbb{E}(\Delta|f(k),n,m)$ be the expected value of the error given the function $f(k)$, the number of terms $n$ in the sum and the length of random sample $m$.

For example, $\mathbb{E}(\Delta|k,100,50) = 2525/1326 \approx 1.904223$ and $\mathbb{E}(\Delta|\varphi(k),10^4,10^2)\approx 5842.849907$, where $\varphi(k)$ is Euler's totient function.

Find $\mathbb{E}(\Delta|\varphi(k),12345678,12345)$ rounded to six places after the decimal point.

### 756. 近似和式

考虑一个定义在全体正整数上的函数 $f(k)$，记 $S$ 为 $f$ 在前 $n$ 个正整数上的取值之和，也就是：

$$
S=f(1)+f(2)+f(3)+\cdots+f(n)=\sum_{k=1}^n f(k).
$$

本题中，我们引入随机性以估计此和式。也就是说，我们均匀随机地选出一个满足 $0=X_0 \lt X_1 \lt X_2 \lt \cdots \lt X_m \leq n$ 的 $m$ 元正整数组 $(X_1,X_2,X_3,\cdots,X_m)$ 并按下述方式计算近似和 $S^*$：

$$
S^* = \sum_{i=1}^m f(X_i)(X_i-X_{i-1})
$$

我们定义这种近似方式的误差为 $\Delta=S-S^*$。

记 $\mathbb{E}(\Delta|f(k),n,m)$ 为：给定函数 $f(k)$，求和上标 $n$ 和随机样本的长度 $m$ 时，该近似方法误差的期望。

例如，$\mathbb{E}(\Delta|k,100,50) = 2525/1326 \approx 1.904223$、$\mathbb{E}(\Delta|\varphi(k),10^4,10^2)\approx 5842.849907$。其中 $\varphi(k)$ 是欧拉总计函数。

求 $\mathbb{E}(\Delta|\varphi(k),12345678,12345)$ 四舍五入至小数点后第六位的结果。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。