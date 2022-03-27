### [691. Long substring with many repetitions](https://projecteuler.net/problem=691)

Given a character string $s$, we define $L(k,s)$ to be the length of the longest substring of $s$ which appears at least $k$ times in $s$, or $0$ if such a substring does not exist. For example, $L(3,\text{“bbabcabcabcacba”})=4$ because of the three occurrences of the substring $\text{“abca”}$, and $L(2,\text{“bbabcabcabcacba”})=7$ because of the repeated substring $\text{“abcabca”}$. Note that the occurrences can overlap.

Let $a_n$, $b_n$ and $c_n$ be the $0/1$ sequences defined by:

- $a_0 = 0$
- $a_{2n} = a_{n}$
- $a_{2n+1} = 1-a_{n}$
- $b_n = \lfloor\frac{n+1}{\varphi}\rfloor - \lfloor\frac{n}{\varphi}\rfloor$ (where $\varphi$ is the golden ratio)
- $c_n = a_n + b_n - 2a_nb_n$

and $S_n$ the character string $c_0\ldots c_{n-1}$. You are given that $L(2,S_{10})=5$, $L(3,S_{10})=2$, $L(2,S_{100})=14$, $L(4,S_{100})=6$, $L(2,S_{1000})=86$, $L(3,S_{1000}) = 45$, $L(5,S_{1000}) = 31$, and that the sum of non-zero $L(k,S_{1000})$ for $k\ge 1$ is $2460$.

Find the sum of non-zero $L(k,S_{5000000})$ for $k\ge 1$.

### 691. 重复多次的长子串

给定一个字符串 $s$，定义 $L(k,s)$ 为至少在 $s$ 中重复出现 $k$ 次的子串中，长度的最大值。若不存在符合要求的子串，函数值即为 $0$。比如说，$L(3,\text{“bbabcabcabcacba”})=4$ 因为子串 $\text{“abca”}$ 出现了三次；$L(2,\text{“bbabcabcabcacba”})=7$ 因为 $\text{“abcabca”}$ 出现了 7 次。请注意，出现的子串之间可能重叠。

令 $a_n$，$b_n$ 和 $c_n$ 为三个 $0/1$ 序列，定义如下： 

- $a_0 = 0$
- $a_{2n} = a_{n}$
- $a_{2n+1} = 1-a_{n}$
- $b_n = \lfloor\frac{n+1}{\varphi}\rfloor - \lfloor\frac{n}{\varphi}\rfloor$（$\varphi$ 是黄金分割比）
- $c_n = a_n + b_n - 2a_nb_n$

$S_n$ 是由 $c_0\ldots c_{n-1}$ 顺序组成的字符串。你已知 $L(2,S_{10})=5$，$L(3,S_{10})=2$，$L(2,S_{100})=14$，$L(4,S_{100})=6$，$L(2,S_{1000})=86$，$L(3,S_{1000}) = 45$，$L(5,S_{1000}) = 31$，并且对于所有 $k\ge 1$，其中非零的 $L(k,S_{1000})$ 之和为 $2460$。

求对于所有 $k\ge 1$，其中非零的 $L(k,S_{5000000})$ 之和。
