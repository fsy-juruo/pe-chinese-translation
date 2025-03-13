### [903. Total Permutation Powers](https://projecteuler.net/problem=903)

A permutation $\pi$ of $\{1, \dots, n\}$ can be represented in **one-line notation** as $\pi(1),\ldots,\pi(n) $. If all $n!$ permutations are written in lexicographic order then $\textrm{rank}(\pi)$ is the position of $\pi$ in this 1-based list.

For example, $\text{rank}(2,1,3) = 3$ because the six permutations of $\{1, 2, 3\}$ in lexicographic order are:

$$
1, 2, 3\quad 1, 3, 2 \quad 2, 1, 3 \quad 2, 3, 1 \quad 3, 1, 2 \quad 3, 2, 1
$$

Let $Q(n)$ be the sum $\sum_{\pi}\sum_{i = 1}^{n!} \text{rank}(\pi^i)$, where $\pi$ ranges over all permutations of $\{1, \dots, n\}$, and $\pi^i$ is the permutation arising from applying $\pi$ $i$ times.

For example, $Q(2) = 5$, $Q(3) = 88$, $Q(6) = 133103808$ and $Q(10) \equiv 468421536 \pmod {10^9 + 7}$.

Find $Q(10^6)$. Give your answer modulo $(10^9 + 7)$.

### 903. 全部置换的幂

我们可以用 **一行表示法** $\pi(1), \cdots, \pi(n)$ 表示 $\{1, 2, \cdots, n\}$ 的一个排列 $\pi$。我们将 $\{1, 2, \cdots, n\}$ 的所有 $n!$ 个排列按字典序升序排序，放入下标从 $1$ 开始的列表内，记 $\textrm{rank}(\pi)$ 为 $\pi$ 在这个列表中的位置。

例如，$\text{rank}(2,1,3) = 3$。因为 $\{1, 2, 3\}$ 的所有 $6$ 个排列按字典序升序排序后的结果是：

$$
1, 2, 3\quad 1, 3, 2 \quad 2, 1, 3 \quad 2, 3, 1 \quad 3, 1, 2 \quad 3, 2, 1
$$

记 $Q(n)$ 为 $\sum_{\pi} \sum_{i = 1}^{n!} \text{rank}(\pi^i)$，其中 $\pi$ 取遍 $\{1, \dots, n\}$ 的所有排列，$\pi^i$ 表示将 $\pi$ 自身复合 $i$ 次得到的排列。

已知：$Q(2) = 5$、$Q(3) = 88$、$Q(6) = 133103808$、$Q(10) \equiv 468421536 \pmod {10^9 + 7}$。

求 $Q(10^6)$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

