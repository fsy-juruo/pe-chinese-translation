### [679. Freefarea](https://projecteuler.net/problem=679)

Let $S$ be the set consisting of the four letters $\tt \{‘A’,‘E’,‘F’,‘R’\} $.
For $n \geq 0$, let $S^{*}(n)$ denote the set of words of length $n$ consisting of letters belonging to $S$.
We designate the words $\tt FREE,FARE,AREA,REEF$ as *keywords*.

Let $f(n)$ be the number of words in $S^{*}(n)$ that contains all four keywords exactly once.

This first happens for $n=9$, and indeed there is a unique $9$ lettered word that contain each of the keywords once: $\tt FREEFAREA$
So, $f(9) = 1$.

You are also given that $f(15)=72863$.

Find $f(30)$.

### 679. Freefarea[^1]

记 $S$ 为四元字符集 $\tt \{'A', 'E', 'F', 'R'\} $。
对于正整数 $n \geq 0$，记 $S^{*}(n)$ 为：只包含 $S$ 中的字符且长度为 $n$ 的字符串的集合。我们将 $\tt FREE,FARE,AREA,REEF$ 四个词指定为 *关键词*。

记 $f(n)$ 为：$S^{*}(n)$ 中，恰好包含四个关键词各一次的字符串的个数。

在 $n=9$ 时，出现第一个合法的字符串 $\tt FREEFAREA$。从而 $f(9) = 1$。亦已知 $f(15)=72863$。

求 $f(30)$。

[^1]: 考虑到本题以四个关键词为主体，以及``FREEFAREA`` 中四个关键词的顺序，故本题原定标题为”免费（free）、礁脉（reef）、费用（fare）、面积（area）“。后来在与审稿人讨论后决定不译。

