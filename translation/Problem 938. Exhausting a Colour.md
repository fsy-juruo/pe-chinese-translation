### [938. Exhausting a Colour](https://projecteuler.net/problem=938)

A deck of cards contains $R$ red cards and $B$ black cards.  
A card is chosen uniformly randomly from the deck and removed. A second card is then chosen uniformly randomly from the cards remaining and removed.

- If both cards are red, they are discarded.
- If both cards are black, they are both put back in the deck.
- If they are different colours, the red card is put back in the deck and the black card is discarded.

Play ends when all the remaining cards in the deck are the same colour and let $P(R,B)$ be the probability that this colour is black. 

You are given $P(2,2) = 0.4666666667$, $P(10,9) = 0.4118903397$ and $P(34,25) = 0.3665688069$.

Find $P(24690,12345)$. Give your answer with 10 digits after the decimal point.

### 938. 耗尽同色牌

一副牌中含有 $R$ 张红色牌、$B$ 张黑色牌。我们从这副牌中随机均匀地选取一张牌，再从剩余的牌中随机均匀地选取第二张牌。

- 若两张牌都是红色的，则弃置这两张牌。
- 若两张牌都是黑色的，则将这两张牌放回牌堆。
- 否则，将红色的牌放回牌堆，并弃置黑色的牌。

如果牌堆中只剩一种颜色的牌，取牌过程立刻终止。记 $P(R, B)$ 为最终牌堆中只剩黑色的牌的概率。已知：$P(2,2) = 0.4666666667$、$P(10,9) = 0.4118903397$、$P(34,25) = 0.3665688069$。

求 $P(24690,12345)$。将你的答案四舍五入至小数点后第 10 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

