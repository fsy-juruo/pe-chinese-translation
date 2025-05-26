### [888. 1249 Nim](https://projecteuler.net/problem=888)

Two players play a game with a number of piles of stones, alternating turns. Each turn a player can choose to remove 1, 2, 4, or 9 stones from a single pile; or alternatively they can choose to split a pile containing two or more stones into two non-empty piles. The winner is the player who removes the last stone.

A collection of piles is called a losing position if the player to move cannot force a win with optimal play. Define $S(N, m)$ to be the number of distinct losing positions arising from $m$ piles of stones where each pile contains from $1$ to $N$ stones. Two positions are considered equivalent if they consist of the same pile sizes. That is, the order of the piles does not matter.

You are given $S(12,4)=204$ and $S(124,9)=2259208528408$.

Find $S(12491249,1249)$. Give your answer modulo $912491249$.

### 888. 1249 尼姆游戏

两位玩家正在玩取石子游戏。他们面前有几堆石子，二人轮流进行如下操作之一：

- 从一堆石子中取走 1、2、4 或 9 枚石子。
- 将含有 $\geq 2$ 枚石子的一堆石子分为非空的两堆石子。

取走最后一枚石子的玩家胜。

如果若干堆石子满足：以这些石子为初始状态，先手采取最佳策略时无法保证获胜，则称这若干堆石子是失败态。记 $S(N, m)$ 为由 $m$ 堆石子、每堆内石子数量在 $[1, N]$ 内的失败态数量。我们不考虑堆间的顺序，也就是说，如果两个状态中每一堆中石子数量的分布完全相同，则认为这两个状态等价。

已知 $S(12,4)=204$、$S(124,9)=2259208528408$。

求 $S(12491249,1249)$ 模 $912491249$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

