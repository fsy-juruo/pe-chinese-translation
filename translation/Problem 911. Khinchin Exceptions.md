### [911. Khinchin Exceptions](https://projecteuler.net/problem=911)

An irrational number $x$ can be uniquely expressed as a **continued fraction** $[a_0; a_1,a_2,a_3,\dots]$:
$$
x=a_{0}+\cfrac{1}{a_1+\cfrac{1}{a_2+\cfrac{1}{a_3+{_\ddots}}}}
$$
where $a_0$ is an integer and $a_1,a_2,a_3,\dots$ are positive integers.

Define $k_j(x)$ to be the **geometric mean** of $a_1,a_2,\dots,a_j$.  
That is, $k_j(x)=(a_1a_2 \cdots a_j)^{1/j}$.  
Also define $k_\infty(x)=\lim_{j\to \infty} k_j(x)$.

Khinchin proved that **almost all** irrational numbers $x$ have the same value of $k_\infty(x)\approx2.685452\dots$ known as **Khinchin's constant**. However, there are some exceptions to this rule.

For $n\geq 0$ define
$$
\rho_n = \sum_{i=0}^{\infty} \frac{2^n}{2^{2^i}}
$$

For example $\rho_2$, with continued fraction beginning $[3; 3, 1, 3, 4, 3, 1, 3,\dots]$, has $k_\infty(\rho_2)\approx2.059767$.

Find the geometric mean of $k_{\infty}(\rho_n)$ for $0\leq n\leq 50$, giving your answer rounded to six digits after the decimal point.

### 911. 辛钦例外

一个无理数恰有惟一的连分数表示 $[a_0; a_1,a_2,a_3,\dots]$，其中 $a_0$ 是整数、而 $a_1,a_2,a_3,\dots$ 均是正整数：

$$
x=a_{0}+\cfrac{1}{a_1+\cfrac{1}{a_2+\cfrac{1}{a_3+{_\ddots}}}}
$$

记 $k_j(x)$ 为  $a_1,a_2,\dots,a_j$ 的**几何平均数**。亦即，$k_j(x)=(a_1a_2 \cdots a_j)^{1/j}$。再记 $k_\infty(x)=\lim_{j\to \infty} k_j(x)$。

前苏联数学家辛钦证明了，对 **几乎所有** 无理数 $x$，$k_{\infty}(x)$ 均等于 **辛钦常数** $\approx2.685452\dots$。不过有一些数不符合这个规律。

对整数 $n\geq 0$ 定义：
$$
\rho_n = \sum_{i=0}^{\infty} \frac{2^n}{2^{2^i}}
$$

例如 $\rho_2$ 的连分数表示是 $[3; 3, 1, 3, 4, 3, 1, 3,\dots]$，对应的 $k_\infty(\rho_2)\approx2.059767$。

求 $0\leq n\leq 50$ 时，全体 $k_{\infty}(\rho_n)$ 的几何平均数。将你的答案四舍五入至小数点后第 $6$ 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。