### [840. Sum of Products](https://projecteuler.net/problem=840)

A **partition** of $n$ is a set of positive integers for which the sum equals $n$.  
The partitions of 5 are:
$\{5\},\{1,4\},\{2,3\},\{1,1,3\},\{1,2,2\},\{1,1,1,2\}$ and $\{1,1,1,1,1\}$.

Further we define the function $D(p)$ as:
$$
\begin{align}
\begin{split}
D(1) & = 1 \\
D(p) & = 1, \text{ for any prime } p \\
D(pq) & = D(p)q + pD(q), \text{ for any positive integers } p,q \gt 1.
\end{split}
\end{align}
$$

Now let $\{a_1, a_2,\ldots,a_k\}$ be a partition of $n$.  
We assign to this particular partition the value:
$$
P=\prod_{j=1}^{k}D(a_j). 
$$

$G(n)$ is the sum of $P$ for all partitions of $n$.   
We can verify that $G(10) = 164$.

We also define:

$$
S(N)=\sum_{n=1}^{N}G(n).
$$

You are given $S(10)=396$.  
Find $S(5\times 10^4) \mod 999676999$.

### 840. 乘积之和

我们定义 $n$ 的一个**拆分（partition）**为一个正整数集合，其所有元素之和为 $n$。例如：$5$ 的所有拆分为 $\{5\},\{1,4\},\{2,3\},\{1,1,3\},\{1,2,2\},\{1,1,1,2\},\{1,1,1,1,1\}$。

进一步定义函数 $D(p)$ 满足：
$$
\begin{align}
\begin{split}
D(1) & = 1 \\
D(p) & = 1, \text{ 对任意质数 } p \\
D(pq) & = D(p)q + pD(q), \text{ 对任意正整数 } p,q \gt 1.
\end{split}
\end{align}
$$

现在我们记 $n$ 的某一个拆分为 $\{a_1, a_2,\ldots,a_k\}$，并指定一个数 $P$ 表示这个拆分的“价值”，$P$ 的计算方法为：

$$
P=\prod_{j=1}^{k}D(a_j)
$$

再令 $G(n)$ 为 $n$ 所有拆分的 $P$ 之和。已知：$G(10) = 164$。

再进一步的，令

$$
S(N)=\sum_{n=1}^{N}G(n)
$$

已知：$S(10)=396$。

求 $S(5\times 10^4) \mod 999676999$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。