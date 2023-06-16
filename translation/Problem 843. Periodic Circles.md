### [843. Periodic Circles](https://projecteuler.net/problem=843)

This problem involves an iterative procedure that begins with a circle of $n\ge 3$ integers. At each step every number is simultaneously replaced with the absolute difference of its two neighbours.

For any initial values, the procedure eventually becomes periodic.

Let $S(N)$ be the sum of all possible periods for $3\le n \leq N$. For example, $S(6) = 6$, because the possible periods for $3\le n \leq 6$ are $1, 2, 3$. Specifically, $n=3$ and $n=4$ can each have period $1$ only, while $n=5$ can have period $1$ or $3$, and $n=6$ can have period $1$ or $2$.

You are also given $S(30) = 20381$.

Find $S(100)$.

### 843. 周期圆环

在本题中，一开始会有一个含 $n$（$n \geq 3$）个整数的环。接下来的每一步中，环上的每一个数都会变成其相邻两个数之差的绝对值。这一过程不断迭代往复。

可以发现，不论初始时环上有什么数，这个过程终究会是周期性的。

记 $S(N)$ 为：在 $3 \leq n \leq N$ 时，所有可能的周期长度之和。已知：$S(6) = 6$。因为 $n = 3$ 或 $4$ 时周期为 $1$、$n = 5$ 时周期为 $1$ 或 $3$、$n = 6$ 时周期为 $1$ 或 $2$。所有可能的周期为 $1, 2, 3$。已知：$S(30) = 20381$。

求 $S(100)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。