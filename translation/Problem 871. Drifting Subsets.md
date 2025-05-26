### [871. Drifting Subsets](https://projecteuler.net/problem=871)

Let $f$ be a function from a finite set $S$ to itself. A *drifting subset* for $f$ is a subset $A$ of $S$ such that the number of elements in the union $A \cup f(A)$ is equal to twice the number of elements of $A$.  
We write $D(f)$ for the maximal number of elements among all drifting subsets for $f$.

For a positive integer $n$, define $f_n$ as the function from $\{0, 1, \dots, n - 1\}$ to itself sending $x$ to $x^3 + x + 1 \bmod n$.  
You are given $D(f_5) = 1$ and $D(f_{10}) = 3$.

Find $\displaystyle\sum_{i = 1}^{100} D(f_{10^5 + i})$.

### 871. 漂移子集

记 $f$ 为某从有限集合 $S$ 到 $S$ 的一个函数。若 $S$ 的一个子集 $A$ 满足：$A \cup f(A)$ 的元素个数是 $A$ 的元素个数的 $2$ 倍，则称 $A$ 是 $f$ 的一个 *漂移子集*。记 $D(f)$ 为：所有 $f$ 的漂移子集中，元素个数的最大值。

对某正整数 $n$，记 $f_n$ 为 $\{0, 1, \dots, n - 1\}$ 上的函数，满足 $f(x) = (x^3 + x + 1) \bmod n$。 已知：$D(f_5) = 1$、$D(f_{10}) = 3$。

求 $\displaystyle\sum_{i = 1}^{100} D(f_{10^5 + i})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。