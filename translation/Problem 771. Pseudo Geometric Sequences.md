### [771. Pseudo Geometric Sequence](https://projecteuler.net/problem=771)

We define a *pseudo-geometric sequence* to be a finite sequence $a_0, a_1, \dotsc, a_n$ of positive integers, satisfying the following conditions:

- $n \geq 4$, i.e. the sequence has at least $5$ terms.
- $0 \lt a_0 \lt a_1 \lt \cdots \lt a_n$, i.e. the sequence is strictly increasing.
- $| a_i^2 - a_{i - 1}a_{i + 1} | \le 2$ for $1 \le i \le n-1$.

Let $G(N)$ be the number of different pseudo-geometric sequences whose terms do not exceed $N$.
For example, $G(6) = 4$, as the following $4$ sequences give a complete list:
$$
1, 2, 3, 4, 5 \qquad 1, 2, 3, 4, 6 \qquad 2, 3, 4, 5, 6 \qquad 1, 2, 3, 4, 5, 6
$$

Also, $G(10) = 26$, $G(100) = 4710$ and $G(1000) = 496805$.

Find $G(10^{18})$. Give your answer modulo $1\,000\,000\,007$.

### 771. 伪等比数列

定义满足如下条件的有限正整数数列 $a_0, a_1, \dotsc, a_n$ 为 *伪等比数列*：

- $n \geq 4$，即该数列至少含有 $5$ 项。
- $0 \lt a_0 \lt a_1 \lt \cdots \lt a_n$，即该数列严格递增。
- 对于所有 $1 \le i \le n-1$ 有 $| a_i^2 - a_{i - 1}a_{i + 1} | \le 2$。

记 $G(N)$ 为每一项均不大于 $N$ 的伪等比数列的数量。已知 $G(6) = 4$，这 4 个伪等比数列是：
$$
1, 2, 3, 4, 5 \qquad 1, 2, 3, 4, 6 \qquad 2, 3, 4, 5, 6 \qquad 1, 2, 3, 4, 5, 6
$$

亦已知 $G(10) = 26$、$G(100) = 4710$ 且 $G(1000) = 496805$。

求 $G(10^{18})$ 模 $1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
