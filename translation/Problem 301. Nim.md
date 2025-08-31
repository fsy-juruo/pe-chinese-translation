### [301. Nim](https://projecteuler.net/problem=301)

*Nim* is a game played with heaps of stones, where two players take it in turn to remove any number of stones from any heap until no stones remain.

We'll consider the three-heap normal-play version of Nim, which works as follows:

- At the start of the game there are three heaps of stones.
- On each player's turn, the player may remove any positive number of stones from any single heap.
- The first player unable to move (because no stones remain) loses.

If $(n_1,n_2,n_3)$ indicates a Nim position consisting of heaps of size $n_1$, $n_2$, and $n_3$, then there is a simple function, which you may look up or attempt to deduce for yourself, $X(n_1,n_2,n_3)$ that returns:

- zero if, with perfect strategy, the player about to move will eventually lose; or
- non-zero if, with perfect strategy, the player about to move will eventually win.

For example $X(1,2,3) = 0$ because, no matter what the current player does, the opponent can respond with a move that leaves two heaps of equal size, at which point every move by the current player can be mirrored by the opponent until no stones remain; so the current player loses. To illustrate:

- current player moves to $(1,2,1)$
- opponent moves to $(1,0,1)$
- current player moves to $(0,0,1)$
- opponent moves to $(0,0,0)$, and so wins.

For how many positive integers $n \le 2^{30}$ does $X(n,2n,3n) = 0$ ?

### 301. 尼姆游戏

在 *尼姆取石子游戏* 中，玩家需轮流从若干堆石子中，任取一个石堆并从中取走若干枚石子，直至所有石子均被取走。

我们考虑含三堆石子的标准游玩 [^1] 尼姆游戏，其流程为：

[^1]: 在组合博弈论中，若某组合游戏的获胜规则是走出最后一步的玩家获胜，则称该游戏是标准游玩 (normal-play) 的。

- 游戏开始时，有三堆石子。
- 轮到某位玩家行动时，玩家可以任选一堆石子，并从中取走任意多枚石子（但不能不取）。
- 首先无法行动的玩家落败。

记 $(n_1,n_2, n_3)$ 表示：由分别含有 $n_1$、$n_2$、$n_3$ 枚石子的石堆进行的尼姆游戏，那么，通过查阅资料或自行推导，可以得到：存在一个简单函数 [^2] $X(n_1, n_2, n_3)$，满足，若两位玩家都绝顶聪明，那么：

[^2]: 若某个函数的值域只由有限个元素组成，则称其为简单函数 (simple function)。

- 若先手必败，则 $X(n_1, n_2, n_3) = 0$。
- 若先手必胜，则 $X(n_1, n_2, n_3) \neq 0$。

例如，$X(1, 2, 3) = 0$。因为不管先手如何操作，后手都能在一次操作内，留下数量相同的两堆石子。届时，后手一直能模仿先手的操作，直至石子被取完。从而先手必败。举例来说：

- 先手从第三堆中取走两枚石子，当前状态：$(1,2,1)$。
- 后手从第二堆中取走两枚石子，当前状态：$(1,0,1)$。
- 先手从第三堆中取走一枚石子，当前状态：$(0,0,1)$。
- 后手从第一堆中取走一枚石子，当前状态：$(0,0,0)$，后手获胜。

对全体 $n \leq 2^{30}$ 的正整数，有多少个 $n$ 满足 $X(n,2n,3n) = 0$？

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。