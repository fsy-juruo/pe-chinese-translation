### [902. Permutation Powers](https://projecteuler.net/problem=902)

A permutation $\pi$ of $\{1, \dots, n\}$ can be represented in **one-line notation** as $\pi(1),\ldots,\pi(n) $. If all $n!$ permutations are written in lexicographic order then $\textrm{rank}(\pi)$ is the position of $\pi$ in this 1-based list.

For example, $\text{rank}(2,1,3) = 3$ because the six permutations of $\{1, 2, 3\}$ in lexicographic order are:
$$
1, 2, 3\quad 1, 3, 2 \quad 2, 1, 3 \quad 2, 3, 1 \quad 3, 1, 2 \quad 3, 2, 1
$$

For a positive integer $m$, we define the following permutation of $\{1, \dots, n\}$ with $n = \frac{m(m+1)}2$:
$$
\begin{align}
\sigma(i) & = \begin{cases} \frac{k(k-1)}2 + 1 &  \textrm{if } i = \frac{k(k + 1)}2\textrm{ for }k\in\{1, \dots, m\};\\i + 1 &  \textrm{otherwise};\end{cases}\\
\tau(i) & = ((10^9 + 7)i \bmod n) + 1\\
\pi(i) & = \tau^{-1}(\sigma(\tau(i)))
\end{align}
$$
where $\tau^{-1}$ is the inverse permutation of $\tau$.

Define $\displaystyle P(m) = \sum_{k=1}^{m!} \text{rank}(\pi^k)$, where $\pi^k$ is the permutation arising from applying $\pi$ $k$ times.  
For example, $P(2) = 4$, $P(3) = 780$ and $P(4) = 38810300$.

Find $P(100)$. Give your answer modulo $(10^9 + 7)$.

### 902. 置换的幂

我们可以用 **一行表示法** $\pi(1), \cdots, \pi(n)$ 表示 $\{1, 2, \cdots, n\}$ 的一个排列 $\pi$。我们将 $\{1, 2, \cdots, n\}$ 的所有 $n!$ 个排列按字典序升序排序，放入下标从 $1$ 开始的列表内，记 $\textrm{rank}(\pi)$ 为 $\pi$ 在这个列表中的位置。

例如，$\text{rank}(2,1,3) = 3$。因为 $\{1, 2, 3\}$ 的所有 $6$ 个排列按字典序升序排序后的结果是：

$$
1, 2, 3\quad 1, 3, 2 \quad 2, 1, 3 \quad 2, 3, 1 \quad 3, 1, 2 \quad 3, 2, 1
$$

对正整数 $m$，令 $n = \frac{m(m + 1)}{2}$，我们定义如下 $\{1, \dots, n\}$ 的排列：

$$
\begin{align}
\sigma(i) & = \begin{cases} \frac{k(k-1)}2 + 1 &  \textrm{若对某 } k\in\{1, \dots, m\} \textrm{ 有 } i = \frac{k(k + 1)}2\\i + 1 &  \textrm{其他情况};\end{cases}\\
\tau(i) & = ((10^9 + 7)i \bmod n) + 1\\
\pi(i) & = \tau^{-1}(\sigma(\tau(i)))
\end{align}
$$

其中，$\tau^{-1}$ 是 $\tau$ 的逆置换。

记 $\displaystyle P(m) = \sum_{k=1}^{m!} \text{rank}(\pi^k)$，其中 $\pi^k$ 是 $\pi$ 自身复合 $k$ 次得到的排列。已知：$P(2) = 4$、$P(3) = 780$、$P(4) = 38810300$。

求 $P(100)$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

