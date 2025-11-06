### [967. $B$-Trivisible Numbers](https://projecteuler.net/problem=967)

A positive integer $n$ is considered *$B$-trivisible* if the sum of all different prime factors of $n$ which are not larger than $B$ is divisible by $3$.

For example, $175 = 5^2 \cdot 7$ is $10$-trivisible because $5 + 7 = 12$ which is divisible by $3$. Similarly, $175$ is $4$-trivisible because all primes dividing $175$ are larger than $4$, and the empty summation $0$ is divisible by $3$.  
On the other hand, $175$ is not $6$-trivisible because the sum of relevant primes is $5$ which is not divisible by $3$.

Let $F(N, B)$ be the number of $B$-trivisible integers not larger than $N$.

For example, $F(10, 4) = 5$, the $4$-trivisible numbers being $1,3,5,7,9$.  
You are also given $F(10, 10) = 3$ and $F(100, 10) = 41$.

Find $F(10^{18}, 120)$.

### 967. $B$-可三分数 [^1]

对正整数 $n$，倘若其所有 $\leq B$ 的质因子之和能被 $3$ 整除，则称 $n$ 是 *$B$-可三分* 的。

例如，$175 = 5^2 \cdot 7$ 是 *$10$-可三分* 的，因为 $5 + 7 = 12$ 可以被 $3$ 整除。同样的，$175$ 也是 $4$-可三分的，因为 $175$ 的所有质因数都大于 $4$，对空集求和的结果 $0$ 确实能被 $3$ 整除。  
另一方面，$175$ 不是 $6$-可三分的，因为其只有 $5$ 这个质因数比 $6$ 小，而 $5$ 不能被 $3$ 整除。

记 $F(N, B)$ 为不大于 $N$ 的 $B$-可三分的整数的个数。

例如，$F(10, 4) = 5$，这 $5$ 个 $4$-可三分数分别是 $1, 3, 5, 7, 9$。  
你还知道 $F(10, 10) = 3$、$F(100, 10) = 41$。

求 $F(10^{18}, 120)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

[^1]: 我对这个译名并不完全满意，若您有更好的译名欢迎指出。
