### [899. DistribuNim I](https://projecteuler.net/problem=899)

Two players play a game with two piles of stones. The players alternately take stones from one or both piles, subject to:

- the total number of stones taken is equal to the size of the smallest pile before the move;
- the move cannot take all the stones from a pile.


The player that is unable to move loses.

For example, if the piles are of sizes 3 and 5 then there are three possible moves.

$$
(3,5) \xrightarrow{(2,1)} (1,4)\qquad\qquad (3,5) \xrightarrow{(1,2)} (2,3)\qquad\qquad (3,5) \xrightarrow{(0,3)} (3,2)
$$

Let $L(n)$ be the number of ordered pairs $(a,b)$ with $1 \leq a,b \leq n$ such that the initial game position with piles of sizes $a$ and $b$ is losing for the first player assuming optimal play.

You are given $L(7) = 21$ and $L(7^2) = 221$.

Find $L(7^{17})$.

### 899. 分布式取石子游戏 1

两位玩家用两堆石子玩游戏，两人须在遵守如下规则的同时，轮流从一个石堆或者两个石堆中取石子：

- 玩家本轮取走的石子总数需等于该轮开始前，含有较少石子的石堆中的石子数。
- 不能把其中任何一个石堆取空。

首先无法操作的玩家落败。

例如，倘若初始时两个石堆各含 3、5 枚石子，那么此时先手有三种可行操作：

$$
(3,5) \xrightarrow{(2,1)} (1,4)\qquad\qquad (3,5) \xrightarrow{(1,2)} (2,3)\qquad\qquad (3,5) \xrightarrow{(0,3)} (3,2)
$$

记 $L(n)$ 为满足如下条件的有序对 $(a, b)$ 的数量：$1 \leq a, b \leq n$，且若初始时两个石堆各含 $a$、$b$ 枚石子，那么在两位玩家都以最优策略操作时，先手必败。

已知 $L(7) = 21$、$L(7^2) = 221$。

求 $L(7^{17})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

