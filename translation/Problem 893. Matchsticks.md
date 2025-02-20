### [893. Matchsticks](https://projecteuler.net/problem=893)

Define $M(n)$ to be the minimum number of matchsticks needed to represent the number $n$.

A number can be represented in digit form or as an expression involving addition and/or multiplication. Also order of operations must be followed, that is multiplication binding tighter than addition. Any other symbols or operations, such as brackets, subtraction, division or exponentiation, are not allowed.

The valid digits and symbols are shown below:
<div style="text-align:center;">
<img src="resources/images/0893_DigitDiagram.jpg?1714876316" alt="0893_DigitDiagram.jpg" height="433" width="668"></div>

For example, $28$ needs $12$ matchsticks to represent it in digit form but representing it as $4\times 7$ would only need $9$ matchsticks and as there is no way using fewer matchsticks $M(28) = 9$.

Define $\displaystyle T(N) = \sum_{n=1}^N M(n)$. You are given $T(100) = 916$.

Find $T(10^6)$.


### 893. 火柴

记 $M(n)$ 为：表示 $n$ 所需要的最少的火柴数。这里，我们认为一个数可以只有如下两种合法的表示方式：(1) 其十进制表示。(2) 只含有加法、乘法的表达式，这表达式在正确的运算顺序下的计算结果为 $n$。诸如减法、除法、幂运算等其他运算，左右括弧等其他符号都是不允许的。

下图是你可以使用的符号合集：

<div style="text-align:center;">
<img src="resources/images/0893_DigitDiagram.jpg?1714876316" alt="0893_DigitDiagram.jpg" height="433" width="668"></div>

例如：用十进制表示表示 $28$ 需要 $12$ 根火柴，但是用表达式 $4 \times 7$ 表示 $28$ 只需要 $9$ 根火柴。可以证明没有更优的表示方法，所以 $M(28) = 9$。

再记 $\displaystyle T(N) = \sum_{n=1}^N M(n)$，已知 $T(100) = 916$。

求 $T(10^6)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。