### [821. 123-Separable](https://projecteuler.net/problem=821)

A set, $S$, of integers is called *123-separable* if $S$, $2S$ and $3S$ are disjoint. Here $2S$ and $3S$ are obtained by multiplying all the elements in $S$ by $2$ and $3$ respectively.

Define $F(n)$ to be the maximum number of elements of
$$
(S\cup 2S \cup 3S)\cap \{1,2,3,\ldots,n\}
$$
where $S$ ranges over all 123-separable sets.

For example, $F(6) = 5$ can be achieved with either $S = \{1,4,5\}$ or $S = \{1,5,6\}$.
You are also given $F(20) = 19$.

Find $F(10^{16})$.

### 821. 可 123 分离的

如果某整数集 $S$ 满足：$S$、$2S$、$3S$ 两两交集为空集，则称集合 $S$ 为 *可 123 分离的*。其中，$2S$、$3S$ 分别是通过把 $S$ 中元素分别乘以 $2$、$3$ 得到的新集合。

记 $F(n)$ 为对于所有可 123 分离的整数集 $S$，$(S\cup 2S \cup 3S)\cap \{1,2,3,\ldots,n\}$ 中元素个数的最大值。例如，$F(6) = 5$。这可以在 $S = \{1,4,5\}$ 或 $S = \{1,5,6\}$ 时取到。同理 $F(20) = 19$。

求 $F(10^{16})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。