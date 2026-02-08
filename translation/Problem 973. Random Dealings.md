### [973. Random Dealings](https://projecteuler.net/problem=973)

A game is played with $n$ cards.
At the start the cards are dealt out onto a table to get $n$ piles of size one.

Each round proceeds as follows:

- Select a pile at random and pick it up.
- Randomly choose a pile from the table and add the top card of the picked-up pile to it.
- Redistribute any remaining cards from the picked-up pile by dealing them into new single-card piles.

The game ends when all cards are in a single pile.

At the end of each round a score is obtained by bitwise-XORing the size of each pile. The score is summed across the rounds. Let $X(n)$ be the expected total score at the end of the game.

You are given $X(2) = 2$, $X(4) = 14$ and $X(10) = 1418$.

Find $X(10^4)$. Give your answer modulo $10^9+7$.

### 973. 随机发牌

我们用 $n$ 张牌玩一个游戏：初始时，我们把牌分发到桌面上，形成 $n$ 个只含一张牌的牌堆。

接下来每一轮的流程如下：

- 随机地取一堆牌，并将其从桌上拿起。
- 从桌上随机选择一堆牌，并将拿起的牌堆中的顶牌加入选中的牌堆。
- 把拿起的牌堆中的其他牌重新分发到桌面上，形成若干只含一张牌的牌堆。

当所有排都处于同一牌堆中时，游戏结束，

每轮游戏结束时，我们将每个牌堆所含牌数作异或，作为此轮的分数。游戏的最终得分是每一轮分数的加和。记 $X(n)$ 是游戏的最终得分的期望。

已知 $X(2) = 2$、$X(4) = 14$ 且 $X(10) = 1418$。

求 $X(10^4)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
