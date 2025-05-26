### [921. Golden Recurrence](https://projecteuler.net/problem=921)

Consider the following recurrence relation:

$$
\begin{align}
a_0 &= \frac{\sqrt 5 + 1}2\\
a_{n+1} &= \dfrac{a_n(a_n^4 + 10a_n^2 + 5)}{5a_n^4 + 10a_n^2 + 1}
\end{align}
$$

Note that $a_0$ is the **golden ratio**.

$a_n$ can always be written in the form $\dfrac{p_n\sqrt{5}+1}{q_n}$, where $p_n$ and $q_n$ are positive integers.

Let $s(n)=p_n^5+q_n^5$. So, $s(0)=1^5+2^5=33$.

The **Fibonacci sequence** is defined as: $F_1=1$, $F_2=1$, $F_n=F_{n-1}+F_{n-2}$ for $n > 2$.

Define $\displaystyle S(m)=\sum_{i=2}^{m}s(F_i)$.

Find $S(1618034)$. Submit your answer modulo $398874989$.

### 921. 黄金分割递推

考虑如下递推：

$$
\begin{align}
a_0 &= \frac{\sqrt 5 + 1}2\\
a_{n+1} &= \dfrac{a_n(a_n^4 + 10a_n^2 + 5)}{5a_n^4 + 10a_n^2 + 1}
\end{align}
$$

可以注意到 $a_0$ 就是著名的 **黄金分割比**。

可以发现，$a_n$ 总是可以写成 $\dfrac{p_n\sqrt{5}+1}{q_n}$ 的形式，其中 $p_n$、$q_n$ 都是正整数。我们记 $s(n) = p_n^5 + q_n^5$，于是可得 $s(0)=1^5+2^5=33$。

本题中定义 **斐波那契数列** 满足如下条件：$F_1=1$、$F_2=1$，且对诸 $n > 2$ 都有 $F_n=F_{n-1}+F_{n-2}$。

再记 $\displaystyle S(m)=\sum_{i=2}^{m}s(F_i)$。

求 $S(1618034)$ 模 $398874989$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

