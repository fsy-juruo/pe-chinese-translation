### [924. Larger Digit Permutation II](https://projecteuler.net/problem=924)

Let $B(n)$ be the smallest number larger than $n$ that can be formed by rearranging digits of $n$, or $0$ if no such number exists. For example, $B(245) = 254$ and $B(542) = 0$.

Define $a_0 = 0$ and $a_n = a_{n - 1}^2 + 2$ for $n > 0$. Let $\displaystyle U(N) = \sum_{n = 1}^N B(a_n)$. You are given $U(10) \equiv 543870437 \pmod{10^9+7}$.

Find $U(10^{16})$. Give your answer modulo $10^9 + 7$.

### 924. 更大的数位排列数 2

记 $B(n)$ 为：通过重排 $n$ 的数位，可以得到的最小的 $> n$ 的数。如果这样的数不存在，则置 $B(n) = 0$。例如，$B(245) = 254$、$B(542) = 0$。

定义如下递推：$a_0 = 0$，且对诸 $n > 0$ 有 $a_n = a_{n - 1}^2 + 2$ 成立。记 $\displaystyle U(N) = \sum_{n = 1}^N B(a_n)$，已知 $U(10) \equiv 543870437 \pmod{10^9+7}$。

求 $U(10^{16})$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。