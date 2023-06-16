### [844. $k$-Markov Numbers](https://projecteuler.net/problem=844)

Consider positive integer solutions to
$$
a^2+b^2+c^2 = 3abc
$$

For example, $(1,5,13)$ is a solution. We define a 3-Markov number to be any part of a solution, so $1$, $5$ and $13$ are all 3-Markov numbers. Adding distinct 3-Markov numbers $\le 10^3$ would give $2797$.

Now we define a $k$-Markov number to be a positive integer that is part of a solution to:

$$
\displaystyle \sum_{i=1}^{k}x_i^2=k\prod_{i=1}^{k}x_i,\quad x_i\text{ are positive integers}
$$

Let $M_k(N)$ be the sum of $k$-Markov numbers $\le N$. Hence $M_3(10^{3})=2797$, also $M_8(10^8) = 131493335$.

Define $\displaystyle S(K,N)=\sum_{k=3}^{K}M_k(N)$. You are given $S(4, 10^2)=229$ and $S(10, 10^8)=2383369980$.

Find $S(10^{18}, 10^{18})$. Give your answer modulo $1\,405\,695\,061$.

### 844. $k$-马尔科夫数

考虑如下不定方程的正整数解：

$$
a^2+b^2+c^2 = 3abc
$$

如 $(1, 5, 13)$ 就是该方程的一组正整数解。我们定义：任意一组解中的任意一个数都是 3-马尔科夫数，如 $1$、$5$、$13$ 都是 3-马尔科夫数。对 $\leq 10^3$ 的 3-马尔科夫数求和，结果为 $2797$。
相似的，定义 $k$-马尔科夫数为以下方程的任意一组解中的任意一个正整数：

$$
\displaystyle \sum_{i=1}^{k}x_i^2=k\prod_{i=1}^{k}x_i,\quad x_i\text{ 均为正整数.}
$$

记 $M_k(N)$ 为 $\le N$ 的 $k$-马尔科夫数之和。已知：$M_3(10^{3})=2797$、$M_8(10^8) = 131493335$。

再记  $\displaystyle S(K,N)=\sum_{k=3}^{K}M_k(N)$。已知：$S(4, 10^2)=229$、$S(10, 10^8)=2383369980$。

求 $S(10^{18}, 10^{18})$ 模 $1\,405\,695\,061$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。