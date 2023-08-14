### [772. Balanceable $k$-bounded Partitions](https://projecteuler.net/problem=772)

A $k$-bounded partition of a positive integer $N$ is a way of writing $N$ as a sum of positive integers not exceeding $k$.

A balanceable partition is a partition that can be further divided into two parts of equal sums.

For example, $3 + 2 + 2 + 2 + 2 + 1$ is a balanceable $3$-bounded partition of $12$ since $3 + 2 + 1 = 2 + 2 + 2$. Conversely, $3 + 3 + 3 + 1$ is a $3$-bounded partition of $10$ which is not balanceable.

Let $f(k)$ be the smallest positive integer $N$ all of whose $k$-bounded partitions are balanceable. For example, $f(3) = 12$ and $f(30) \equiv 179092994 \pmod {1\,000\,000\,007}$.

Find $f(10^8)$. Give your answer modulo $1\,000\,000\,007$.

### 772. 可平衡 $k$-有界分拆

将某正整数 $N$ 分拆为若干不大于 $k$ 的正整数的和的方式被称为 $N$ 的一种 $k$-有界分拆。若分拆出来的数可以被分为两组，且这两组内的数的和相等，则称该分拆方式为可平衡分拆。

如 $3 + 2 + 2 + 2 + 2 + 1$ 是 $12$ 的一种可平衡 $3$-有界分拆，因为 $3 + 2 + 1 = 2 + 2 + 2$。而 $3 + 3 + 3 + 1$ 就不是 $10$ 的一种可平衡 $3$-有界分拆。

记 $f(k)$ 为最小的满足下述条件的正整数 $N$：其 $k$-有界分拆都是可平衡分拆。已知 $f(3) = 12$、$f(30) \equiv 179092994 \pmod {1\,000\,000\,007}$。

求 $f(10^8)$ 模 $1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
