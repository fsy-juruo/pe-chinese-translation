### 678. Fermat-like Equations

If a triple of positive integers $(a, b, c)$ satisfies $a^2+b^2=c^2$, it is called a Pythagorean triple. No triple $(a, b, c)$ satisfies $a^e + b^e = c^e$ when $e \geq 3$  (Fermat's Last Theorem). However, if the exponents of the left-hand side and right-hand side differ, this is not true. For example, $3^3 + 6^3 = 3^5$.

Let $a, b, c, e, f$ be all positive integers, $0 < a < b$, $e \geq 2$, $f \geq 3$ and $c^f \leq N$. Let $F(N)$ be the number of $(a, b, c, e, f)$ such that $a^e + b^e = c^f$. You are given  $F(10^3) = 7$, $F(10^5) = 53$, and $F(10^7) = 287$.

Find $F(10^{18})$. 


### 678. 费马式方程

如果一个正整数三元组 $(a, b, c)$ 满足 $a^2+b^2=c^2$，那它就是一个毕达哥拉斯三元组。 

对于 $e \geq 3$，费马大定理指出，没有任何正整数三元组 $(a, b, c)$ 满足 $a^e + b^e = c^e$。但是，如果方程左边的指数与右边不一样，费马大定理就不一定成立了。比如说，$3^3 + 6^3 = 3^5$。

令 $a,b,c,e,f$ 全部为正整数，且满足 $0 < a < b$, $e \geq 2$, $f \geq 3$ 和 $c^f \leq N$. 令 $F(N)$ 为满足方程 $a^e + b^e = c^f$ 的正整数五元组个数 $(a, b, c, e, f)$。你已经知道 $F(10^3) = 7$，$F(10^5) = 53$，且 $F(10^7) = 287$。

求 $F(10^{18})$。
