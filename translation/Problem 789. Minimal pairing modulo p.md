### [789. Minimal pairing modulo $p$](https://projecteuler.net/problem=789)

Given an odd prime $p$, put the numbers $1,...,p-1$ into $\frac{p-1}{2}$ pairs such that each number appears exactly once. Each pair $(a,b)$ has a cost of $ab \bmod p$. For example, if $p=5$ the pair $(3,4)$ has a cost of $12 \bmod 5 = 2$.

The *total cost* of a pairing is the sum of the costs of its pairs. We say that such pairing is optimal if its total cost is minimal for that $p$.

For example, if $p = 5$, then there is a unique optimal pairing: $(1, 2), (3, 4)$, with total cost of $2 + 2 = 4$.

The *cost product* of a pairing is the product of the costs of its pairs. For example, the cost product of the optimal pairing for $p = 5$ is $2 \cdot 2 = 4$.

It turns out that all optimal pairings for $p = 2\,000\,000\,011$ have the same cost product.

Find the value of this product.

### 789. 模 $p$ 的最小花费配对方案

现给定一奇质数 $p$，我们将 $1,...,p-1$ 这些数分成 $\frac{p-1}{2}$ 个数对，每个数恰好出现一次。每个数对 $(a,b)$ 有费用 $ab \bmod p$。例如 $p=5$ 时，数对 $(3,4)$ 的费用即为 $12 \bmod 5 = 2$。

我们称一个配对方案的*总花费*为其所有数对的费用之和。如果对于某个 $p$，有一个配对方案，使得它的总花费在所有配对方案中最小，则我们称这个配对方案在模 $p$ 意义下是最优的。

例如 $p = 5$ 时，只有唯一一个最优配对方案：$(1, 2), (3, 4)$，其总花费为 $2 + 2 = 4$。

我们再令一个配对方案的*花费积*为其所有数对的费用之积。比如说，模 $5$ 意义下最优配对方案的花费积为 $2 \cdot 2 = 4$。

可以证明，若 $p = 2\,000\,000\,011$，则所有模 $p$ 意义下的最优配对方案的花费积均是相同的。

试求这个花费积。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。