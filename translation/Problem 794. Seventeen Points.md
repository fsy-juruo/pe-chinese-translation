### [794. Seventeen Points](https://projecteuler.net/problem=794)

This problem uses half open interval notation where $[a,b)$ represents $a \le x < b$.

A real number, $x_1$, is chosen in the interval $[0,1)$.
A second real number, $x_2$, is chosen such that each of $[0,\frac{1}{2})$ and $[\frac{1}{2},1)$ contains exactly one of $(x_1, x_2)$.
Continue such that on the $n$-th step a real number, $x_n$, is chosen so that each of the intervals $[\frac{k-1}{n}, \frac{k}{n})$ for $k \in \{1, ..., n\}$ contains exactly one of $(x_1, x_2, ..., x_n)$.

Define $F(n)$ to be the minimal value of the sum $x_1 + x_2 + ... + x_n$ of a tuple $(x_1, x_2, ..., x_n)$ chosen by such a procedure. For example, $F(4) = 1.5$ obtained with $(x_1, x_2, x_3, x_4) = (0, 0.75, 0.5, 0.25)$.

Surprisingly, no more than $17$ points can be chosen by this procedure. 

Find $F(17)$ and give your answer rounded to 12 decimal places.

### 794. 十七个点

本题中我们用左闭右开区间 $[a,b)$ 表示 $a \le x < b$。

我们先从 $[0,1)$ 中选出一个实数 $x_1$。
随后，我们再选出一个实数 $x_2$，使得区间 $[0,\frac{1}{2})$, $[\frac{1}{2},1)$ 均只含二元组 $(x_1, x_2)$ 中的一个数。
我们不断进行此过程：第 $n$ 步中，我们选出一个实数 $x_n$ 使得：对于任意 $k \in \{1, ..., n\}$，区间 $[\frac{k-1}{n}, \frac{k}{n})$ 都只含 $n$ 元组 $(x_1, x_2, ..., x_n)$ 中的一个数。

$n$ 步后我们得到一个 $n$ 元组 $(x_1, x_2, ..., x_n)$，记 $F(n)$ 为 $x_1 + x_2 + \cdots + x_n$ 的最小值。例如 $F(4) = 1.5$，这可以通过 $(x_1, x_2, x_3, x_4) = (0, 0.75, 0.5, 0.25)$ 取到。

令人惊讶的是，在此过程中，你最多只能取 $17$ 个实数。[^1]

求 $F(17)$，将你的答案四舍五入至小数点后第 12 位。

[^1]: 如果有感兴趣的读者的话，这里描述的问题被称为 Irregularities in the distributions。数学家 E. R. Berlekamp 和 R. L. Graham 曾在 1970 年给出过其[证明](https://www.sciencedirect.com/science/article/pii/0022314X70900156?ref=pdf_download&fr=RR-2&rr=7a4bf2d2d981f95b)。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。