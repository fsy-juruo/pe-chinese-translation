### [849. The Tournament](https://projecteuler.net/problem=849)

In a tournament there are $n$ teams and each team plays each other team twice. A team gets two points for a win, one point for a draw and no points for a loss.

With two teams there are three possible outcomes for the total points. $(4,0)$ where a team wins twice, $(3,1)$ where a team wins and draws, and $(2,2)$ where either there are two draws or a team wins one game and loses the other. Here we do not distinguish the teams and so $(3,1)$ and $(1,3)$ are considered identical.

Let $F(n)$ be the total number of possible final outcomes with $n$ teams, so that $F(2) = 3$.
You are also given $F(7) = 32923$.

Find $F(100)$. Give your answer modulo $10^9+7$.

### 849. 锦标赛

某锦标赛有 $n$ 支队伍参加。每支队伍将与其余每支队伍进行两次比赛。每场比赛的胜者得 2 分，败者得 0 分；若双方战平，则双方各得 1 分。

只有两支队伍时，它们可能的得分情况只会有如下 3 种：某队胜两次，则两队得分情况为 $(4, 0)$；某队胜一次、平一次，则两队得分情况为 $(3, 1)$；两队都胜一场、败一场，则两队得分情况为 $(2, 2)$。本题中不考虑不同队伍所带来的顺序问题，也就是说，$(3, 1)$ 和 $(1, 3)$ 被认为是相同的得分情况。

我们记在有 $n$ 支队伍参赛时，可能的得分情况的数量为 $F(n)$。已知 $F(2) = 3$、$F(7) = 32923$。

求 $F(100)$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。