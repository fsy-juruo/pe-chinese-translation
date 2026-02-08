### [900. DistribuNim II](https://projecteuler.net/problem=900)

Two players play a game with at least two piles of stones. The players alternately take stones from one or more piles, subject to:

- the total number of stones taken is equal to the size of the smallest pile before the move;
- the move cannot take all the stones from a pile.

The player that is unable to move loses.

For example, if the piles are of sizes 2, 2 and 4 then there are four possible moves.

$$
(2,2,4)\xrightarrow{(1,1,0)}(1,1,4)\quad (2,2,4)\xrightarrow{(1,0,1)}(1,2,3)\quad
(2,2,4)\xrightarrow{(0,1,1)}(2,1,3)\quad (2,2,4)\xrightarrow{(0,0,2)}(2,2,2)
$$

Let $t(n)$ be the smallest nonnegative integer $k$ such that the position with $n$ piles of $n$ stones and a single pile of $n+k$ stones is losing for the first player assuming optimal play.  For example, $t(1) = t(2) = 0$ and $t(3) = 2$.

Define $\displaystyle S(N) = \sum_{n=1}^{2^N} t(n)$.  You are given $S(10) = 361522$.

Find $S(10^4)$. Give your answer modulo $900497239$.

### 900. 分布式取石子游戏 2

两位玩家用至少两堆石子玩游戏，两人须在遵守如下规则的同时，轮流从一个石堆或者两个石堆中取石子：

- 玩家本轮取走的石子总数需等于该轮开始前，含有较少石子的石堆中的石子数。
- 不能把其中任何一个石堆取空。

首先无法操作的玩家落败。

例如，倘若初始时有各含 2、2、4 枚石子的三个石堆，那么此时先手有四种可行操作：

$$
(2,2,4)\xrightarrow{(1,1,0)}(1,1,4)\quad (2,2,4)\xrightarrow{(1,0,1)}(1,2,3)\quad
(2,2,4)\xrightarrow{(0,1,1)}(2,1,3)\quad (2,2,4)\xrightarrow{(0,0,2)}(2,2,2)
$$

记 $t(n)$ 为满足如下条件的最小非负整数 $k$：若初始时有 $n$ 个含 $n$ 枚石子的石堆、$1$ 个含 $n + k$ 枚石子的石堆，在两人都以最优策略操作时，先手必败。例如：$t(1) = t(2) = 0$、$t(3) = 2$。

记 $\displaystyle S(N) = \sum_{n=1}^{2^N} t(n)$。已知 $S(10) = 361522$。

求 $S(10^4)$ 模 $900497239$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

