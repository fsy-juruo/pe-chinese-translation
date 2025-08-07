### [948. Left vs Right](https://projecteuler.net/problem=948)

Left and Right play a game with a word consisting of L's and R's, alternating turns. On Left's turn, Left can remove any positive number of letters, but not all the letters, from the left side of the word. Right does the same on Right's turn except that Right removes letters from the right side. The game continues until only one letter remains: if it is an 'L' then Left wins; if it is an 'R' then Right wins.

Let $F(n)$ be the number of words of length $n$ where the player moving first, whether it's Left or Right, will win the game if both play optimally.

You are given $F(3)=4$ and $F(8)=181$.

Find $F(60)$.

### 948. 小左对小右

小左和小右正用一个只含 L、R 的词玩游戏。两人轮流进行操作，轮到小左操作时，小左可以删去这个词左侧的若干个字符，但不能不删或全删；小右可以删去这个词右侧的若干个字符，但不能不删或全删。当这个词只剩一个字母时，游戏结束。如果剩下的字符是 L，那么小左获胜；反之小右获胜。

记 $F(n)$ 为：若双方都按最优方式决策，不论谁是先手，都能保证先手获胜的长度为 $n$ 的词的数量。你已知 $F(3)=4$、$F(8)=181$。

求 $F(60)$。


---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

