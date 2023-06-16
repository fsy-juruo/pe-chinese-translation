### [677. Coloured Graphs](https://projecteuler.net/problem=677)

Let $g(n)$ be the number of **undirected graphs** with $n$ nodes satisfying the following properties:

- The graph is connected and has no cycles or multiple edges.
- Each node is either red, blue, or yellow.
- A red node may have no more than 4 edges connected to it.
- A blue or yellow node may have no more than 3 edges connected to it.
- An edge may not directly connect a yellow node to a yellow node.

For example, $g(2)=5$, $g(3)=15$, and $g(4) = 57$.
You are also given that $g(10) = 710249$ and $g(100) \equiv 919747298 \pmod{1\,000\,000\,007}$.

Find $g(10\,000) \bmod 1\,000\,000\,007$.


### 677. 被染色的图

令 $g(n)$ 为有 $n$ 个节点，且满足以下性质的**无向图**的个数：

- 这个图是连通的，没有重边和环。
- 每个节点只可能被染成红、蓝、黄三色之一。
- 一个红色的节点最多有 4 条边与之相连。
- 一个蓝色或黄色的节点最多有 3 条边与之相连。
- 没有一条边直接连接两个黄色节点。

已知：$g(2)=5$、$g(3)=15$、$g(4) = 57$、$g(10) = 710249$ 且 $g(100) \equiv 919747298 \pmod{1\,000\,000\,007}$。

求 $g(10\,000) \bmod 1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。