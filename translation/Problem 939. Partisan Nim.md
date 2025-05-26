### [939. Partisan Nim](https://projecteuler.net/problem=939)

Two players A and B are playing a variant of Nim.  
At the beginning, there are several piles of stones. Each pile is either at the side of A or at the side of B. The piles are unordered.

They make moves in turn. At a player's turn, the player can
- either choose a pile on the opponent's side and remove one stone from that pile;
- or choose a pile on their own side and remove the whole pile.

The winner is the player who removes the last stone.

Let $E(N)$ be the number of initial settings with at most $N$ stones such that, whoever plays first, A always has a winning strategy.

For example $E(4) = 9$; the settings are:

| Nr. | Piles at the side of A | Piles at the side of B |
| :---: | :---: | :---: |
| 1 | $4$ | none |
| 2 | $1,3$ | none |
| 3 | $2,2$ | none |
| 4 | $1,1,2$ | none |
| 5 | $3$ | $1$ |
| 6 | $1,2$ | $1$ |
| 7 | $2$ | $1,1$ |
| 8 | $3$ | none |
| 9 | $2$ | none |

Find $E(5000) \bmod 1234567891$.

### 939. 不公平尼姆游戏

A、B 两位玩家正在玩一个变种尼姆游戏。游戏开始时，他们面前有若干堆无序的石子，每堆石子要么在靠 A 的一侧、要么在靠 B 的一侧。

他们轮流进行操作。轮到某玩家操作时，他可以
- 要么，在靠对手一侧的石子中，移除一颗石子。
- 要么，在靠自己这侧的石子中，移除 **一堆** 石子。

移除最后一颗石子的人获胜。

记 $E(N)$ 为满足如下条件的初始状态的数量：共含有 $\leq N$ 颗石子且能使得先手有必胜策略。例如 $E(4) = 9$，这 $9$ 个初始状态是：

| 序号 | 在 A 这侧的石子堆 | 在 B 这侧的石子堆 |
| :---: | :---: | :---: |
| 1 | $4$ | 无 |
| 2 | $1,3$ | 无 |
| 3 | $2,2$ | 无 |
| 4 | $1,1,2$ | 无 |
| 5 | $3$ | $1$ |
| 6 | $1,2$ | $1$ |
| 7 | $2$ | $1,1$ |
| 8 | $3$ | 无 |
| 9 | $2$ | 无 |

求 $E(5000) \bmod 1234567891$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

