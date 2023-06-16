### [823. Factor Shuffle](https://projecteuler.net/problem=823)

A list initially contains the numbers $2, 3, \dots, n$.
At each round, every number in the list is divided by its smallest prime factor. Then the product of these smallest prime factors is added to the list as a new number. Finally, all numbers that become $1$ are removed from the list.

For example, below are the first three rounds for $n = 5$:

$$
[2, 3, 4, 5] \xrightarrow{(1)} [2, 60] \xrightarrow{(2)} [30, 4] \xrightarrow{(3)} [15, 2, 4].
$$
Let $S(n, m)$ be the sum of all numbers in the list after $m$ rounds.

For example, $S(5, 3) = 15 + 2 + 4 = 21$. Also $S(10, 100) = 257$.

Find $S(10^4, 10^{16})$. Give your answer modulo $1234567891$.

### 823. 因子重排

某列表最初含有 $2, 3, \dots, n$ 这些数。

每一轮中，所有在列表中的数都会被除以其最小的质因数，然后这些最小质因数之积会被加入这个列表，最后所有 $1$ 都会被从这个列表中移出。例如，下面是 $n = 5$ 时的前三轮操作：

$$
[2, 3, 4, 5] \xrightarrow{(1)} [2, 60] \xrightarrow{(2)} [30, 4] \xrightarrow{(3)} [15, 2, 4].
$$

记 $S(n, m)$ 为 $m$ 轮后列表中所有数字之和。例如，$S(5, 3) = 15 + 2 + 4 = 21$。同样可得 $S(10, 100) = 257$。

求 $S(10^4, 10^{16})$ 模 $1234567891$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。