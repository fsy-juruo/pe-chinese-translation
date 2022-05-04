### [679. Freefarea](https://projecteuler.net/problem=679)

Let $S$ be the set consisting of the four letters $\tt \{‘A’,‘E’,‘F’,‘R’\} $.
For $n \geq 0$, let $S^{*}(n)$ denote the set of words of length $n$ consisting of letters belonging to $S$.
We designate the words $\tt FREE,FARE,AREA,REEF$ as *keywords*.

Let $f(n)$ be the number of words in $S^{*}(n)$ that contains all four keywords exactly once.

This first happens for $n=9$, and indeed there is a unique $9$ lettered word that contain each of the keywords once: $\tt FREEFAREA$
So, $f(9) = 1$.

You are also given that $f(15)=72863$.

Find $f(30)$.



### 679. Freefarea

令 $S$ 为一个包含 $\tt \{‘A’,‘E’,‘F’,‘R’\} $ 四个字母的集合。
对于 $n \geq 0$，令 $S^{*}(n)$ 为只包含了 $S$ 中的字符，且长度为 $n$ 的字符串集合。我们将 $\tt FREE,FARE,AREA,REEF$ 四个词指定为 *关键词*。

令 $f(n)$ 为 $S^{*}(n)$ 中，恰好包含四个关键词各一次的字符串的个数。

在 $n=9$ 时，出现第一个合法的字符串 $\tt FREEFAREA$。故 $f(9) = 1$。

已知 $f(15)=72863$。

求 $f(30)$。
