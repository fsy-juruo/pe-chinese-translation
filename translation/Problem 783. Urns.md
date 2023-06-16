### [783. Urns](https://projecteuler.net/problem=783)

Given $n$ and $k$ two positive integers we begin with an urn that contains $kn$ white balls. We then proceed through $n$ turns where on each turn $k$ black balls are added to the urn and then $2k$ random balls are removed from the urn.

We let $B_t(n,k)$ be the number of black balls that are removed on turn $t$.

Further define $E(n,k)$ as the expectation of $\displaystyle \sum_{t=1}^n B_t(n,k)^2$.

You are given $E(2,2) = 9.6$

Find $E(10^6,10)$. Round your answer to the nearest whole number.

### 783. 球瓮

我们有一个装有 $nk$ 个白球的球瓮，其中 $n$、$k$ 为两个给定的正整数。接下来，我们进行 $n$ 轮操作。每一轮操作中，我们往瓮中加入 $k$ 个黑球，然后随机从球瓮中拿出 $2k$ 个球。

记 $B_t(n,k)$ 为在第 $t$ 轮操作中被拿出的黑球个数。再记 $E(n, k)$ 为 $\displaystyle \sum_{t=1}^n B_t(n,k)^2$ 的期望值。已知 $E(2,2) = 9.6$。

求 $E(10^6,10)$。将你的答案四舍五入至最近的正整数。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

