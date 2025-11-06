
### [762. Amoebas in a 2D Grid](https://projecteuler.net/problem=762)

Consider a two dimensional grid of squares. The grid has 4 rows but infinitely many columns.
An amoeba in square $(x, y)$ can divide itself into two amoebas to occupy the squares $(x+1,y)$ and $(x+1,(y+1) \bmod 4)$, provided these squares are empty.

The following diagrams show two cases of an amoeba placed in square **A** of each grid. When it divides, it is replaced with two amoebas, one at each of the squares marked with **B**:

![](images/0762_table_a.png)
![](images/0762_table_b.png)

Originally there is only one amoeba in the square $(0, 0)$. After $N$ divisions there will be $N+1$ amoebas arranged in the grid. An arrangement may be reached in several different ways but it is only counted once. Let $C(N)$ be the number of different possible arrangements after $N$ divisions.

For example, $C(2) = 2$, $C(10) = 1301$, $C(20)=5895236$ and the last nine digits of $C(100)$ are $125923036$.

Find $C(100\,000)$, enter the last nine digits as your answer.

### 762. 二维网格上的变形虫

考虑一个二维的，由四行、无数列方格排成的网格。如果 $(x + 1, y)$、$(x + 1,(y + 1) \bmod 4)$ 这两个位置上都没有变形虫，那么位于 $(x, y)$ 的变形虫可以将自身分裂为两只变形虫，分别占据这两个格子。

如下两张图展示了变形虫分裂的过程：初始时，**A** 方格上有一只变形虫，其分裂后产生的两只新变形虫位于标有 **B** 的两个方格上。

![](images/0762_table_a.png)
![](images/0762_table_b.png)

初始时，仅有 $(0, 0)$ 一格上有一只变形虫。在 $N$ 次分裂之后，网格上会有 $N + 1$ 只变形虫。当然，可能会有多种安排变形虫分裂的方式，它们最终得到的变形虫的排布完全相同，但此处，相同的排布方式我们只计一次。记 $C(N)$ 为：在 $N$ 次分裂之后，不同的变形虫排布方案数。

已知  $C(2) = 2$、$C(10) = 1301$、$C(20)=5895236$ 且 $C(100)$ 的末九位数是 $125923036$。

求 $C(100\,000)$，将其末九位数作为你的答案。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
