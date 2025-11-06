### [963. Removing Trits](https://projecteuler.net/problem=963)

**NOTE**: This problem is related to [Problem 882](https://projecteuler.net/problem=882). It is recommended to solve that problem before doing this one.

Two players are playing a game. When the game starts, each player holds a paper with two positive integers written on it.  
They make moves in turn. At a player's turn, the player can do one of the following:

- pick a number on the player's own paper and change it by removing a $0$ from its **ternary expansion**;
- pick a number on the opponent's paper and change it by removing a $1$ from its ternary expansion;
- pick a number on either paper and change it by removing a $2$ from its ternary expansion.

The player that is unable to make a move loses.  
Leading zeros are not allowed in any ternary expansion; in particular nobody can make a move on the number $0$.

An initial setting is called _fair_ if whichever player moves first will lose the game if both play optimally.

For example, if initially the integers on the paper of the first player are $1, 5$ and those on the paper of the second player are $2, 4$, then this is a fair initial setting, which we can denote as $(1, 5 \mid 2, 4)$.  
Note that the order of the two integers on a paper does not matter, but the order of the two papers matter.  
Thus $(5, 1 \mid 4, 2)$ is considered the same as $(1, 5 \mid 2, 4)$, while $(2, 4 \mid 1, 5)$ is a different initial setting.

Let $F(N)$ be the number of fair initial settings where each initial number does not exceed $N$.  
For example, $F(5) = 21$.

Find $F(10^5)$.

### 963. 移除三进制位

**注意**：本题与 [882 题](https://fsy-juruo.github.io/pe-chinese-translation/problems/882.html) 有关，我们推荐您在做这题之前先解决那道题。

两位玩家正在玩游戏。游戏开始时，每位玩家手上都持有一张写有两个正整数的纸。两人轮流操作，轮到某个玩家时，他可以执行如下操作中的一个：

- 选择自己的纸上写的一个数字，并移除这个数的 **三进制表示** 中的一个 $0$。
- 选择对手的纸上写的一个数字，并移除这个数的三进制表示中的一个 $1$。
- 选择任意一张纸上写的一个数字，并移除这个数的三进制表示中的一个 $2$。

首先无法操作者落败。  
注意，三进制表示中不允许前导零。特别的，$0$ 这个数无法被移除三进制位。

对某个初始局面，如果在双方都采取最优策略时，无论谁先手，先手均必败，则称这个初始局面是 *公平* 的。例如：如果初始时先手的纸上写有 $1, 5$、后手的纸上写有 $2, 4$，那么这个局面是公平的，我们将该局面记为 $(1, 5 \mid 2, 4)$。  
注意到，交换同一张纸上两个数字的顺序，对游戏结果没有影响；但是交换先手、后手的纸，对游戏结果是有影响的。于是，$(5, 1 \mid 4, 2)$ 和 $(1, 5 \mid 2, 4)$ 是同一个局面，但是 $(2, 4 \mid 1, 5)$ 是不同于 $(1, 5 \mid 2, 4)$ 的一个局面。

记 $F(N)$ 为：满足两张纸上写有的数均不超过 $N$ 的公平局面的数量。例如，$F(5) = 21$。

求 $F(10^5)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
