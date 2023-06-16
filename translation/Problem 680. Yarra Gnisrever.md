### [680. Yarra Gnisrever](https://projecteuler.net/problem=680)

Let $N$ and $K$ be two positive integers.

$F_n$ is the $n$-th Fibonacci number: $F_1 = F_2 = 1$, $F_n = F_{n - 1} + F_{n - 2}$ for all $n \geq 3$.
Let $s_n = F_{2n - 1} \mod N$ and let $t_n = F_{2n} \mod N$.

Start with an array of integers $A = (A[0], \cdots, A[N - 1])$ where initially every $A\text{[}i]$ is equal to $i$.
Now perform $K$ successive operations on $A$, where the $j$-th operation consists of reversing the order of those elements in $A$ with indices between $s_j$ and $t_j$ (both ends inclusive).

Define $R(N,K)$ to be $\sum_{i = 0}^{N - 1}i \times A\text {[}i]$ after $K$ operations.

For example, $R(5, 4) = 27$, as can be seen from the following procedure:
Initial position: $(0, 1, 2, 3, 4)$

Step 1 - Reverse $A[1]$ to $A[1]$: $(0, 1, 2, 3, 4)$
Step 2 - Reverse $A[2]$ to $A[3]$: $(0, 1, 3, 2, 4)$
Step 3 - Reverse $A[0]$ to $A[3]$: $(2, 3, 1, 0, 4)$
Step 4 - Reverse $A[3]$ to $A[1]$: $(2, 0, 1, 3, 4)$

$R(5, 4) = 0 \times 2 + 1 \times 0 + 2 \times 1 + 3 \times 3 + 4 \times 4 = 27$

Also, $R(10^2, 10^2) = 246597$ and $R(10^4, 10^4) = 249275481640$.
Find $R(10^{18}, 10^6)$ giving your answer modulo $10^9$.

### 680. 组数转翻[^1]

$N$、$K$ 是两个正整数。

$F_n$ 是第 $n$ 个斐波那契数，其中 $F_1 = F_2 = 1$，且对于正整数 $n \geq 3$，$F_n = F_{n - 1} + F_{n - 2}$。再记 $s_n = F_{2n - 1} \mod N$、$t_n = F_{2n} \mod N$。

我们给定一个正整数数组 $A = (A[0], \cdots, A[N - 1])$。初始时每个 $A\text{[}i]$ 均等于 $i$。
现在我们接连对数组 $A$ 进行 $K$ 次操作。对于第 $j$ 次操作，你需要将 $A$ 中的 $[s_j, t_j]$ 这段区间翻转。 

然后，记 $R(N,K)$ 为经过 $K$ 次操作后， $\sum_{i = 0}^{N - 1}i \times A\text {[}i]$ 的值。

例如 $R(5, 4) = 27$，计算它的过程如下：

- 初始数组：$(0, 1, 2, 3, 4)$
- 第一步 - 翻转 $[1,1]$：$(0, 1, 2, 3, 4)$
- 第二步 - 翻转 $[2,3]$：$(0, 1, 3, 2, 4)$
- 第三步 - 翻转 $[0,3]$：$(2, 3, 1, 0, 4)$
- 第四步 - 翻转 $[3,1]$：$(2, 0, 1, 3, 4)$[^2]

故 $R(5, 4) = 0 \times 2 + 1 \times 0 + 2 \times 1 + 3 \times 3 + 4 \times 4 = 27$。

亦已知 $R(10^2, 10^2) = 246597$ 且 $R(10^4, 10^4) = 249275481640$。
求 $R(10^{18}, 10^6)$ 模 $10^9$ 之值。

[^1]: 分别翻转 yarra 和 gnisrever 后得到 array reversing（数组翻转）。又因为两个词被分别翻转，故将数组、翻转两词分别翻转，译作“组数转翻”。

[^2]: 虽然没有说明，但读者应该也能发现这里是翻转了区间 $[1,3]$。翻译保留原状的原因是 $s_j$、$t_j$ 顺序固定。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。