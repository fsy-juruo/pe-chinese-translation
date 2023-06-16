### [787. Bézout's Game](https://projecteuler.net/problem=787)

Two players play a game with two piles of stones. They take alternating turns. If there are currently $a$ stones in the first pile and $b$ stones in the second, a turn consists of removing $c\geq 0$ stones from the first pile and $d\geq 0$ from the second in such a way that $ad-bc=\pm1$. The winner is the player who first empties one of the piles.

Note that the game is only playable if the sizes of the two piles are coprime.

A game state $(a, b)$ is a winning position if the next player can guarantee a win with optimal play. Define $H(N)$ to be the number of winning positions $(a, b)$ with $\gcd(a,b)=1$, $a > 0$, $b > 0$ and $a+b \leq N$. Note the order matters, so for example $(2,1)$ and $(1,2)$ are distinct positions.

You are given $H(4)=5$ and $H(100)=2043$.

Find $H(10^9)$.

### 787. 裴蜀游戏

现有两名玩家，用着两堆石子，玩着一个游戏。二人轮流进行操作。  
若此时第一堆里有 $a$ 枚石子，第二堆里有 $b$ 枚石子。则某名玩家在操作时，可以从第一堆里拿走 $c$ 枚石子，从第二堆里拿走 $d$ 枚石子，且满足：$c \geq 0$、$d \geq 0$、$ad-bc=\pm1$。如果某玩家操作完毕后，取尽了某一堆石子，则该玩家获胜。

不难发现，只有当 $a,b$ 互质时，这个游戏才能玩。

若某个状态 $(a, b)$ 满足下一位玩家能在最优操作下保证获胜，则我们称这个状态为必胜态。再记 $H(N)$ 为满足 $\gcd(a,b)=1$、$a > 0$、$b > 0$ 且 $a+b \leq N$ 的必胜态 $(a, b)$ 的个数。注意，本题考虑顺序问题。比如说，$(2, 1)$ 和 $(1, 2)$ 在计算时，应被认为是两个不同的状态。已知 $H(4)=5$、$H(100)=2043$。

求 $H(10^9)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。