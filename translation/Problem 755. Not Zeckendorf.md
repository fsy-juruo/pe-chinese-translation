### [755. Not Zeckendorf](https://projecteuler.net/problem=755)

Consider the Fibonacci sequence $\{1,2,3,5,8,13,21,\ldots\}$.

We let $f(n)$ be the number of ways of representing an integer $n\ge 0$ as the sum of different Fibonacci numbers.  
For example, $16 = 3+13 = 1+2+13 = 3+5+8 = 1+2+5+8$ and hence $f(16) = 4$. 
By convention $f(0) = 1$.

Further we define
$$
S(n) = \sum_{k=0}^n f(k).
$$
You are given $S(100) = 415$ and $S(10^4) = 312807$.

Find $\displaystyle S(10^{13})$.

### 755. 不是齐肯多夫表示 [^1]

[^1]: 数学家 Edouard Zeckendorf 证明了：每个正整数都可以被表示成若干不相邻的 Fibonacci 数之和，且该表示方法惟一。这种表示法被称为 Zeckendorf 表示法。本题中没有不相邻的限制，自然不是 Zeckendorf 表示法。

考虑斐波那契数列 $\{1,2,3,5,8,13,21,\ldots\}$。

记 $f(n)$ 为：将整数 $n \geq 0$ 写为不同的斐波那契数的和的方法数。  
例如，有 $16 = 3+13 = 1+2+13 = 3+5+8 = 1+2+5+8$，于是有 $f(16) = 4$。按惯例，我们令 $f(0) = 1$。

进一步定义
$$
S(n) = \sum_{k=0}^n f(k).
$$
你已知 $S(100) = 415$、$S(10^4) = 312807$。

求 $\displaystyle S(10^{13})$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
