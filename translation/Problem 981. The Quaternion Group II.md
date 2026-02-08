### [981. The Quaternion Group II](https://projecteuler.net/problem=981)

Starting from an empty string, we want to build a string with letters "x", "y", "z". At each step, one of the following operations is performed:

- insert two consecutive identical letters "xx", "yy" or "zz" anywhere into the string;
- replace one letter in the string with two consecutive letters, according to the rule: "x" $\to$ "yz", "y" $\to$ "zx", "z" $\to$ "xy";
- exchange two consecutive **different** letters in the string, e.g. "xy" $\to$ "yx", "zx" $\to$ "xz", etc.

A string is called *neutral* if it is possible to produce the string from the empty string after an **even** number of steps.

Let $N(X, Y, Z)$ be the number of neutral strings which contain $X$ copies of "x", $Y$ copies of "y" and $Z$ copies of "z".  
For example, $N(2, 2, 2) = 42$ and $N(8, 8, 8) = 4732773210$.

Find the sum of $N(i^3, j^3, k^3)$ for $0 \le i, j, k \lt 88$. Give your answer modulo $888\,888\,883$.

### 981. 四元群 2

从一个空串开始，我们希望构造一个仅含字母 'x'、'y'、'z' 的字符串。构造的每一步中，你只能进行如下操作之一：

- 在这个字符串中的任意处插入两个连续且相同的字符 "xx"、"yy" 或 "zz"。
- 依照如下规则，把字符串中的一个字符替换成两个连续字符："x" $\to$ "yz"、"y" $\to$ "zx"、"z" $\to$ "xy"。
- 交换字符串中两个连续且 **不同** 的字符。例如："xy" $\to$ "yx"、"zx" $\to$ "xz" 等。

若能够从空串开始，经 **偶数** 次操作后得到某个字符串，则称这个字符串是 *中性的*。

记 $N(X, Y, Z)$ 为含 $X$ 个 "x"、$Y$ 个 "y"、$Z$ 个 "z" 的中性的字符串的数量。  
例如 $N(2, 2, 2) = 42$、$N(8, 8, 8) = 4732773210$。

求 $N(i^3, j^3, k^3)$ 的和模 $888\,888\,883$ 的值，其中 $0 \le i, j, k \lt 88$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。