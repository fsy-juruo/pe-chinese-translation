### [833. Square Triangle Products](https://projecteuler.net/problem=833)

Triangle numbers $T_k$ are integers of the form $\frac{k(k+1)} 2$.

A few triangle numbers happen to be perfect squares like $T_1=1$ and $T_8=36$, but more can be found when considering the product of two triangle numbers. For example, $T_2 \cdot T_{24}=3 \cdot 300=30^2$.

Let $S(n)$ be the sum of $c$ for all integers triples $(a, b, c)$ with $0 <c \le n$, $c^2=T_a \cdot T_b$ and $0 < a < b$.For example, $S(100)= \sqrt{T_1 T_8}+\sqrt{T_2 T_{24}}+\sqrt{T_1 T_{49}}+\sqrt{T_3 T_{48}}=6+30+35+84=155$.

You are given $S(10^5)=1479802$ and $S(10^9)=241614948794$.

Find $S(10^{35})$. Give your answer modulo $136101521$.

### 833. 三角形数乘积中的平方

三角形数 $T_k$ 是形如 $\frac{k(k+1)} 2$ 的整数。

某些三角形数恰好是平方数，如 $T_1=1$ 和 $T_8=36$。如果考虑某两个三角形数的乘积的话，可能的平方数就更多了。如 $T_2 \cdot T_{24}=3 \cdot 300=30^2$。

记 $S(n)$ 为所有满足如下条件的整数三元组 $(a, b, c)$ 中，$c$ 的和：$0 <c \le n$，$0 < a < b$，$c^2=T_a \cdot T_b$。已知：$S(100)= \sqrt{T_1 T_8}+\sqrt{T_2 T_{24}}+\sqrt{T_1 T_{49}}+\sqrt{T_3 T_{48}}=6+30+35+84=155$。亦有：$S(10^5)=1479802$ 且 $S(10^9)=241614948794$。

求 $S(10^{35})$ 模 $136101521$。