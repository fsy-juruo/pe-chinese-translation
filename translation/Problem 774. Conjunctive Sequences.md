### [774. Conjunctive Sequences](https://projecteuler.net/problem=774)

Let '$\&$' denote the bitwise AND operation.
For example, $10\, \& \, 12 = 1010_2\, \& \, 1100_2 = 1000_2 = 8$.

We shall call a finite sequence of non-negative integers $(a_1, a_2, \ldots, a_n)$ *conjunctive* if $a_i\, \& \, a_{i+1} \neq 0$ for all $i=1\ldots n-1$.

Define $c(n,b)$ to be the number of conjunctive sequences of length $n$ in which all terms are $\le b$.  
You are given that $c(3,4)=18$, $c(10,6)=2496120$, and $c(100,200) \equiv 268159379 \pmod {998244353}$.

Find $c(123,123456789)$. Give your answer modulo $998244353$.

### 774. 合取数列

记 '$\&$' 为逻辑与。如 $10\, \& \, 12 = 1010_2\, \& \, 1100_2 = 1000_2 = 8$。

若某非负整数数列 $(a_1, a_2, \ldots, a_n)$ 满足，对于所有 $i=1\ldots n-1$ 皆有 $a_i\, \& \, a_{i+1} \neq 0$，则称该数列为 *合取数列*。

记 $c(n, b)$ 为长度为 $n$，所有项均 $\le b$ 的合取数列的数量。已知 $c(3, 4) = 18$、$c(10, 6) = 2496120$、$c(100, 200) \equiv 268159379 \pmod {998244353}$。

求 $c(123, 123456789)$ 模 $998244353$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
