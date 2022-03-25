### 785. Symmetric Diophantine equation

Consider the following Diophantine equation:
$$15  (x^2 + y^2 + z^2) = 34  (xy + yz + zx)$$
where $x$, $y$ and $z$ are positive integers.

Let $S(N)$ be the sum of all solutions, $(x,y,z)$, of this equation such that, $1 \le x \le y \le z \le N$ and $\gcd(x, y, z) = 1$.

For $N = 10^2$, there are three such solutions - $(1, 7, 16), (8, 9, 39), (11, 21, 72)$. So $S(10^2) = 184$.

Find $S(10^9)$.

### 785. 对称丢番图方程

考虑如下丢番图方程：
$$15  (x^2 + y^2 + z^2) = 34  (xy + yz + zx)$$
其中 $x$，$y$，$z$ 均为正整数。

令 $S(N)$ 为所有满足如上丢番图方程，且有 $1 \le x \le y \le z \le N$，$\gcd(x, y, z) = 1$ 的所有解的 $x+y+z$ 之和。

对于 $N = 10^2$，有三组满足条件的解：$(1, 7, 16), (8, 9, 39), (11, 21, 72)$。故 $S(10^2) = 184$。

求 $S(10^9)$。