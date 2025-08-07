### [951. A Game of Chance](https://projecteuler.net/problem=951)

Two players play a game using a deck of $2n$ cards: $n$ red and $n$ black. Initially the deck is shuffled into one of the $\binom{2n}{n}$ possible starting configurations. Play then proceeds, alternating turns, where a player follows two steps on each turn:

1. Remove the top card from the deck, taking note of its colour.
2. If there is a next card and it is the same colour as the previous card they toss a fair coin. If the coin lands on heads they remove that card as well; otherwise leave it on top of the deck.

The player who removes the final card from the deck wins the game.

Some starting configurations give an advantage to one of the players; while some starting configurations are **fair**, in which both players have exactly $50\%$ chance to win the game. For example, if $n=2$ there are four starting configurations which are fair: RRBB, BBRR, RBBR, BRRB. The remaining two, RBRB and BRBR, result in a guaranteed win for the second player.

Define $F(n)$ to be the number of starting configurations which are fair. Therefore $F(2)=4$. You are also given $F(8)=11892$.

Find $F(26)$.


### 951. 一个机遇游戏 [^1]

[^1]: game of chance 意指靠碰运气（而非技巧）取胜的游戏。

现有一副由 $n$ 张黑色卡牌和 $n$ 张红色卡牌组成的牌堆，两位玩家正用它玩游戏：将这副牌洗成 $\binom{2n}{n}$ 种可能牌型的一种，作为初始牌堆，随后游戏开始，二人轮流操作。每一轮中，对应玩家需照做如下两步：

1. 将牌堆最顶端的牌移除，并记下这张牌的颜色。
2. 如果下一张牌和刚移除的牌颜色相同，就抛掷一枚公平硬币。若抛出正面，则把这张牌也移除；否则，不动这张牌。

移走牌堆中最后一张牌的玩家获胜。

某些初始牌堆会让一方占据优势，而某些初始牌堆是 **公平的**，能使双方获胜的概率都是 $50\%$。例如，$n = 2$ 时，共有红红黑黑、黑黑红红、红黑黑红、黑红红黑四个公平的初始牌堆，如果初始牌堆是红黑红黑、黑红黑红，则后手必胜。

记 $F(n)$ 为：有 $n$ 张黑色的牌、$n$ 张红色的牌时，公平的初始牌堆数量。于是 $F(2) = 4$，你也知道 $F(8) = 11892$。

求 $F(26)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

