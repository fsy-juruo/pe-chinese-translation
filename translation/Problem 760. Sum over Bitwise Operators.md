### [760. Sum over Bitwise Operators](https://projecteuler.net/problem=760)

Define
$$
\displaystyle g(m,n) = (m\oplus n)+(m\vee n)+(m\wedge n)
$$
where $\oplus, \vee, \wedge$ are the bitwise XOR, OR and AND operator respectively.
Also set
$$
\displaystyle G(N) = \sum_{n=0}^N\sum_{k=0}^n g(k,n-k)
$$
For example, $G(10) = 754$ and $G(10^2) = 583766$.

Find $G(10^{18})$. Give your answer modulo $1\,000\,000\,007$.

### 760. 位运算求和

记
$$
\displaystyle g(m,n) = (m\oplus n)+(m\vee n)+(m\wedge n)
$$
其中 $\oplus, \vee, \wedge$ 分别指按位异或、按位或、按位与运算。

另记
$$
\displaystyle G(N) = \sum_{n=0}^N\sum_{k=0}^n g(k,n-k)
$$
例如有 $G(10) = 754$、$G(10^2) = 583766$。

求 $G(10^{18})$ 模 $1\,000\,000\,007$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
