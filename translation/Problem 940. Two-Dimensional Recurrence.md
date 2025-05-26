### [940. Two-Dimensional Recurrence](https://projecteuler.net/problem=940)

The **Fibonacci sequence** $(f_i)$ is the unique sequence such that

- $f_0=0$
- $f_1=1$
- $f_{i+1}=f_i+f_{i-1}$

Similarly, there is a unique function $A(m,n)$ such that

- $A(0,0)=0$
- $A(0,1)=1$
- $A(m+1,n)=A(m,n+1)+A(m,n)$
- $A(m+1,n+1)=2A(m+1,n)+A(m,n)$

Define $S(k)=\displaystyle\sum_{i=2}^k\sum_{j=2}^k A(f_i,f_j)$. For example

$$
\begin{align}
S(3)&=A(1,1)+A(1,2)+A(2,1)+A(2,2)\\
&=2+5+7+16\\
&=30
\end{align}
$$

You are also given $S(5)=10396$.

Find $S(50)$, giving your answer modulo $1123581313$.

### 940. 二维递推关系

**斐波那契数列** $(f_i)$ 指的是满足如下条件的惟一数列：

- $f_0=0$
- $f_1=1$
- $f_{i+1}=f_i+f_{i-1}$

类似的，记 $A(m, n)$ 为惟一一个满足如下条件的函数：

- $A(0,0)=0$
- $A(0,1)=1$
- $A(m+1,n)=A(m,n+1)+A(m,n)$
- $A(m+1,n+1)=2A(m+1,n)+A(m,n)$

记 $S(k)=\displaystyle\sum_{i=2}^k\sum_{j=2}^k A(f_i,f_j)$，例如：

$$
\begin{align}
S(3)&=A(1,1)+A(1,2)+A(2,1)+A(2,2)\\
&=2+5+7+16\\
&=30
\end{align}
$$

你还知道 $S(5)=10396$。

求 $S(50)$ 模 $1123581313$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

