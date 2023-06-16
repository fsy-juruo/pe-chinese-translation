### [804. Counting Binary Quadratic Representations](https://projecteuler.net/problem=804)

Let $g(n)$ denote the number of ways a positive integer $n$ can be represented in the form: $$x^2+xy+41y^2$$ where $x$ and $y$ are integers. For example, $g(53)=4$ due to $(x,y) \in \{(-4,1),(-3,-1),(3,1),(4,-1)\}$.

Define $\displaystyle T(N)=\sum_{n=1}^{N}g(n)$. You are given $T(10^3)=474$ and $T(10^6)=492128$

Find $T(10^{16})$.

### 804. 二元二次表示法计数

记 $g(n)$ 为把正整数 $n$ 表示成 $x^2+xy+41y^2$ 的形式，其中 $x$、$y$ 均为整数的方法数。如 $g(53) = 4$，这 4 种表示方法分别为：$(x,y) \in \{(-4,1),(-3,-1),(3,1),(4,-1)\}$。

记 
$$
\displaystyle T(N)=\sum_{n=1}^{N}g(n)
$$
已知 $T(10^3)=474$、$T(10^6)=492128$。

求 $T(10^{16})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
