### [801. $x^y\equiv y^x$](https://pe.xiaoyaowudi.com/problem=801)

The positive integral solutions of the equation $x^y=y^x$ are $(2,4)$, $(4,2)$ and $(k,k)$ for all $k > 0$.

For a given positive integer $n$, let $f(n)$ be the number of integral values $0 < x,y \leq n^2-n$ such that
$$x^y\equiv y^x \pmod n$$
For example, $f(5)=104$ and $f(97)=1614336$.

Let $S(M,N)=\sum f(p)$ where the sum is taken over all primes $p$ satisfying $M\le p\le N$.

You are given $S(1,10^2)=7381000$ and $S(1,10^5) \equiv 701331986 \pmod{993353399}$.

Find $S(10^{16}, 10^{16}+10^6)$. Give your answer modulo $993353399$.

### 801. $x^y\equiv y^x$

方程 $x^y=y^x$ 的所有正整数解为 $(2,4)$, $(4,2)$ 与 $(k,k)$，其中 $k$ 是任意正整数。

给定正整数 $n$，记 $f(n)$ 为满足 $0 < x, y \leq n^2 - n$ 且 $x^y\equiv y^x \pmod n$ 的正整数对的数量。如 $f(5)=104$, $f(97)=1614336$。

记 $S(M,N)=\sum f(p)$，其中 $p$ 取遍 $[M,N]$ 中所有质数。

你已知 $S(1,10^2)=7381000$, $S(1,10^5) \equiv 701331986 \pmod{993353399}$。

求 $S(10^{16}, 10^{16}+10^6)$ 模 $993353399$ 之值。