### [887. Bounded Binary Search](https://projecteuler.net/problem=887)

Consider the problem of determining a secret number from a set $\{1, ..., N\}$ by repeatedly choosing a number $y$ and asking "Is the secret number greater than $y$?".

If $N=1$ then no questions need to be asked. If $N=2$ then only one question needs to be asked. If $N=64$ then six questions need to be asked. However, in the latter case if the secret number is $1$ then six questions still need to be asked. We want to restrict the number of questions asked for small values.

Let $Q(N, d)$ be the least number of questions needed for a strategy that can find any secret number from the set $\{1, ..., N\}$ where no more than $x + d$ questions are needed to find the secret value $x$.

It can be proved that $Q(N, 0) = N - 1$. You are also given $Q(7, 1) = 3$ and $Q(777, 2) = 10$.

Find $\displaystyle \sum_{d=0}^7 \sum_{N=1}^{7^{10}} Q(N, d)$.

### 887. 有界二分查找

考虑如下游戏：你现在需要猜一个在 $\{1, ..., N\}$ 内的神秘数字，你可以不断选一个数 $y$ 并询问「神秘数字 $\geq y$ 吗？」，直至确定神秘数字。

如果 $N = 1$，那么无须提问就能确定神秘数字。如果 $N = 2$，那么只需提问 $1$ 次。如果 $N = 64$，那么则需提问 $6$ 次。但是 $N = 64$ 时，若神秘数字是 $1$，我们仍需要 $6$ 次提问才能确认神秘数字。在本题中，在神秘数字较小时，我们希望对提问次数进行限制。

考虑能够满足如下条件的策略：若 $\{1, ..., N\}$ 内的神秘数字是 $x$，那么该策略可以在 $x + d$ 次提问内确定该数。记 $Q(N, d)$ 为：所有能够满足上述条件的策略中，最坏情况下的提问次数的最小值。

可以证明 $Q(N, 0) = N - 1$，亦已知 $Q(7, 1) = 3$、$Q(777, 2) = 10$。

求 $\displaystyle \sum_{d=0}^7 \sum_{N=1}^{7^{10}} Q(N, d)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

