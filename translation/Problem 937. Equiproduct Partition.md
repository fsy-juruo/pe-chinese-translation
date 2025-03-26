### [937. Equiproduct Partition](https://projecteuler.net/problem=937)

Let $\theta=\sqrt{-2}$.

Define $T$ to be the set of numbers of the form $a+b\theta$, where $a$ and $b$ are integers and either $a\gt 0$, or $a=0$ and $b\gt 0$. For a set $S \subseteq T$ and element $z \in T$, define $p(S,z)$ to be the number of ways of choosing two distinct elements from $S$ with product either $z$ or $-z$.

For example if $S=\{1,2,4\}$ and $z=4$, there is only one valid pair of elements with product $\pm4$, namely $1$ and $4$. Thus, in this case $p(S,z)=1$.

For another example, if $S=\{1,\theta,1+\theta,2-\theta\}$ and $z=2-\theta$, we have $1\cdot(2-\theta)=z$ and $\theta\cdot(1+\theta)=-z$, giving $p(S,z)=2$.

Let $A$ and $B$ be two sets satisfying the following conditions:

- $1 \in A$
- $A \cap B = \emptyset$
- $A \cup B = T$
- $p(A,z) = p(B,z)$ for all $z\in T$

Remarkably, these four conditions uniquely determine the sets $A$ and $B$.

Let $F_n$ be the set of the first $n$ factorials: $F_n=\{1!,2!,\dots,n!\}$, and define $G(n)$ to be the sum of all elements of $F_n\cap A$.

You are given $G(4) = 25$, $G(7) = 745$, and $G(100) \equiv 709772949 \pmod{10^9+7}$.

Find $G(10^8)$ and give your answer modulo $10^9+7$.

### 937. 等乘积分拆

令 $\theta=\sqrt{-2}$，记 $T$ 为形如 $a + b \theta$ 的数的集合，其中整数 $a, b$ 需满足如下两个条件之一：

- $a > 0$。
- $a = 0$ 且 $b > 0$。

对诸 $S \subseteq T$、$z \in T$，令 $p(S,z)$ 为：从 $S$ 中任取两个不同的、乘积为 $z$ 或 $-z$ 的元素的方案数。举个例子：若取 $S=\{1,2,4\}$、$z=4$，惟一满足要求的取法是取出 $1$ 和 $4$。于是 $p(S,z)=1$。再比如，取 $S=\{1,\theta,1+\theta,2-\theta\}$、$z=2-\theta$，则有两种合法的取法：$1\cdot(2-\theta)=z$、$\theta\cdot(1+\theta)=-z$，于是 $p(S,z)=2$。

记 $A$、$B$ 为满足如下条件的两个集合。

- $1 \in A$。
- $A \cap B = \varnothing$。
- $A \cup B = T$。
- 对诸 $z\in T$，$p(A,z) = p(B,z)$。

值得一提的是，这四个条件能够唯一确定集合 $A$、$B$。

记 $F_n$ 是 $n$ 个阶乘数组成的集合，即 $F_n=\{1!,2!,\dots,n!\}$。再记 $G(n)$ 是 $F_n\cap A$ 中全体元素的和。已知：$G(4) = 25$、$G(7) = 745$、$G(100) \equiv 709772949 \pmod{10^9+7}$。

求 $G(10^8)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

