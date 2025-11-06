### [857. Beautiful Graphs](https://projecteuler.net/problem=857)

A graph is made up of vertices and coloured edges. 
Between every two distinct vertices there must be exactly one of the following:

- A red directed edge one way, and a blue directed edge the other way
- A green undirected edge
- A brown undirected edge

Such a graph is called *beautiful* if 

- A cycle of edges contains a red edge **if and only if** it also contains a blue edge
- No triangle of edges is made up of entirely green or entirely brown edges


Below are four distinct examples of beautiful graphs on three vertices:

![](images/0857_GoodGraphs.jpg)

Below are four examples of graphs that are not beautiful:

![](images/0857_BadGraphs.jpg)

Let $G(n)$ be the number of beautiful graphs on the labelled vertices: $1,2,\ldots,n$.
You are given $G(3)=24$, $G(4)=186$ and $G(15)=12472315010483328$.

Find $G(10^7)$. Give your answer modulo $10^9+7$.


### 857. 漂亮的图

现有一张由若干结点、若干有色边组成的图，对该图中的任意两个不同的结点，它们之间须恰由如下三者之一相连：

- 两条方向相反的有向边，其中恰有一条红色边、一条蓝色边。
- 一条绿色无向边。
- 一条棕色无向边。

满足上述条件的图若还满足如下条件，则称该图是 *漂亮的*：

- 对该图中的任意一个环，当且仅当其中有蓝色边时，该圈中有红色边。
- 没有一个仅由绿色边（或棕色边）组成的三元环。

如下是四个不同的，含三个结点的漂亮的图：

![](images/0857_GoodGraphs.jpg)

如下是四个不漂亮的图：

![](images/0857_BadGraphs.jpg)

记 $G(n)$ 为含 $n$ 个结点的带标号漂亮图的数量。已知：$G(3)=24$、$G(4)=186$、$G(15)=12472315010483328$。

求 $G(10^7)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。