### [692. Siegbert and Jo](https://projecteuler.net/problem=692)

Siegbert and Jo take turns playing a game with a heap of $N$ pebbles:
1. Siegbert is the first to take some pebbles. He can take as many pebbles as he wants. (Between 1 and $N$ inclusive.)
2. In each of the following turns the current player must take at least one pebble and at most twice the amount of pebbles taken by the previous player.
3. The player who takes the last pebble wins.

Although Siegbert can always win by taking all the pebbles on his first turn, to make the game more interesting he chooses to take the smallest number of pebbles that guarantees he will still win (assuming both Siegbert and Jo play optimally for the rest of the game).
Let $H(N)$ be that minimal amount for a heap of $N$ pebbles.
$H(1)=1$, $H(4)=1$, $H(17)=1$, $H(8)=8$ and $H(18)=5$ .
Let $G(n)$ be $\displaystyle{\sum_{k=1}^n H(k)}$.
$G(13)=43$.
Find $G(23416728348467685)$.

### 692. 西格伯特与乔

西格伯特与乔两个人在轮流玩一个取石子的游戏。现在他们面前有一堆鹅卵石，这堆鹅卵石有 $N$ 枚。  
1. 西格伯特先取鹅卵石，他可以拿取 1 至 $N$ 枚鹅卵石。
2. 在之后的每一轮中，当前玩家必须至少拿取一枚鹅卵石，但拿取的鹅卵石的数量不能超过上一轮玩家拿取鹅卵石数量的两倍。 
3. 拿到最后一枚鹅卵石的玩家获胜。

尽管西格伯特可以通过在第一轮拿取所有鹅卵石来保证获胜，但为了使游戏更有意思，他会在保证获胜的前提下，在第一轮拿去数量尽量少的鹅卵石。

假设两人每一轮做出的都是最优决策，令 $H(N)$ 为在一轮有 $N$ 枚鹅卵石的游戏中，在保证获胜的前提下，西格伯特会拿取的最小的鹅卵石数。

已知 $H(1)=1$，$H(4)=1$，$H(17)=1$，$H(8)=8$ 并且 $H(18)=5$。
令 $G(n)$ 为 $\displaystyle{\sum_{k=1}^n H(k)}$，$G(13)=43$。
请计算 $G(23416728348467685)$。