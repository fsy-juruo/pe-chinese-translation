### [798. Card Stacking Game](https://projecteuler.net/problem=798)

Two players play a game with a deck of cards which contains $s$ suits with each suit containing $n$ cards numbered from $1$ to $n$.

Before the game starts, a set of cards (which may be empty) is picked from the deck and placed face-up on the table, with no overlap. These are called the visible cards.

The players then make moves in turn.
A move consists of choosing a card X from the rest of the deck and placing it face-up on top of a visible card Y, subject to the following restrictions:

* X and Y must be the same suit;
* the value of X must be larger than the value of Y.

The card X then covers the card Y and replaces Y as a visible card.
The player unable to make a valid move loses and play stops.

Let $C(n, s)$ be the number of different initial sets of cards for which the first player will lose given best play for both players.

For example, $C(3, 2) = 26$ and $C(13, 4) \equiv 540318329 \pmod {1\,000\,000\,007}$.

Find $C(10^7, 10^7)$. Give your answer modulo $1\,000\,000\,007$.


### 798. 卡堆叠游戏

某副牌有 $s$ 种花色，每种花色里都有标号为 $1$ 至 $n$ 的 $n$ 张牌。两位玩家正用这副牌来玩一个游戏。

游戏开始前，二人从这副牌中选出一部分初始牌（可以不选），将初始牌一张一张面朝上放在桌上，牌与牌之间不重叠。这部分初始牌称作可见牌。

接下来，两名玩家轮流进行操作。
一次操作中，玩家从剩余牌堆中选出一张牌 X，并把它按如下要求面朝上放置在一张可见牌 Y 的上方：

* X 与 Y 的花色必须相同。
* X 的标号必须大于 Y。

随后，牌 X 把牌 Y 盖住，成为新的可见牌。最终无法操作的玩家输。

记 $C(n, s)$ 为假定两人均以最优策略游戏的情况下，先手必败的挑选初始牌的方法数。如 $C(3, 2) = 26$、$C(13, 4) \equiv 540318329 \pmod {1\,000\,000\,007}$。

求 $C(10^7, 10^7)$ 模 $1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。