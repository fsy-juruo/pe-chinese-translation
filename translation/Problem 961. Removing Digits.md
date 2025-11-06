### [961. Removing Digits](https://projecteuler.net/problem=961)

This game starts with a positive integer. Two players take turns to remove a single digit from that integer. After the digit is removed any resulting leading zeros are removed.

For example, removing a digit from $105$ results in either $5$, $10$ or $15$.

The winner is the person who removes the last nonzero digit.

Define $W(N)$ to be how many positive integers less than $N$ for which the first player can guarantee a win given optimal play. You are given $W(100) = 18$ and $W(10^4) = 1656$.

Find $W(10^{18})$.

### 961. 移除数位

现有一个正整数，两位玩家轮流从该整数中移除一个数位并删去因此产生的任何前导零。

例如，从 $105$ 中移除一个数位后，可能得到的结果包括 $5$、$10$ 和 $15$。

移走最后一个非零数位的玩家获胜。

我们记 $W(N)$ 为：若双方都以最优策略操作，所有 $< N$ 的数中，能让先手必胜的数的个数。已知：$W(100) = 18$、$W(10^4) = 1656$。

求 $W(10^{18})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。