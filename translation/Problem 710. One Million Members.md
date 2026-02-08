### [710. One Million Members](https://projecteuler.net/problem=710)

**On Sunday 5 April 2020 the Project Euler membership first exceeded one million members. We would like to present this problem to celebrate that milestone. Thank you to everyone for being a part of Project Euler.**

The number 6 can be written as a palindromic sum in exactly eight different ways:
$$
(1, 1, 1, 1, 1, 1), (1, 1, 2, 1, 1), (1, 2, 2, 1), (1, 4, 1), (2, 1, 1, 2), (2, 2, 2), (3, 3), (6)
$$

We shall define a *twopal* to be a palindromic tuple having at least one element with a value of 2. It should also be noted that elements are not restricted to single digits. For example, $(3, 2, 13, 6, 13, 2, 3)$ is a valid twopal.

If we let $t(n)$ be the number of twopals whose elements sum to $n$, then it can be seen that $t(6) = 4$:
$$
(1, 1, 2, 1, 1), (1, 2, 2, 1), (2, 1, 1, 2), (2, 2, 2)
$$

Similarly, $t(20) = 824$.

In searching for the answer to the ultimate question of life, the universe, and everything, it can be verified that $t(42) = 1999923$, which happens to be the first value of $t(n)$ that exceeds one million.

However, your challenge to the "ultimatest" question of life, the universe, and everything is to find the least value of $n \gt 42$ such that $t(n)$ is divisible by one million.

### 710. 一百万位成员

**2020 年 4 月 5 日（星期日），欧拉计划成员数首次冲破百万大关。为庆祝此里程碑，我们特此提出本题。感谢欧拉计划的每一份子！**

元素之和为 $6$ 的回文元组共有 $8$ 个：

$$
(1, 1, 1, 1, 1, 1), (1, 1, 2, 1, 1), (1, 2, 2, 1), (1, 4, 1), (2, 1, 1, 2), (2, 2, 2), (3, 3), (6)
$$

若某个回文元组含有至少一个元素 $2$，则称其为 *含二回文元组*。需要说明，元组中的元素不仅限于单个数位：例如 $(3, 2, 13, 6, 13, 2, 3)$ 也是合法的含二回文元组。

记 $t(n)$ 为：元素之和为 $n$ 的含二回文元组的数量，则可见 $t(6) = 4$：
$$
(1, 1, 2, 1, 1), (1, 2, 2, 1), (2, 1, 1, 2), (2, 2, 2)
$$

类似的有 $t(20) = 824$。

在尝试回答生命、宇宙和世间万物的终极问题 [^1] 时，你验证过 $t(42) = 1999923$——这恰是首个大于一百万的 $t(n)$。

[^1]: 这是一个知名的梗，出自英国作家 Douglas Adams 的科幻小说《银河系漫游指南》(The Hitchhiker's Guide to the Galaxy)。原作中，超级计算机「深思 (*Deep Thought*)」在 750 万年的计算后，得出生命、宇宙和世间万物的终极问题的答案是 42。

然而，你现在有了新挑战：回答生命、宇宙和世间万物的”最终极“问题——求最小的整数 $n > 42$ ，使得 $t(n)$ 可被一百万整除。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
