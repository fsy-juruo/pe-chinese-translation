### [908. Clock Sequence II](https://projecteuler.net/problem=908)

A *clock sequence* is a periodic sequence of positive integers that can be broken into contiguous segments such that the sum of the $n$-th segment is equal to $n$.

For example, the sequence 

$$
1\ 2\ 3\ 4\ 3\ 2\ 1\ 2\ 3\ 4\ 3\ 2\ 1\ 2\ 3\ 4\ 3\ 2\ 1\ \cdots
$$

is a clock sequence with period $6$, as it can be broken into 

$$
1\Big |2\Big |3\Big |4\Big |3\ 2\Big |1\ 2\ 3\Big |4\ 3\Big |2\ 1\ 2\ 3\Big |4\ 3\ 2\Big |1\ 2\ 3\ 4\Big |3\ 2\ 1\ 2\ 3\Big |\cdots
$$

Let $C(N)$ be the number of different clock sequences with period at most $N$.
For example, $C(3) = 3$, $C(4) = 7$ and $C(10) = 561$.

Find $C(10^4) \bmod 1111211113$.

### 908. 钟表序列 2

若一个由正整数组成的周期序列能够被划分为若干连续段，其中第 $n$ 个连续段的所有元素之和恰为 $n$，则称这个序列是一个 *钟表序列*。

例如，如下序列就是一个周期是 $6$ 的钟表序列：

$$
1\ 2\ 3\ 4\ 3\ 2\ 1\ 2\ 3\ 4\ 3\ 2\ 1\ 2\ 3\ 4\ 3\ 2\ 1\ \cdots
$$

因为它可以被划分为如下连续段： 

$$
1\Big |2\Big |3\Big |4\Big |3\ 2\Big |1\ 2\ 3\Big |4\ 3\Big |2\ 1\ 2\ 3\Big |4\ 3\ 2\Big |1\ 2\ 3\ 4\Big |3\ 2\ 1\ 2\ 3\Big |\cdots
$$

记 $C(N)$ 为所有周期 $\leq N$ 的不同钟表序列的总数。已知：$C(3) = 3$、$C(4) = 7$、$C(10) = 561$。

求 $C(10^4) \bmod 1111211113$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

