### [791. Average and Variance](https://projecteuler.net/problem=791)

Denote the average of $k$ numbers $x_1, ..., x_k$ by $\bar{x} = \frac{1}{k} \sum_i x_i$. Their variance is defined as $\frac{1}{k} \sum_i \left( x_i - \bar{x} \right) ^ 2$.

Let $S(n)$ be the sum of all quadruples of integers $(a,b,c,d)$ satisfying $1 \leq a \leq b \leq c \leq d \leq n$ such that their average is exactly twice their variance.

For $n=5$, there are $5$ such quadruples, namely: $(1, 1, 1, 3), (1, 1, 3, 3), (1, 2, 3, 4), (1, 3, 4, 4), (2, 2, 3, 5)$.

Hence $S(5)=48$. You are also given $S(10^3)=37048340$.

Find $S(10^8)$. Give your answer modulo $433494437$.

### 791. 平均数与方差

对于 $k$ 个数 $x_1, ..., x_k$，记其平均数 $\bar{x} = \frac{1}{k} \sum_i x_i$，方差为 $\frac{1}{k} \sum_i \left( x_i - \bar{x} \right) ^ 2$。

记 $S(n)$ 为所有满足 $1 \leq a \leq b \leq c \leq d \leq n$，且其平均数等于两倍的方差的整数四元组 $(a,b,c,d)$ 的 $a + b + c + d$ 之和。

$n = 5$ 时，共有 $5$ 个符合要求的四元组。分别是：$(1, 1, 1, 3), (1, 1, 3, 3), (1, 2, 3, 4), (1, 3, 4, 4), (2, 2, 3, 5)$，故 $S(5)=48$。又已知 $S(10^3)=37048340$。

求 $S(10^8)$ 模 $433494437$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。