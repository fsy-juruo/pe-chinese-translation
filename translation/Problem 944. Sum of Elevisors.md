### [944. Sum of Elevisors](https://projecteuler.net/problem=944)

Given a set $E$ of positive integers, an element $x$ of $E$ is called an *element divisor (elevisor)* of $E$ if $x$ divides **another** element of $E$.

The sum of all elevisors of $E$ is denoted $\operatorname{sev}(E)$.  
For example, $\operatorname{sev}(\{1, 2, 5, 6\}) = 1 + 2 = 3$.

Let $S(n)$ be the sum of $\operatorname{sev}(E)$ for all subsets $E$ of $\{1, 2, \dots, n\}$.  
You are given $S(10) = 4927$.

Find $S(10^{14}) \bmod 1234567891$.

### 944. 基本因数之和

对某个只含正整数的集合 $E$，若 $E$ 中的一个元素 $x$ 能够整除 $E$ 中不同于 $x$ 的一个元素，则称 $x$ 是 $E$ 的一个 *基本因数*。

我们记 $\operatorname{sev}(E)$ 为 $E$ 中全体基本因数的和。例如，$\operatorname{sev}(\{1, 2, 5, 6\}) = 1 + 2 = 3$。

记 $S(n)$ 为全体 $\{1, 2, \cdots, n\}$ 的子集的 $\operatorname{sev}$ 之和，已知 $S(10) = 4927$。

求 $S(10^{14}) \bmod 1234567891$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。


