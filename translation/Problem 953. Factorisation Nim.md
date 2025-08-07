### [953. Factorisation Nim](https://projecteuler.net/problem=953)

In the classical game of **Nim** two players take turns removing stones from piles. A player may remove any positive number of stones from a single pile. If there are no remaining stones, the next player to move loses.

In Factorisation Nim the initial position of the game is chosen according to the prime factorisation of a given natural number $n$ by setting a pile for each prime factor, including multiplicity. For example, if $n=12=2 \times 2 \times 3$ the game starts with three piles: two piles with two stones and one pile with three stones.

It can be verified that the first player to move loses for $n=1$ and for $n=70$, assuming both players play optimally.

Let $S(N)$ be the sum of $n$ for $1 \le n \le N$ such that the first player to move loses, assuming both players play optimally. You are given $S(10) = 14$ and $S(100) = 455$.

Find $S(10^{14})$. Give your answer modulo $10^9 + 7$.

### 953. 质因数分解尼姆游戏

在经典的 **尼姆取石子游戏** 中，两位玩家轮流从若干堆石子中取走石子。每一轮中，玩家可以取走任意一堆中的任意多个石子，但不能不取。首先无法取石子的玩家落败。

在质因数分解尼姆游戏中，我们预先选择一个自然数 $n$，并将初始盘面下每一堆石子的数量设定为 $n$ 的各个质因数。对于重复的质因数，我们对应设置多堆石子。例如，若 $n = 12 = 2 \times 2 \times 3$，那么我们分别设置含 $2$ 个、$2$ 个、$3$ 个石子的三个石堆，并以此盘面开始尼姆游戏。

可以验证：若两位玩家都以最优方式决策，那么在 $n = 1$、$n = 70$ 时，先手将落败。

记 $S(N)$ 为：若两位玩家都以最优方式决策，所有满足 $1 \le n \le N$ 的正整数中，能使先手落败的 $n$ 的和。已知：$S(10) = 14$、$S(100) = 455$。

求 $S(10^{14})$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。