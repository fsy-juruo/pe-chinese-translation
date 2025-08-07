### [876. Triplet Tricks](https://projecteuler.net/problem=876)


Starting with three numbers $a, b, c$, at each step do one of the three operations:

- change $a$ to $2(b + c) - a$;
- change $b$ to $2(c + a) - b$;
- change $c$ to $2(a + b) - c$;

Define $f(a, b, c)$ to be the minimum number of steps required for one number to become zero. If this is not possible then $f(a, b, c)=0$.

For example, $f(6,10,35)=3$:
$$
(6,10,35) \to (6,10,-3) \to (8,10,-3) \to (8,0,-3).
$$
However, $f(6,10,36)=0$ as no series of operations leads to a zero number.

Also define $F(a, b)=\sum_{c=1}^\infty f(a,b,c)$.
You are given $F(6,10)=17$ and $F(36,100)=179$.

Find $\displaystyle\sum_{k=1}^{18}F(6^k,10^k)$.

### 876. 三元组技巧

现有三个数 $a, b, c$。在接下来的每一步中，你可以进行如下三个操作之一：

- 令 $a \gets 2(b + c) - a$。 
- 令 $b \gets 2(c + a) - b$。
- 令 $c \gets 2(a + b) - c$。

记 $f(a, b, c)$ 为：使其中一个数变为 $0$ 所需的最少步数，若不可能则令 $f(a, b, c)=0$。

例如，$f(6,10,35)=3$，可能的三步操作如下：
$$
(6,10,35) \to (6,10,-3) \to (8,10,-3) \to (8,0,-3).
$$
然而，$f(6,10,36)=0$，因为你无法通过上述操作使得任何数为 $0$。

另外记 $F(a, b)=\sum_{c=1}^\infty f(a,b,c)$，已知 $F(6,10)=17$、$F(36,100)=179$。

求 $\displaystyle\sum_{k=1}^{18}F(6^k,10^k)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

