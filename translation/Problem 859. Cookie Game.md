### [859. Cookie Game](https://projecteuler.net/problem=859)

Odd and Even are playing a game with $N$ cookies.

The game begins with the $N$ cookies divided into one or more piles, not necessarily of the same size. They then make moves in turn, starting with Odd.  
Odd's turn: Odd may choose any pile with an <b>odd</b> number of cookies, eat one and divide the remaining (if any) into two equal piles.  
Even's turn: Even may choose any pile with an <b>even</b> number of cookies, eat two of them and divide the remaining (if any) into two equal piles.  
The player that does not have a valid move loses the game.

Let $C(N)$ be the number of ways that $N$ cookies can be divided so that Even has a winning strategy.  
For example, $C(5) = 2$ because there are two winning configurations for Even: a single pile containing all five cookies; three piles containing one, two and two cookies.  
You are also given $C(16) = 64$.

Find $C(300)$.

### 859. 曲奇游戏

小奇和小偶正用 $N$ 片曲奇玩游戏。游戏开始前，这 $N$ 片曲奇将被分为若干大小不一定相等的堆。

随后，由小奇先手，二人轮流进行操作：
- 在小奇的回合中，他可以选择含**奇数**片曲奇的一堆曲奇，吃掉其中一片曲奇后，将该堆中剩余的曲奇均分成两堆。
- 在小偶的回合中，他可以选择含**偶数**片曲奇的一堆曲奇，吃掉其中两片曲奇后，将该堆中剩余的曲奇均分成两堆。

无法行动的玩家落败。

记：将 $N$ 片曲奇分堆的所有方法中，有 $C(N)$ 种能使得小偶有必胜策略。例如，$C(5) = 2$。因为你可以将 $5$ 片曲奇单独成堆，或者将其分为大小分别为 $2$、$2$、$1$ 的三堆，这两种情况下，小偶都有必胜策略。

已知 $C(16) = 64$。

求 $C(300)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
