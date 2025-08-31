### [497. Drunken Tower of Hanoi](https://projecteuler.net/problem=497)

Bob is very familiar with the famous mathematical puzzle/game, "Tower of Hanoi," which consists of three upright rods and disks of different sizes that can slide onto any of the rods. The game begins with a stack of $n$ disks placed on the leftmost rod in descending order by size. The objective of the game is to move all of the disks from the leftmost rod to the rightmost rod, given the following restrictions:

1. Only one disk can be moved at a time.
2. A valid move consists of taking the top disk from one stack and placing it onto another stack (or an empty rod).
3. No disk can be placed on top of a smaller disk.

Moving on to a variant of this game, consider a long room $k$ units (square tiles) wide, labeled from $1$ to $k$ in ascending order. Three rods are placed at squares $a$, $b$, and $c$, and a stack of $n$ disks is placed on the rod at square $a$.

Bob begins the game standing at square $b$. His objective is to play the Tower of Hanoi game by moving all of the disks to the rod at square $c$. However, Bob can only pick up or set down a disk if he is on the same square as the rod/stack in question.

Unfortunately, Bob is also drunk. On a given move, Bob will either stumble one square to the left or one square to the right with equal probability, unless Bob is at either end of the room, in which case he can only move in one direction. Despite Bob's inebriated state, he is still capable of following the rules of the game itself, as well as choosing when to pick up or put down a disk.

The following animation depicts a side-view of a sample game for $n = 3$, $k = 7$, $a = 2$, $b = 4$, and $c = 6$:

![](images/0497_hanoi.gif)

Let $E(n, k, a, b, c)$ be the expected number of squares that Bob travels during a single optimally-played game. A game is played optimally if the number of disk-pickups is minimized.

Interestingly enough, the result is always an integer. For example, $E(2,5,1,3,5) = 60$ and $E(3,20,4,9,17) = 2358$.

Find the last nine digits of $\sum_{1\le n \le 10000} E(n,10^n,3^n,6^n,9^n)$.

### 497. 醉鬼的汉诺塔游戏

鲍勃对著名数学谜题 “汉诺塔” 很是熟悉。现有三根竖直的杆子和若干大小互异、可在任何杆子上上下滑动的圆盘。游戏开始时，所有 $n$ 个圆盘按从大到小的顺序堆放在最左侧的杆子上。游戏目标是在遵循如下规则的同时，将所有圆盘移至最右侧的杆子上：

1. 一次只能移动一个圆盘。
2. 你只能从某堆顶端取盘，并将其置于另一堆（或空杆）的顶端。
3. 不能将某个圆盘放在比它小的圆盘上方。

接着，我们考虑该游戏的一个变种。现有一条由 $k$ 个方格组成的长廊，方格分别编号为 $1 \sim k$。开始时，编号为 $a$、$b$、$c$ 的方格上分别立有一根杆子，$n$ 个圆盘堆放在位于 $a$ 号方格的杆上。

鲍勃初始时在 $b$ 号方格上，他的目标是遵循汉诺塔游戏的规则，把所有圆盘移到位于 $c$ 号方格的杆上。但是，为了从杆子上拿取（或放下）圆盘，他必须先移动到该杆所在的方格。

不幸的是，鲍勃喝醉了。除非鲍勃已处于长廊的两端，只能往一个方向走，否则，鲍勃每次移动都只能等概率的向左或向右蹒跚地行进一格。当然，纵使鲍勃已酩酊大醉，他仍然能够遵守游戏规则，并能理智的选择何时拿取、放下圆盘。

下面的动图从侧面视角展示了一例 $n = 3$、$k = 7$、$a = 2$、$b = 4$ 且 $c = 6$ 时的游戏过程：

![](images/0497_hanoi.gif)

记 $E(n, k, a, b, c)$ 为：鲍勃以最优策略完成游戏时，其行走过的格数的期望值。这里，我们认为，拿起圆盘的次数越少，策略越优秀。

有趣的是，这个期望一定是一个整数。例如，$E(2,5,1,3,5) = 60$、$E(3,20,4,9,17) = 2358$。

求 $\sum_{1\le n \le 10000} E(n,10^n,3^n,6^n,9^n)$ 的末九位数。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。