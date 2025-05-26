### [884. Removing Cubes](https://projecteuler.net/problem=884)


Starting from a positive integer $n$, at each step we subtract from $n$ the largest perfect cube not exceeding $n$, until $n$ becomes $0$.  
For example, with $n = 100$ the procedure ends in $4$ steps:
$$
100 \xrightarrow{-4^3} 36 \xrightarrow{-3^3} 9 \xrightarrow{-2^3} 1 \xrightarrow{-1^3} 0.
$$
Let $D(n)$ denote the number of steps of the procedure. Thus $D(100) = 4$.


Let $S(N)$ denote the sum of $D(n)$ for all positive integers $n$ **strictly less** than $N$.  
For example, $S(100) = 512$.

Find $S(10^{17})$.

### 884. 移除立方数

对某正整数 $n$，我们不断将 $n$ 减去不大于它的最大立方数，直至 $n$ 为 $0$ 时停止。我们记 $D(n)$ 为该过程中执行的减法的次数。例如 $n = 100$ 时，一共需要减去 $4$ 个立方数，所以 $D(100) = 4$：

$$
100 \xrightarrow{-4^3} 36 \xrightarrow{-3^3} 9 \xrightarrow{-2^3} 1 \xrightarrow{-1^3} 0.
$$

再记 $S(N)$ 为：对于所有严格小于 $N$ 的 $n$，其 $D(n)$ 之和。已知：$S(100) = 512$。

求 $S(10^{17})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。