### [827. Pythagorean Triple Occurrence](https://projecteuler.net/problem=827)

Define $Q(n)$ to be the smallest number that occurs in exactly $n$ **Pythagorean triples** $(a,b,c)$ where $a \lt b \lt c$.

For example, $15$ is the smallest number occurring in exactly $5$ Pythagorean triples:
$$
(9,12,\mathbf{15})\quad (8,\mathbf{15},17)\quad (\mathbf{15},20,25)\quad (\mathbf{15},36,39)\quad (\mathbf{15},112,113)
$$
and so $Q(5) = 15$.

You are also given $Q(10)=48$ and $Q(10^3)=8064000$.

Find $\displaystyle \sum_{k=1}^{18} Q(10^k)$. Give your answer modulo $409120391$.

### 827. 在毕达哥拉斯三元组中的出现次数

记 $Q(n)$ 为在所有 **毕达哥拉斯三元组** $(a,b,c)$（其中 $a \lt b \lt c$）中恰好出现 $n$ 次的最小正整数。

如 $15$ 就是最小的，恰好在 $5$ 个毕达哥拉斯三元组中出现的整数。因而 $Q(5) = 15$。

$$
(9,12,\mathbf{15})\quad (8,\mathbf{15},17)\quad (\mathbf{15},20,25)\quad (\mathbf{15},36,39)\quad (\mathbf{15},112,113)
$$

已知：$Q(10)=48$ 且 $Q(10^3)=8064000$。

求 $\displaystyle \sum_{k=1}^{18} Q(10^k)$ 模 $409120391$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。