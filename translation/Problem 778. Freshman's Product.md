### [778. Freshman's Product](https://projecteuler.net/problem=778)

If $a,b$ are two nonnegative integers with decimal representations $a=(\dots a_2a_1a_0)$ and $b=(\dots b_2b_1b_0)$ respectively, then the *freshman's product* of $a$ and $b$, denoted $a\boxtimes b$, is the integer $c$ with decimal representation $c=(\dots c_2c_1c_0)$ such that $c_i$ is the last digit of $a_i\cdot b_i$.
For example, $234 \boxtimes 765 = 480$.

Let $F(R,M)$ be the sum of $x_1 \boxtimes \dots \boxtimes x_R$ for all sequences of integers $(x_1,\dots,x_R)$ with $0\leq x_i \leq M$.
For example, $F(2, 7) = 204$, and $F(23, 76) \equiv 5870548 \pmod{ 1\,000\,000\,009}$.

Find $F(234567,765432)$, give your answer modulo $1\,000\,000\,009$.

### 778. 新生乘积

若非负整数 $a, b$ 的十进制表达分别是 $a=(\dots a_2a_1a_0)$、$b=(\dots b_2b_1b_0)$，则定义 $a$ 和 $b$ 的 *新生乘积* $a\boxtimes b$ 为正整数 $c$，其中 $c$ 的十进制表达 $(\dots c_2c_1c_0)$ 下的每一个 $c_i$ 都是对应的 $a_i\cdot b_i$ 的个位数。如有 $234 \boxtimes 765 = 480$。

记 $F(R,M)$ 为：对所有满足 $0\leq x_i \leq M$ 的 $R$ 元整数组 $(x_1,\dots,x_R)$，其 $x_1 \boxtimes \dots \boxtimes x_R$ 之和。已知：$F(2, 7) = 204$、$F(23, 76) \equiv 5870548 \pmod{ 1\,000\,000\,009}$。

求 $F(234567,765432)$ 模 $1\,000\,000\,009$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。