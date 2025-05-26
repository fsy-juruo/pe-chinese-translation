### [929. Odd-Run Compositions](https://projecteuler.net/problem=929)

A **composition** of $n$ is a sequence of positive integers which sum to $n$. Such a sequence can be split into *runs*, where a run is a maximal contiguous subsequence of equal terms.

For example, $2,2,1,1,1,3,2,2$ is a composition of $14$ consisting of four runs:

$$
2, 2\quad 1, 1, 1\quad 3 \quad 2, 2
$$

Let $F(n)$ be the number of compositions of $n$ where every run has odd length.

For example, $F(5)=10$:

$$
\begin{align*}
 5 && 4,1  && 3,2 && 2,3 && 2,1,2 \\
 2,1,1,1 && 1,4 && 1,3,1 && 1,1,1,2 && 1,1,1,1,1
\end{align*}
$$

Find $F(10^5)$. Give your answer modulo $1111124111$.


### 929. 奇长度相同段组成

若某正整数序列的所有元素之和是 $n$，则称这是 $n$ 的一个 **组成**。这个序列可以被拆分成若干含相同元素的极大连续段。

例如，$[2,2,1,1,1,3,2,2]$ 是 $14$ 的一个组成，它包含 $4$ 个含相同元素的极大连续段。

$$
2, 2\quad 1, 1, 1\quad 3 \quad 2, 2
$$

记 $F(n)$ 为满足如下条件的序列数量：其是 $n$ 的一个组成，且这个序列中，所有含相同元素的极大连续段的长度都是奇数。

例如，$F(5)=10$，这 $10$ 个满足条件的序列如下：

$$
\begin{align*}
 5 && 4,1  && 3,2 && 2,3 && 2,1,2 \\
 2,1,1,1 && 1,4 && 1,3,1 && 1,1,1,2 && 1,1,1,1,1
\end{align*}
$$

求 $F(10^5)$ 模 $1111124111$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

