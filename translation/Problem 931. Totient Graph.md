### [931. Totient Graph](https://projecteuler.net/problem=931)

For a positive integer $n$ construct a graph using all the divisors of $n$ as the vertices. An edge is drawn between $a$ and $b$ if $a$ is divisible by $b$ and $a/b$ is prime, and is given weight $\phi(a)-\phi(b)$, where $\phi$ is the Euler totient function.   
Define $t(n)$ to be the total weight of this graph.  
The example below shows that $t(45) = 52$

![](images/0931_totientgraph.png)

Let $T(N)=\displaystyle\sum_{n=1}^{N} t(n)$. You are given $T(10)=26$ and $T(10^2)=5282$.

Find $T(10^{12})$. Give your answer modulo $715827883$.

### 931. 欧拉总计函数图

对一个正整数 $n$，我们按如下规则建一张带权图：将 $n$ 的所有约数作为结点；对于 $n$ 的约数 $a$、$b$，若 $b$ 整除 $a$ 且 $a/b$ 是质数，则在 $a$、$b$ 之间连一条权为 $\varphi(a) - \varphi(b)$ 的边，其中 $\varphi$ 代指欧拉总计函数 (Euler totient function)。我们记 $t(n)$ 为该图的边权和。例如，下图说明了 $t(45) = 52$。

![](images/0931_totientgraph.png)

令 $T(N)=\displaystyle \sum_{n=1}^{N} t(n)$，已知 $T(10)=26$、$T(10^2)=5282$。

求 $T(10^{12})$ 模 $715827883$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。