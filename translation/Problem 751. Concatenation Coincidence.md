### [751. Concatenation Coincidence](https://projecteuler.net/problem=751)

A non-decreasing sequence of integers $a_n$ can be generated from any positive real value $\theta$ by the following procedure:
$$
\begin{align}
\begin{split}
b_1 &= \theta \\
b_n &= \left\lfloor b_{n-1} \right\rfloor \left(b_{n-1} - \left\lfloor b_{n-1} \right\rfloor + 1\right)~~~\forall ~ n \geq 2 \\
a_n &= \left\lfloor b_{n} \right\rfloor
\end{split}
\end{align}
$$
Where $\left\lfloor \cdot \right\rfloor$ is the floor function.

For example, $\theta=2.956938891377988...$ generates the Fibonacci sequence: $2, 3, 5, 8, 13, 21, 34, 55, 89, ...$

The *concatenation* of a sequence of positive integers $a_n$ is a real value denoted $\tau$ constructed by concatenating the elements of the sequence after the decimal point, starting at $a_1$: $a_1.a_2a_3a_4...$

For example, the Fibonacci sequence constructed from $\theta=2.956938891377988...$ yields the concatenation $\tau=2.3581321345589...$ Clearly, $\tau \neq \theta$ for this value of $\theta$.

Find the only value of $\theta$ for which the generated sequence starts at $a_1=2$ and the concatenation of the generated sequence equals the original value: $\tau = \theta$. Give your answer rounded to $24$ places after the decimal point.

### 751. 拼接相合

下述过程能使用任意正实数 $\theta$ 生成一个不减的整数序列 $\{a_n\}$：

$$
\begin{align}
\begin{split}
b_1 &= \theta \\
b_n &= \left\lfloor b_{n-1} \right\rfloor \left(b_{n-1} - \left\lfloor b_{n-1} \right\rfloor + 1\right)~~~\forall ~ n \geq 2 \\
a_n &= \left\lfloor b_{n} \right\rfloor
\end{split}
\end{align}
$$

其中 $\left\lfloor \cdot \right\rfloor$ 是取整函数。

例如，取 $\theta=2.956938891377988...$ 就能产生斐波那契数列 $2, 3, 5, 8, 13, 21, 34, 55, 89, ...$。

对任意正整数序列 $\{a_n\}$，定义其 *拼接数* 为：把 $a_1$ 作为整数部分，在小数点后顺次写下序列的其他元素所得到的实数 $\tau = a_1.a_2a_3a_4...$。

例如，由 $\theta=2.956938891377988...$ 生成的斐波那契数列的拼接数为 $\tau=2.3581321345589...$，显然对这个 $\theta$ 有 $\tau \neq \theta$。

求 $\theta$ 的唯一值，使其满足 $a_1 = 2$ 且 $\theta$ 生成的序列的拼接数 $\tau$ 等于 $\theta$。将答案四舍五入至小数点后第 $24$ 位。


---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
