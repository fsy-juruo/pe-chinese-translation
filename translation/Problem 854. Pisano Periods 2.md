### [854. Pisano Periods 2](https://projecteuler.net/problem=854)

For every positive integer $n$ the Fibonacci sequence modulo $n$ is periodic. The period depends on the value of $n$.
This period is called the **Pisano period** for $n$, often shortened to $\pi(n)$.

Define $M(p)$ as the largest integer $n$ such that $\pi(n) = p$, and define $M(p) = 1$ if there is no such $n$.  
For example, there are three values of $n$ for which $\pi(n)$ equals $18$: $19, 38, 76$. Therefore $M(18) = 76$.

Let the product function $P(n)$ be: 
$$
P(n)=\prod_{p = 1}^{n}M(p).
$$
You are given: $P(10)=264$.

Find $P(1\,000\,000)\bmod 1\,234\,567\,891$.

### 854. 皮萨诺周期 2

对诸正整数 $n$，斐波那契数列每项模 $n$ 产生的新数列必是周期数列。这个周期与 $n$ 有关，我们称其为 $n$ 的 **皮萨诺周期**，常简记为 $\pi(n)$。

记 $M(p)$ 为满足 $\pi(n) = p$ 的最大的整数 $n$，若不存在满足条件的正整数，则令 $M(p) = 1$。  
例如，共有 $3$ 个满足 $\pi(n) = 18$ 的正整数，分别是 $19, 38, 76$。故 $M(18) = 76$。


记 $M(p)$ 的前缀积是 $P(n)$：
$$
P(n)=\prod_{p = 1}^{n}M(p).
$$
已知 $P(10)=264$。

求 $P(1\,000\,000)\bmod 1\,234\,567\,891$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。