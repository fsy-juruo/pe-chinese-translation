### [822. Square the Smallest](https://pe.xiaoyaowudi.com/problem=822)

A list initially contains the numbers $2, 3, \dots, n$.
At each round, the smallest number in the list is replaced by its square. If there is more than one such number, then only one of them is replaced.

For example, below are the first three rounds for $n = 5$:
$$
[2, 3, 4, 5] \xrightarrow{(1)} [4, 3, 4, 5] \xrightarrow{(2)} [4, 9, 4, 5] \xrightarrow{(3)} [16, 9, 4, 5].
$$

Let $S(n, m)$ be the sum of all numbers in the list after $m$ rounds.

For example, $S(5, 3) = 16 + 9 + 4 + 5 = 34$. Also $S(10, 100) \equiv 845339386 \pmod{1234567891}$.

Find $S(10^4, 10^{16})$. Give your answer modulo $1234567891$.

### 822. 把最小数平方

某列表最初含有 $2, 3, \dots, n$ 这些数。

每一轮中，列表中最小的一个数会被平方。如果有多个最小数，我们只平方其中一个。

举个例子，这是 $n = 5$ 时的前三轮操作：
$$
[2, 3, 4, 5] \xrightarrow{(1)} [4, 3, 4, 5] \xrightarrow{(2)} [4, 9, 4, 5] \xrightarrow{(3)} [16, 9, 4, 5].
$$

记 $S(n, m)$ 为 $m$ 轮后列表中所有数字之和。例如，$S(5, 3) = 16 + 9 + 4 + 5 = 34$。同样可得 $S(10, 100) \equiv 845339386 \pmod{1234567891}$。

求 $S(10^4, 10^{16})$ 模 $1234567891$。