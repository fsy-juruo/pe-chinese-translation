### [874. Maximal Prime Score](https://projecteuler.net/problem=874)

Let $p(t)$ denote the $(t+1)$th prime number. So that $p(0) = 2$, $p(1) = 3$, etc.  
We define the *prime score* of a list of nonnegative integers $[a_1, \dots, a_n]$ as the sum $\sum_{i = 1}^n p(a_i)$.  
Let $M(k, n)$ be the maximal prime score among all lists $[a_1, \dots, a_n]$ such that:

- $0 \leq a_i < k$ for each $i$;
- the sum $\sum_{i = 1}^n a_i$ is a multiple of $k$.

For example, $M(2, 5) = 14$ as $[0, 1, 1, 1, 1]$ attains a maximal prime score of $14$.

Find $M(7000, p(7000))$.

### 874. 最大质数得分

记 $p(t)$ 为第 $(t+1)$ 个质数，所以 $p(0) = 2$、$p(1) = 3$，以此类推。  
对一列非负整数 $[a_1, \dots, a_n]$，我们定义其 *质数得分* 为 $\sum_{i = 1}^n p(a_i)$。  
记 $M(k, n)$ 为满足如下条件的数列中，质数得分的最大值：

- 对诸 $1 \leq i \leq n$，有 $0 \leq a_i < k$。
- $\sum_{i = 1}^n a_i$ 是 $k$ 的倍数。

例如，$M(2, 5) = 14$，因为序列 $[0, 1, 1, 1, 1]$ 的质数得分是 $14$。

求 $M(7000, p(7000))$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

