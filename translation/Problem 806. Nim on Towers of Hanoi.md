### [806. Nim on Towers of Hanoi](https://projecteuler.net/problem=806)

This problem combines the game of Nim with the Towers of Hanoi. For a brief introduction to the rules of these games, please refer to [Problem 301](https://pe.xiaoyaowudi.com/problem=301) and [Problem 497](https://pe.xiaoyaowudi.com/problem=497), respectively.

The unique shortest solution to the Towers of Hanoi problem with $n$ disks and $3$ pegs requires $2^n-1$ moves. Number the positions in the solution from index 0 (starting position, all disks on the first peg) to index $2^n-1$ (final position, all disks on the third peg).

Each of these $2^n$ positions can be considered as the starting configuration for a game of Nim, in which two players take turns to select a peg and remove any positive number of disks from it. The winner is the player who removes the last disk.

We define $f(n)$ to be the sum of the indices of those positions for which, when considered as a Nim game, the first player will lose (assuming an optimal strategy from both players).

For $n=4$, the indices of losing positions in the shortest solution are 3,6,9 and 12. So we have $f(4) = 30$.

You are given that $f(10) = 67518$.

Find $f(10^5)$. Give your answer modulo $1\,000\,000\,007$.

### 806. 汉诺塔上的尼姆游戏

此问题结合了尼姆取石子（Nim）游戏、汉诺塔问题两种游戏。如需这两种游戏的简介，请分别参阅 [301 题](https://fsy-juruo.github.io/pe-chinese-translation/problems/301.html)、[497 题](https://fsy-juruo.github.io/pe-chinese-translation/problems/497.html)。

对于有 $n$ 张圆盘，$3$ 个柱子的汉诺塔问题，其唯一的步骤数最少的解法需要 $2^n-1$ 次移动。我们将其过程中出现的盘面状态按序标号。初始状态（所有圆盘均在 1 号柱上）标为 $0$，最终状态（所有圆盘均在 3 号柱上）标为 $2^n-1$。

这 $2^n$ 个盘面状态均可以作为一次尼姆取石子游戏的初始状态。在此游戏中，两名玩家轮流选择一根柱子并从该柱子中移除任意数量（但不可为 0）的圆盘。移除最后一张圆盘者胜。

记 $f(n)$ 为满足如下条件的盘面状态的标号之和：当以此盘面状态作为一次取石子游戏的初始状态时，假定二人皆以最优策略进行操作，先手必败。

$n=4$ 时，标号为 $3$、$6$、$9$、$12$ 的盘面状态符合要求。故 $f(4) = 30$。同理可知 $f(10) = 67518$。

求 $f(10^5)$ 模 $1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。