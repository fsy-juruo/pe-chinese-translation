### [253. Tidying Up A](https://projecteuler.net/problem=253)

A small child has a “number caterpillar” consisting of forty jigsaw pieces, each with one number on it, which, when connected together in a line, reveal the numbers $1$ to $40$ in order.

Every night, the child's father has to pick up the pieces of the caterpillar that have been scattered across the play room. He picks up the pieces at random and places them in the correct order.   
As the caterpillar is built up in this way, it forms distinct segments that gradually merge together.   
The number of segments starts at zero (no pieces placed), generally increases up to about eleven or twelve, then tends to drop again before finishing at a single segment (all pieces placed).

For example:

| Piece Placed | Segments So Far |
| :----------: | :-------------: |
|      12      |        1        |
|      4       |        2        |
|      29      |        3        |
|      6       |        4        |
|      34      |        5        |
|      5       |        4        |
|      35      |        4        |
|     ...      |       ...       |

Let $M$ be the maximum number of segments encountered during a random tidy-up of the caterpillar.  
For a caterpillar of ten pieces, the number of possibilities for each $M$ is

| $M$  | Possibilities |
| :--: | :-----------: |
|  1   |      512      |
|  2   |    250912     |
|  3   |    1815264    |
|  4   |    1418112    |
|  5   |    144000     |

so the most likely value of $M$ is $3$ and the average value is $385643/113400 = 3.400732$, rounded to six decimal places.

The most likely value of $M$ for a forty-piece caterpillar is $11$; but what is the average value of $M$?

Give your answer rounded to six decimal places.

### 253. 收拾拼图 1

一个小朋友有一副由 $40$ 块拼图组成的 “数字毛毛虫” 玩具 [^1]，每块拼图上都标有一个数字。这些拼图按正确顺序连成一条线后，会按顺序显现出 $1$ 至 $40$ 中的数字。

[^1]: number caterpillar 或 counting caterpillar 是常见的孩童启蒙玩具。一般由圆形卡纸（供孩童自行 DIY）或木制拼版制成。此处我们尊重原文中的 jigsaw puzzle。

每天晚上，小朋友的父亲须把散落于游戏室中的拼图收拾好。他会不断完全随机的捡起一片拼图，将其放到正确的位置上，直到所有拼图全部归位。  
上述过程中，已归位的拼图会形成若干不相连的连续段，而后逐渐被合并，最终形成一条完整的毛毛虫。  
初始时没有拼图归位，没有形成连续段。随着诸拼图的归位，连续段的数量会上涨至约 $11$ 或 $12$，随后趋于下降，直至所有拼图都已归位，所有连续段都被合为一段。

以下是一种可能的拼图归位的过程，和该过程中形成的连续段数量：[^2]

| 归位的拼图的编号 | 形成的连续段数量 |
| :----------: | :-------------: |
|      12      |        1        |
|      4       |        2        |
|      29      |        3        |
|      6       |        4        |
|      34      |        5        |
|      5       |        4        |
|      35      |        4        |
|     ...      |       ...       |

[^2]: 如果对题目有疑义的话：先前 $4$ 号拼图、$6$ 号拼图各成一个连续段，在 $5$ 号拼图归位后，三块拼图相连形成了 $[4, 5, 6]$ 连续段，从而使得连续段的数量减少 $1$。

我们将拼图归位过程中，形成的连续段数量的最大值记为 $M$。  
对一个由 $10$ 块拼图组成的 “数字毛毛虫”，根据 $M$ 的不同，可能的归位过程的总数如下：

| $M$  | 可能归位方法的总数 |
| :--: | :-----------: |
|  1   |      512      |
|  2   |    250912     |
|  3   |    1815264    |
|  4   |    1418112    |
|  5   |    144000     |

此时，$M$ 最有可能是 $3$，$M$ 的平均值是 $385643/113400$，四舍五入至小数点后第六位的结果是 $3.400732$。

对一个由 $40$ 块拼图组成的 “数字毛毛虫”，$M$ 最有可能是 $11$。但 $M$ 的平均值是多少？

将你的答案四舍五入至小数点后第六位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
