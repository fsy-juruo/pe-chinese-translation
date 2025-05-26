### [943. Self Describing Sequences](https://projecteuler.net/problem=943)

Given two unequal positive integers $a$ and $b$, we define a self-describing sequence consisting of alternating runs of $a$s and $b$s. The first element is $a$ and the sequence of run lengths is the original sequence.

For $a=2, b=3$, the sequence is: 
$$
2, 2, 3, 3, 2, 2, 2, 3, 3, 3, 2, 2, 3, 3, 2, 2, 3, 3, 3, 2, 2, 2, 3, 3, 3,...
$$
The sequence begins with **two** $2$s and **two** $3$s, then **three** $2$s and **three** $3$s, so the run lengths $2, 2, 3, 3, ...$ are given by the original sequence.

Let $T(a, b, N)$ be the sum of the first $N$ elements of the sequence. You are given $T(2,3,10) = 25$, $T(4,2,10^4) = 30004$, $T(5,8,10^6) = 6499871$.

Find $\sum T(a, b, 22332223332233)$ for $2 \le a \le 223$, $2 \le b \le 223$ and $a \neq b$. Give your answer modulo $2233222333$.

### 943. 自描述序列

给定两个不等的正整数 $a, b$，我们用这两个正整数，生成惟一一个满足如下要求的自描述序列 $\{c_n\}$：

- $c_1 = a$。
- 按下标顺序排序，该序列的元素依次为：$c_1$ 个 $a$，$c_2$ 个 $b$，$c_3$ 个 $a$，$c_4$ 个 $b$，依次类推。

例如 $a = 2, b = 3$ 时，该序列形如：

$$
2, 2, 3, 3, 2, 2, 2, 3, 3, 3, 2, 2, 3, 3, 2, 2, 3, 3, 3, 2, 2, 2, 3, 3, 3,...
$$

记 $T(a, b, N)$ 为：用 $a, b$ 生成的自描述序列的前 $N$ 个元素之和。已知 $T(2,3,10) = 25$、$T(4,2,10^4) = 30004$、$T(5,8,10^6) = 6499871$。

求所有满足 $2 \le a, b \le 223$ 且 $a \neq b$ 的 $T(a, b, 22332223332233)$ 之和，给出答案模 $2233222333$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。