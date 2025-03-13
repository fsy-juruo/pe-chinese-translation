### [916. Restricted Permutations](https://projecteuler.net/problem=916)

Let $P(n)$ be the number of permutations of $\{1,2,3,\ldots,2n\}$ such that:

1. There is no ascending subsequence with more than $n+1$ elements, and
2. There is no descending subsequence with more than two elements.

Note that subsequences need not be contiguous. For example, the permutation $(4,1,3,2)$ is not counted because it has a descending subsequence of three elements: $(4,3,2)$. You are given $P(2)=13$ and $P(10) \equiv 45265702 \pmod{10^9 + 7}$.

Find $P(10^8)$ and give your answer modulo $10^9 + 7$.

### 916. 满足限制的排列计数

记 $P(n)$ 为满足如下条件的 $\{1,2,3,\ldots,2n\}$ 的排列数：

1. 没有由 $> n + 1$ 个元素组成的上升子序列。
2. 没有由 $> 2$ 个元素组成的下降子序列。

注意，子序列不必由相邻的元素组成。例如，排列 $(4,1,3,2)$ 不满足上述条件，因为它有由 $3$ 个元素组成的下降子序列 $(4,3,2)$。已知：$P(2)=13$、$P(10) \equiv 45265702 \pmod{10^9 + 7}$。

求 $P(10^8)$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。