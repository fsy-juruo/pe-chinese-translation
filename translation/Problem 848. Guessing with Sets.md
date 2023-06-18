### [848. Guessing with Sets](https://projecteuler.net/problem=848)

Two players play a game. At the start of the game each player secretly chooses an integer; the first player from $1,...,n$ and the second player from $1,...,m$. Then they take alternate turns, starting with the first player. The player, whose turn it is, displays a set of numbers and the other player tells whether their secret number is in the set or not. The player to correctly guess a set with a single number is the winner and the game ends.

Let $p(m,n)$ be the winning probability of the first player assuming both players play optimally. For example $p(1, n) = 1$ and $p(m, 1) = 1/m$.

You are also given $p(7,5) \approx 0.51428571$.

Find $\displaystyle \sum_{i=0}^{20}\sum_{j=0}^{20} p(7^i, 5^j)$ and give your answer rounded to 8 digits after the decimal point.

### 848. 集合猜数游戏

两位玩家在玩一个猜数字的游戏。开始时，第一位、第二位玩家分别从 $[1, n]$ 的正整数、$[1, m]$ 的正整数中选择一个数，两人都把自己选择的数保密。随后从第一位玩家开始，两人轮流告诉对方一个正整数集，而对方必须如实回答自己所选择的数是否在该正整数集中。最先猜出对方所选择的数的人即为胜者。

假设两人均采取最优策略，记 $p(m, n)$ 为第一位玩家获胜的概率。如有 $p(1, n) = 1$、$p(m, 1) = 1/m$。亦已知：$p(7,5) \approx 0.51428571$。

求 $\displaystyle \sum_{i=0}^{20}\sum_{j=0}^{20} p(7^i, 5^j)$，将你的答案四舍五入至小数点后第 8 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

