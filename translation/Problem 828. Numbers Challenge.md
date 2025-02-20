### [828. Numbers Challenge](https://projecteuler.net/problem=828)

It is a common recreational problem to make a target number using a selection of other numbers. In this problem you will be given six numbers and a target number.

For example, given the six numbers $2$, $3$, $4$, $6$, $7$, $25$, and a target of $211$, one possible solution is:

$$
211 = (3+6)\times 25 − (4\times7)\div 2
$$

This uses all six numbers. However, it is not necessary to do so. Another solution that does not use the $7$ is:

$$
211 = (25−2)\times (6+3) + 4
$$

Define the *score* of a solution to be the sum of the numbers used. In the above example problem, the two given solutions have scores $47$ and $40$ respectively. It turns out that this problem has no solutions with score less than $40$.

When combining numbers, the following rules must be observed:

* Each available number may be used at most once.
* Only the four basic arithmetic operations are permitted: $+$, $-$, $\times$, $\div$.
* All intermediate values must be positive integers, so for example $(3\div 2)$ is never permitted as a subexpression (even if the final answer is an integer).

The attached file [number-challenges.txt](https://pe.xiaoyaowudi.com/project/resources/p828_number_challenges.txt) contains 200 problems, one per line in the format:

<center><big><tt>211:2,3,4,6,7,25</tt></big></center>

where the number before the colon is the target and the remaining comma-separated numbers are those available to be used.

Numbering the problems 1, 2, ..., 200, we let $s_n$ be the minimum score of the solution to the $n$th problem. For example, $s_1=40$, as the first problem in the file is the example given above. Note that not all problems have a solution; in such cases we take $s_n=0$.

Find $\displaystyle\sum_{n=1}^{200} 3^n s_n$. Give your answer modulo $1005075251$.

### 828. 数字挑战

通过某些数字，对其进行运算，来得到目标数字，是数学圈常见的一种消遣。本题中，你需要用六个数字通过运算得到目标数字。

例如，给定六个数字 $2,3,4,6,7,25$，目标数字为 $211$ 时，一种可能的解法如下：

$$
211 = (3+6)\times 25 − (4\times7)\div 2
$$

这个解法用上了所有的六个数。但这其实没有必要，下面的这个解法就没有使用 $7$：

$$
211 = (25−2)\times (6+3) + 4
$$

定义一个解法的*分数*为所有使用的数字之和。以上两个解法的分数分别为 $47$ 和 $40$。可以发现，在本题中，没有解法的分数会低于 $40$。

在用运算组合数字的时候，必须遵守以下规则：

* 每个给定的数字至多使用一次。
* 只能对数字进行四则运算。
* 所有中间量都必须是整数。所以 $(3\div 2)$ 不可以作为解法的一部分，即使答案是整数也不可以。

下发文件 [number-challenges.txt](https://pe.xiaoyaowudi.com/project/resources/p828_number_challenges.txt) 包括 200 道题目，每道题的格式如下：

<center><big><tt>211:2,3,4,6,7,25</tt></big></center>

冒号前的数字是目标数字，而后面六个用逗号隔开的数字就是给定的数字了。

将所有题目编号为 $1, 2, \cdots, 200$。记 $s_n$ 为第 $n$ 题所有解法的最小得分。如上所述，$s_1=40$。注意，不是所有题目都有解。若有题目无解，则置 $s_n=0$。

求 $\displaystyle\sum_{n=1}^{200} 3^n s_n$ 模 $1005075251$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。