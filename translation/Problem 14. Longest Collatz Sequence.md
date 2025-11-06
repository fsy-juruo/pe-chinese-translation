### [14. Longest Collatz Sequence](https://projecteuler.net/problem=14)

The following iterative sequence is defined for the set of positive integers:

- $n \to n/2$ ($n$ is even)
- $n \to 3n + 1$ ($n$ is odd)

Using the rule above and starting with $13$, we generate the following sequence:
$$
13 \to 40 \to 20 \to 10 \to 5 \to 16 \to 8 \to 4 \to 2 \to 1.
$$

It can be seen that this sequence (starting at $13$ and finishing at $1$) contains $10$ terms. Although it has not been proved yet (Collatz Problem), it is thought that all starting numbers finish at $1$.
Which starting number, under one million, produces the longest chain?

**NOTE:** Once the chain starts the terms are allowed to go above one million.

### 14. 最长的考拉兹序列

我们在正整数集上，按如下迭代规则生成序列：

- 若 $n$ 是偶数，则令 $n \to n/2$。
- 若 $n$ 是奇数，则令 $n \to 3n + 1$。

从 $13$ 开始，按如上迭代规则生成出的序列形如：

$$
13 \to 40 \to 20 \to 10 \to 5 \to 16 \to 8 \to 4 \to 2 \to 1.
$$

可以发现，这个序列（从 $13$ 开始、以 $1$ 结束）共包含 $10$ 项。考拉兹猜想指出，不管从哪个数字开始，生成出的序列均将终止于 $1$，当然，这个猜想还没有被证明。

小于一百万的所有数中，从哪个数开始，生成出的序列的项数最大？

**注：** 迭代开始后，允许这个序列中的项达到一百万。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
