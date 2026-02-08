### [977. Iterated Functions](https://projecteuler.net/problem=977)

For a positive integer $n$, let $F(n)$ denote the number of functions $f$ from the set $S_n=\{1,2,\dots,n\}$ to itself such that $f^{(x)}(y)=f^{(y)}(x)$ for any $x,y$ in $S_n$. Here $f^{(k)}$ denotes the $k$-th iterated composition of $f$, e.g. $f^{(2)}(x)=f(f(x))$.

For example, $F(3)=8$, $F(7)=174$, $F(100)=570271270297640131$.

Find $F(10^6) \bmod (10^9+7)$.

### 977. 迭代函数

对正整数 $n$，我们记 $F(n)$ 为满足如下条件的，从集合 $S_n=\{1,2,\dots,n\}$ 到 $S_n$ 的函数的数量：对诸 $x, y \in S_n$，都有 $f^{(x)}(y)=f^{(y)}(x)$。此处 $f^{(k)}$ 指的是 $f$ 的 $k$ 次迭代，譬如，$f^{(2)}(x)=f(f(x))$。

已知 $F(3)=8$、$F(7)=174$、$F(100)=570271270297640131$。

求 $F(10^6) \bmod (10^9+7)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。