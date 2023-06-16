### [832. Mex Sequence](https://projecteuler.net/problem=832)

In this problem $\oplus$ is used to represent the bitwise **exclusive or** of two numbers.
Starting with blank paper repeatedly do the following:

1. Write down the smallest positive integer $a$ which is currently not on the paper;

2. Find the smallest positive integer $b$ such that neither $b$ nor $(a \oplus b)$ is currently on the paper. Then write down both $b$ and $(a \oplus b)$.

After the first round $\{1,2,3\}$ will be written on the paper. In the second round $a=4$ and because $(4 \oplus 5)$, $(4 \oplus 6)$ and $(4 \oplus 7)$ are all already written $b$ must be $8$.

After $n$ rounds there will be $3n$ numbers on the paper. Their sum is denoted by $M(n)$.  
For example, $M(10) = 642$ and $M(1000) = 5432148$.

Find $M(10^{18})$. Give your answer modulo $1\,000\,000\,007$.

### 832. mex[^1] 序列

本题用 $\oplus$ 表示两个数的按位异或运算。

我们在一张白纸上，进行如下操作：

1. 写下目前不在纸上的最小正整数。

2. 找到最小的正整数 $b$，使其满足 $b$ 和 $(a \oplus b)$ 都不在纸上，随后写下 $b$ 和 $(a \oplus b)$。

第一轮后纸上有 $1,2,3$ 三个数。第二轮中 $a = 4$，而且因为 $(4 \oplus 5), (4 \oplus 6), (4 \oplus 7)$ 都在纸上，所以 $b = 8$。

$n$ 轮后，纸上会有 $3n$ 个数，记它们的和为 $M(n)$。已知：$M(10) = 642$ 且 $M(1000) = 5432148$。

求 $M(10^{18})$ 模 $1\,000\,000\,007$ 之值。

[^1]: mex 为 minimal excluded 的缩写，在此过程中的第二步被体现。信息学竞赛中一般不翻译 mex，这里也不翻译。另外，一般的 mex 运算一般是不在某个数集中最小的自然数，而非正整数。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。