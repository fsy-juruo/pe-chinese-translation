### [839. Beans in Bowls](https://projecteuler.net/problem=839)

The sequence $S_n$ is defined by $S_0 = 290797$ and $S_n = S_{n - 1}^2 \bmod 50515093$ for $n > 0$.

There are $N$ bowls indexed $0,1,\dots ,N-1$. Initially there are $S_n$ beans in bowl $n$.

At each step, the smallest index $n$ is found such that bowl $n$ has strictly more beans than bowl $n+1$. Then one bean is moved from bowl $n$ to bowl $n+1$.

Let $B(N)$ be the number of steps needed to sort the bowls into non-descending order.
For example, $B(5) = 0$, $B(6) = 14263289$ and $B(100)=3284417556$.

Find $B(10^7)$.

### 839. 碗中豆

定义数列 $\{S_n\}$ 满足以下递推关系：$S_0 = 290797$ 且 $n > 0$ 时有 $S_n = S_{n - 1}^2 \bmod 50515093$。

初始时有 $N$ 个碗，分别标号为 $0, 1, \cdots, N-1$。初始时 $n$ 号碗里有 $S_n$ 粒豆子。

每一步中，我们将找到最小的 $n$，使其满足 $n$ 号碗中的豆子数量严格多于第 $n+1$ 号碗中的豆子数。随后从 $n$ 号碗中移一颗豆子到 $n + 1$ 号碗中。

记 $B(N)$ 为在有 $N$ 个碗的情况下，将碗中的豆子数变为单调不下降序列所需的步数。已知：$B(5) = 0$、$B(6) = 14263289$ 且 $B(100)=3284417556$。

求 $B(10^7)$。