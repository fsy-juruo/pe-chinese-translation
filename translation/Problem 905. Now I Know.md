### [905. Now I Know](https://projecteuler.net/problem=905)

Three epistemologists, known as A, B, and C, are in a room, each wearing a hat with a number on it. They have been informed beforehand that all three numbers are positive and that one of the numbers is the sum of the other two.

Once in the room, they can see the numbers on each other's hats but not on their own. Starting with A and proceeding cyclically, each epistemologist must either honestly state "I don't know my number" or announce "Now I know my number!" which terminates the game.

For instance, if their numbers are $A=2, B=1, C=1$ then A declares "Now I know" at the first turn. If their numbers are $A=2, B=7, C=5$ then "I don't know" is heard four times before B finally declares "Now I know" at the fifth turn.

Let $F(A,B,C)$ be the number of turns it takes until an epistemologist declares "Now I know", including the turn this declaration is made. So $F(2,1,1)=1$ and $F(2,7,5)=5$.

Find $\displaystyle \sum_{a=1}^7 \sum_{b=1}^{19} F(a^b, b^a, a^b + b^a)$.

### 905. 现在我知道了

三位认识论学者 A、B、C 正待在同一个房间里玩游戏。他们每个人头上都戴了一顶写有数字的帽子。他们已经知悉：帽子上的数都是正整数，且其中一顶帽子上的数恰好是另外两顶帽子上的数之和。

他们能够看到另外两个人帽子上的数，但是看不到自己帽子上的数。随后，A、B、C 三人从 A 开始，轮流、诚实地回答如下问题：「你知道自己的数了吗？」如果答案为是，则游戏即刻终止。

例如，A、B、C 三人头顶上的数分别是 $2$、$1$、$1$，则 A 立刻宣布他知道了自己的数。若 A、B、C 三人头顶上的数分别是 $2$、$7$、$5$，那么在前四轮中，A、B、C、A 都会回答「不知道」，直到第五轮中，B 回答「知道」，从而终止游戏。

记 $F(A,B,C)$ 为：若 A、B、C 头顶的数分别是 $A$、$B$、$C$，游戏结束时一共提问了多少轮。从而可得 $F(2,1,1)=1$、$F(2,7,5)=5$。

求 $\displaystyle \sum_{a=1}^7 \sum_{b=1}^{19} F(a^b, b^a, a^b + b^a)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。


