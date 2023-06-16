### [834. Add and Divide](https://projecteuler.net/problem=834)

A sequence is created by starting with a positive integer $n$ and incrementing by $(n+m)$ at the $m^{th}$ step.   
If $n=10$, the resulting sequence will be $21,33,46,60,75,91,108,126,\ldots$.

Let $S(n)$ be the set of indices $m$, for which the $m^{th}$ term in the sequence is divisible by $(n+m)$.  
For example, $S(10)=\{5,8,20,35,80\}$.

Define $T(n)$ to be the sum of the indices in $S(n)$. For example, $T(10) = 148$ and $T(10^2)=21828$.

Let $\displaystyle U(N)=\sum_{n=3}^{N}T(n)$. You are given, $U(10^2)=612572$.

Find $U(1234567)$.

### 834. 加上数并能整除

我们通过如下方式构造一个数列：先指定一个正整数 $n$。在第 $m$ 步时将当前的数加上 $(n + m)$ 并把其加入数列。如果 $n = 10$，产生的数列就是 $21,33,46,60,75,91,108,126,\ldots$。

记 $S(n)$ 为下标 $m$ 的集合，其中所有的下标 $m$ 都满足：这个数列的第 $m$ 项能被 $(n + m)$ 整除。如 $S(10)=\{5,8,20,35,80\}$。

记 $T(n)$ 为 $S(n)$ 中所有元素之和。已知：$T(10) = 148$ 且 $T(10^2)=21828$。

记 $\displaystyle U(N)=\sum_{n=3}^{N}T(n)$，已知：$U(10^2)=612572$。

求 $U(1234567)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。