>:warning: **剧透警告！**
>
>下文包括了大部分 Project Euler 的奖励题目，提前阅读下文内容可能会降低您在探索奖励题目时的兴趣。

> :question: **需要更多信息**
>
> 笔者目前仍未解锁任何奖励题目，下文中的所有内容均来自 [NaCly\_Fish：Project Euler 隐藏题目列表 - 洛谷专栏](https://www.luogu.com/article/cc9clyi1) 和 [IVL - Project Euler Solutions - Bonus Problems](https://www.ivl-projecteuler.com/overview-of-problems/bonus-problems)。
>
> 目前，仍有一道奖励题目未知。欢迎读者提供相关信息。

下文展示了 Project Euler 的部分奖励题目 (Bonus Problems)，读者可以在 Progress > Bonus 中查看自己是否解锁这些题目。如果您没有解锁相关题目，那么点击下文中的题目链接不会有任何作用。



### [Problem: -1](https://projecteuler.net/problem=-1)

> If we list all the natural numbers below $10$ that are multiples of $3$ or $5$, we get $3, 5, 6$ and $9$. The sum of these multiples is $23$.
>
> Find the sum of all the multiples of $3$ or $5$ below infinity.

$\leq 10$ 的自然数中，$3, 5, 6, 9$ 这四个数或是 $3$ 的倍数，或是 $5$ 的倍数。这些数的和是 $23$。

求全体或是 $3$ 的倍数，或是 $5$ 的倍数的自然数之和。



### [Problem: Heegner](https://projecteuler.net/problem=heegner)

> Among all non-square integers $n$ with absolute value not exceeding $10^3$, find the value of $n$ such that $\cos(\pi \sqrt{n})$ is closest to an integer.

在全体绝对值 $\leq 10^3$ 的非完全平方数中，使得 $\cos(\pi \sqrt{n})$ 最接近整数的 $n$ 是哪一个？



### [Problem: $\sqrt{13}$ (root13)](https://projecteuler.net/problem=root13)

> The decimal expansion of the square root of two is $1.\underline{4142135623}730\cdots$。
>
> If we define $S(n, d)$ to be the sum of the first $d$ digits in the fractional part of the decimal expansion of $\sqrt{n}$, it can be seen that $S(2, 10) = 4 + 1 + 4 + \cdots + 3 = 31$.
>
> It can be confirmed that $S(2, 100) = 481$.
>
> Find $S(13, 1000)$.
>
> **Note:** Instead of just using arbitrary precision floats, try to be creative with your method.

$\sqrt{2}$ 的十进制表示是 $1.\underline{4142135623}730 \cdots$。

若记 $S(n, d)$ 为：$\sqrt{n}$ 的十进制表示中，小数点后第 1 位至第 $d$ 位的数码之和，则有 $S(2, 10) = 31$，亦可验证 $S(2, 100) =481$。

求 $S(13, 1000)$ 的值。

**注：** 你大可以使用任意精度浮点数得到答案，不过尝试在求解方法上做点创新吧！



### [Problem: 18i](https://projecteuler.net/problem=18i)

> Let $R(p)$ be the remainder when he **product** $\prod_{x=0}^{p-1} (x^3 - 3x + 4)$ is divided by $p$. For example, $R(11) = 0$ and $R(29) = 13$.
>
> Find the sum of $R(p)$ over all primes $p$ between $1 \ 000 \ 000 \ 000$ and $1 \ 100 \ 000 \ 000$.

记 $R(p)$ 为 $\prod_{x=0}^{p-1} (x^3 - 3x + 4)$ 模 $p$ 的值，例如 $R(11) =  0$、$R(29) = 13$。

求 $\sum_p R(p)$，其中 $p$ 取遍  $[1 \ 000 \ 000 \ 000, 1 \ 100 \ 000 \ 000]$ 的全体质数。
