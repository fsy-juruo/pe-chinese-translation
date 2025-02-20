### [928. Cribbage](https://projecteuler.net/problem=928)

This problem is based on (but not identical to) the scoring for the card game [Cribbage](https://en.wikipedia.org/wiki/Cribbage)

Consider a normal pack of $52$ cards. A Hand is a selection of one or more of these cards.

For each Hand the *Hand score* is the sum of the values of the cards in the Hand where the value of Aces is $1$ and the value of court cards (Jack, Queen, King) is $10$.

The *Cribbage score* is obtained for a Hand by adding together the scores for:

- Pairs. A pair is two cards of the same rank. Every pair is worth $2$ points.
- Runs. A run is a set of at least $3$ cards whose ranks are consecutive, e.g. 9, 10, Jack. Note that Ace is never high, so Queen, King, Ace is <b>not</b> a valid run. The number of points for each run is the size of the run. All locally maximum runs are counted. For example, 2, 3, 4, 5, 7, 8, 9 the two runs of 2, 3, 4, 5 and 7, 8, 9 are counted but not 2, 3, 4 or 3, 4, 5.
- Fifteens. A fifteen is a combination of cards that has value adding to $15$. Every fifteen is worth $2$ points. For this purpose the value of the cards is the same as in the Hand Score.

For example, $(5 \spadesuit, 5 \clubsuit, 5 \diamondsuit, K \heartsuit)$ has a Cribbage score of $14$ as there are four ways that fifteen can be made and also three pairs can be made.

The example $( A \diamondsuit, A \heartsuit, 2 \clubsuit, 3 \heartsuit, 4 \clubsuit, 5 \spadesuit)$ has a Cribbage score of $16$: two runs of five worth $10$ points, two ways of getting fifteen worth $4$ points and one pair worth $2$ points. In this example the Hand score is equal to the Cribbage score.

Find the number of Hands in a normal pack of cards where the Hand score is equal to the Cribbage score.

### 928. 克里比奇牌戏

本题基于 [克里比奇牌戏](https://en.wikipedia.org/wiki/Cribbage) 的计分方式（但不完全相同）。

考虑一副 $52$ 张牌的标准扑克。一手牌指的是该扑克中的一张或者多张牌。

对于每一手牌，其 *手牌得分* 的计算方式为：把该手牌中每张牌的数值相加得到的值。其中 A 的数值计为 $1$、花牌（J、Q、K）的数值计为 $10$。

对于每一手牌，其 *克里比奇得分* 是以下三项得分的总和：

- 对子：点数相同的两张牌是称为对子。每个对子计 $2$ 分。
- 顺子：点数连续的 $\geq 3$ 张牌称为顺子，例如：9、10、J 就是一个顺子。注意此处 A 的优先级最低，也就是说 Q、K、A **不**算做顺子。每个顺子的得分是该顺子中的牌数。注意，在计分时，我们只统计极长的顺子。例如，对于 2、3、4、5、7、8、9 这手牌，我们在计分时只考虑 2、3、4、5 和 7、8、9 这两个顺子，而不考虑 2、3、4 和 3、4、5 这两个顺子。
- 十五点：若干数值之和为 $15$ 的牌称为十五点。每个十五点计 $2$ 分。这里数值的定义和计算手牌得分时使用的定义相同。

例如，$(5 \spadesuit, 5 \clubsuit, 5 \diamondsuit, K \heartsuit)$ 的克里比奇得分是 $14$，因为这手牌有 4 个十五点和 3 个对子。而 $( A \diamondsuit, A \heartsuit, 2 \clubsuit, 3 \heartsuit, 4 \clubsuit, 5 \spadesuit)$  的克里比奇得分是 $16$：两个长度为 5 的顺子一共 $10$ 分，两个十五点计 $4$ 分，一个对子计 $2$ 分。可以发现，这手牌的手牌得分恰等于克里比奇得分。


在一副 $52$ 张牌的标准扑克中，有多少手牌的手牌得分恰等于克里比奇得分？

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。