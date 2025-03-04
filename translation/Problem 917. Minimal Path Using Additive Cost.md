### [917. Minimal Path Using Additive Cost](https://projecteuler.net/problem=917)

The sequence $s_n$ is defined by $s_1 = 102022661$ and $s_n = s_{n-1}^2 \bmod {998388889}$ for $n > 1$.

Let $a_n = s_{2n - 1}$ and $b_n = s_{2n}$ for $n=1,2,...$

Define an $N \times N$ matrix whose values are $M_{i,j} = a_i + b_j$.

Let $A(N)$ be the minimal path sum from $M_{1,1}$ (top left) to $M_{N,N}$ (bottom right), where each step is either right or down.

You are given $A(1) = 966774091$, $A(2) = 2388327490$ and $A(10) = 13389278727$.

Find $A(10^7)$.

### 917. 费用是两项加和时的最小路径和

我们按如下递推定义数列 $\{s_n\}$：$s_1 = 102022661$，且对诸 $n > 1$，都有 $s_n = s_{n-1}^2 \bmod {998388889}$。

对 $n = 1, 2, \cdots$，记 $a_n = s_{2n - 1}$、$b_n = s_{2n}$。

再定义 $N \times N$ 的矩阵 $M$，其中 $M_{i,j} = a_i + b_j$。

记 $A(N)$ 为：从 $M$ 的左上角 $M_{1, 1}$ 走到右下角 $M_{N,N}$，每一步要么向右走、要么向下走，路径上所有数字和的最小值。已知 $A(1) = 966774091$、$A(2) = 2388327490$、$A(10) = 13389278727$。

求 $A(10^7)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。