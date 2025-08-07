### [955. Finding Triangles](https://projecteuler.net/problem=955)

A sequence $(a_n)_{n \ge 0}$ starts with $a_0 = 3$ and for each $n \ge 0$,

- if $a_n$ is a **triangle number** (A triangle number is a number of the form $m(m + 1)/2$ for some integer $m$), then $a_{n + 1} = a_n + 1$;
- otherwise, $a_{n + 1} = 2a_n - a_{n - 1} + 1$.

The sequence begins:
$$
{\color{red}3}, 4, {\color{red}6}, 7, 9, 12, 16, {\color{red}21}, 22, 24, 27, 31, {\color{red}36}, 37, 39, 42, \dots
$$
where triangle numbers are marked red.

The $10$th triangle number in the sequence is $a_{2964} = 1439056$.  
Find the index $n$ such that $a_n$ is the $70$th triangle number in the sequence.

### 955. 寻找三角形数

我们按如下规则构造序列 $(a_n)_{n \ge 0}$：$a_0 = 3$，且对诸 $n \geq 0$：

- 若 $a_n$ 是一个 **三角形数**（可被写作 $m(m + 1)/2, m \in \mathbb{Z}$ 的数），则 $a_{n + 1} = a_n + 1$。
- 否则，$a_{n + 1} = 2a_n - a_{n - 1} + 1$。

该序列的前 16 项如下，其中三角形数已被标红：

$$
{\color{red}3}, 4, {\color{red}6}, 7, 9, 12, 16, {\color{red}21}, 22, 24, 27, 31, {\color{red}36}, 37, 39, 42, \dots
$$

这个序列中的第 $10$ 个三角形数是 $a_{2964} = 1439056$。  
求这个序列第 $70$ 个三角形数 $a_n$ 的下标 $n$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。