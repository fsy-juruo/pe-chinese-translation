### [763. Amoebas in a 3D Grid](https://projecteuler.net/problem=763)

Consider a three dimensional grid of cubes. An amoeba in cube $(x, y, z)$ can divide itself into three amoebas to occupy the cubes $(x + 1, y, z)$, $(x, y + 1, z)$ and $(x, y, z + 1)$, provided these cubes are empty.

Originally there is only one amoeba in the cube $(0, 0, 0)$. After $N$ divisions there will be $2N+1$ amoebas arranged in the grid. An arrangement may be reached in several different ways but it is only counted once. Let $D(N)$ be the number of different possible arrangements after $N$ divisions.

For example, $D(2) = 3$, $D(10) = 44499$, $D(20)=9204559704$ and the last nine digits of $D(100)$ are $780166455$.

Find $D(10\,000)$, enter the last nine digits as your answer.

### 763. 三维网格上的变形虫

考虑一个三维网格，如果 $(x + 1, y, z)$、$(x, y + 1, z)$、$(x, y, z + 1)$ 这三个格子上都没有变形虫，那么位于 $(x, y, z)$ 一格上的变形虫可以将自身分裂为三只变形虫，并分别占据这三格。

初始时，仅有 $(0, 0, 0)$ 一格上有一只变形虫。在 $N$ 次分裂之后，网格上会有 $2N + 1$ 只变形虫。当然，可能会有多种安排变形虫分裂的方式，它们最终得到的变形虫的排布完全相同，但此处，相同的排布方式我们只计一次。记 $D(N)$ 为：在 $N$ 次分裂之后，不同的变形虫排布方案数。

例如，$D(2) = 3$、$D(10) = 44499$、$D(20)=9204559704$ 且 $D(100)$ 的末九位是 $780166455$。

求 $D(10\,000)$ 并将其末九位作为你的答案。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
