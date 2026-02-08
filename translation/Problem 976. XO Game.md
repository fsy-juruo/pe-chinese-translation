### [976. XO Game](https://projecteuler.net/problem=976)

Two players X and O play a game with $k$ strips of squares of lengths $n_1,\dots,n_k$, originally all blank.

Starting with X, they make moves in turn. At X's turn, X draws an "X" symbol; at O's turn, O draws an "O" symbol.  
The symbol must be drawn in one blank square with either red or blue pen, subject to the following restrictions:

1. two symbols in adjacent squares on one strip must be different symbols **and** must have different colour;
2. if there is at least one blank strip, then one must draw on a blank strip.

Whoever does not have a valid move loses the game.
Let $P(K, N)$ be the number of tuples $(n_1,\dots,n_k)$ such that $1 \leq k \leq K$, $1\leq n_1\leq\cdots\leq n_k\leq N$ and that X has a winning strategy to the corresponding game.  
For example, $P(2, 4)=7$ and $P(5, 10) = 901$.

Find $P(10^7, 10^7)\bmod 1234567891$.

### 976. 叉圈游戏

小叉和小圈正用 $k$ 张分别含 $n_1, n_2, \cdots, n_k$ 个放个的纸带玩游戏，初始时所有方格均空白。

由小叉先手，二人轮流操作。小叉的回合中，他需画下一个 "X"；小圈的回合中，他需画下一个 "O"；这些符号需用红笔或蓝笔，绘制在任意一个空白方格上，并满足下述要求：

1. 同一纸带上相邻格子中的两个符号必须不同，**且** 他们的颜色也必须不同。
2. 如果至少有一张完全空白的纸带，那么玩家只能把符号绘制在完全空白的纸带上。

无法操作者落败。

记 $P(K, N)$ 为满足如下条件的 $(n_1,\dots,n_k)$ 的数量：$1 \leq k \leq K$、$1\leq n_1\leq\cdots\leq n_k\leq N$、在对应游戏下，小叉有必胜策略。  
例如有 $P(2, 4)=7$、$P(5, 10) = 901$。

求 $P(10^7, 10^7)\bmod 1234567891$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
