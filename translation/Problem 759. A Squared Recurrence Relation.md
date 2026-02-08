### [759. A Squared Recurrence Relation](https://projecteuler.net/problem=759)

The function $f$ is defined for all positive integers as follows:
$$
\begin{align*}
f(1) &=  1\\
f(2n) &= 2f(n)\\
f(2n+1) &= 2n+1 + 2f(n)+\tfrac 1n f(n)
\end{align*}
$$
It can be proven that $f(n)$ is integer for all values of $n$.

The function $S(n)$ is defined as $S(n) = \displaystyle \sum_{i=1}^n f(i) ^2$.
For example, $S(10)=1530$ and $S(10^2)=4798445$.

Find $S(10^{16})$. Give your answer modulo $1\,000\,000\,007$.

### 759. 递推关系的平方和

一定义在全体正整数上的函数 $f$ 满足下述递推：

$$
\begin{align*}
f(1) &=  1\\
f(2n) &= 2f(n)\\
f(2n+1) &= 2n+1 + 2f(n)+\tfrac 1n f(n)
\end{align*}
$$

可以证明，对诸正整数 $n$，$f(n)$ 都是整数。

定义函数 $S(n) = \displaystyle \sum_{i=1}^n f(i) ^2$。例如 $S(10)=1530$、$S(10^2)=4798445$。

求 $S(10^{16})$ 模 $1\,000\,000\,007$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
