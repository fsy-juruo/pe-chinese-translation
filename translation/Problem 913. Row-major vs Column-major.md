### [913. Row-major vs Column-major](https://projecteuler.net/problem=913)

The numbers from $1$ to $12$ can be arranged into a $3 \times 4$ matrix in either **row-major** or **column-major** order:

$$
R=\begin{pmatrix}
1 & 2 & 3 & 4\\
5 & 6 & 7 & 8\\
9 & 10 & 11 & 12\end{pmatrix}, C=\begin{pmatrix}
1 & 4 & 7 & 10\\
2 & 5 & 8 & 11\\
3 & 6 & 9 & 12\end{pmatrix}
$$

By swapping two entries at a time, at least $8$ swaps are needed to transform $R$ to $C$.

Let $S(n, m)$ be the minimal number of swaps needed to transform an $n\times m$ matrix of $1$ to $nm$ from row-major order to column-major order. Thus $S(3, 4) = 8$.

You are given that the sum of $S(n, m)$ for $2 \leq n \leq m \leq 100$ is $12578833$.

Find the sum of $S(n^4, m^4)$ for $2 \leq n \leq m \leq 100$.

### 913. 优先填行或填列

$1$ 至 $12$ 间的整数可以通过 **优先填行** 的顺序排成 $3 \times 4$ 的矩阵 $R$，或通过 **优先填列** 的顺序排成 $3 \times 4$ 的矩阵 $C$：

$$
R=\begin{pmatrix}
1 & 2 & 3 & 4\\
5 & 6 & 7 & 8\\
9 & 10 & 11 & 12\end{pmatrix}, C=\begin{pmatrix}
1 & 4 & 7 & 10\\
2 & 5 & 8 & 11\\
3 & 6 & 9 & 12\end{pmatrix}
$$

若允许同时交换某矩阵中的两个元素，那么至少需要 $8$ 次交换才能将 $R$ 转换为 $C$。

记 $S(n, m)$ 为：将 $1$ 至 $nm$ 间的整数通过优先填行、优先填列的顺序排成的 $n \times m$ 的矩阵分别记为 $R'$、$C'$，把 $R'$ 转换为 $C'$ 最少需要交换元素的次数。因而 $S(3, 4) = 8$。

你已知：对所有 $2 \leq n \leq m \leq 100$，$S(n, m)$ 的和是 $12578833$。

求：对所有 $2 \leq n \leq m \leq 100$，$S(n^4, m^4)$ 的和。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。


