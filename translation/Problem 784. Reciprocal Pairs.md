### [784. Reciprocal Pairs](https://projecteuler.net/problem=784)

Let's call a pair of positive integers $p$, $q$ ($p \lt q$) *reciprocal*, if there is a positive integer $r\lt p$ such that $r$ equals both the inverse of $p$ modulo $q$ and the inverse of $q$ modulo $p$.

For example, $(3,5)$ is one reciprocal pair for $r=2$.
Let $F(N)$ be the total sum of $p+q$ for all reciprocal pairs $(p,q)$ where $p \le N$.

$F(5)=59$ due to these four reciprocal pairs $(3,5)$, $(4,11)$, $(5,7)$ and $(5,19)$.
You are also given $F(10^2) = 697317$.

Find $F(2\cdot 10^6)$.

### 784. 互反数对

我们称数对 $(p, q) (p \lt q$) 为*互反数对*，当且仅当存在一个正整数 $r < p$，使得 $r$ 既为模 $q$ 意义下 $p$ 的乘法逆，也为模 $p$ 意义下 $q$ 的乘法逆。例如 $(3,5)$ 是一对互反数对，令 $r=2$ 即可。

记 $F(N)$ 为所有满足 $p \le N$ 的互反数对 $(p,q)$ 的 $p+q$ 之和。例如 $F(5)=59$，因为共有 $(3,5)$、$(4,11)$、$(5,7)$ 和 $(5,19)$ 四个满足条件的互反数对。已知：$F(10^2) = 697317$。

求 $F(2\cdot 10^6)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。