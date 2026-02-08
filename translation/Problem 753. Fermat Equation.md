### [753. Fermat Equation](https://projecteuler.net/problem=753)

Fermat's Last Theorem states that no three positive integers $a$, $b$, $c$ satisfy the equation 
$$
a^n+b^n=c^n
$$
for any integer value of $n$ greater than 2.

For this problem we are only considering the case $n=3$. For certain values of $p$, it is possible to solve the congruence equation:
$$
a^3+b^3 \equiv c^3 \pmod{p}
$$

For a prime $p$, we define $F(p)$ as the number of integer solutions to this equation for $1 \le a,b,c < p$.

You are given $F(5) = 12$ and $F(7) = 0$.

Find the sum of $F(p)$ over all primes $p$ less than $6\,000\,000$.

### 753. 费马等式

费马大定理指出，对任意大于 $2$ 的正整数 $n$，不存在正整数 $a$、$b$、$c$ 使如下等式成立：

$$
a^n+b^n=c^n
$$

本题中，我们仅考虑 $n = 3$ 的情况。$p$ 取某些特定值时，如下同余式可能有解：

$$
a^3+b^3 \equiv c^3 \pmod{p}
$$

对质数 $p$，我们记 $F(p)$ 为如上同余式中满足 $1 \le a,b,c < p$ 的整数解的组数。已知 $F(5) = 12$、$F(7) = 0$。

求 $F(p)$ 之和，其中 $p$ 取遍所有小于 $6\,000\,000$ 的质数。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。