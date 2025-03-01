### [925. Larger Digit Permutation III](https://projecteuler.net/problem=925)

Let $B(n)$ be the smallest number larger than $n$ that can be formed by rearranging digits of $n$, or $0$ if no such number exists. For example, $B(245) = 254$ and $B(542) = 0$.

Define $\displaystyle T(N) = \sum_{n=1}^N B(n^2)$. You are given $T(10)=270$ and $T(100)=335316$.

Find $T(10^{16})$. Give your answer modulo $10^9 + 7$.

### 925. 更大的数位排列数 3

记 $B(n)$ 为：通过重排 $n$ 的数位，可以得到的最小的 $> n$ 的数。如果这样的数不存在，则置 $B(n) = 0$。例如，$B(245) = 254$、$B(542) = 0$。

记 $\displaystyle T(N) = \sum_{n=1}^N B(n^2)$，已知 $T(10)=270$、$T(100)=335316$。

求 $T(10^{16})$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。