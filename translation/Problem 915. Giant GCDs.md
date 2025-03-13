### [915. Giant GCDs](https://projecteuler.net/problem=915)

The function $s(n)$ is defined recursively for positive integers by 
$s(1) = 1$ and $s(n+1) = \big(s(n) - 1\big)^3 +2$ for $n\geq 1$.   
The sequence begins: $s(1) = 1, s(2) = 2, s(3) = 3, s(4) = 10, \ldots$.

For positive integers $N$, define 
$$
T(N) = \sum_{a=1}^N \sum_{b=1}^N \gcd\Big(s\big(s(a)\big), s\big(s(b)\big)\Big).
$$
You are given $T(3) = 12$, $T(4) \equiv 24881925$ and $T(100)\equiv 14416749$ both modulo $123456789$.

Find $T(10^8)$. Give your answer modulo $123456789$.

### 915. 巨大的最大公约数

在正整数上递归定义函数 $s(n)$ 如下：$s(1) = 1$，且对诸 $n \geq 1$ 有 $s(n+1) = \big(s(n) - 1\big)^3 +2$。$\{s(n)\}$ 的前几项是：$s(1) = 1, s(2) = 2, s(3) = 3, s(4) = 10, \ldots$。

对正整数 $N$，定义：
$$
T(N) = \sum_{a=1}^N \sum_{b=1}^N \gcd\Big(s\big(s(a)\big), s\big(s(b)\big)\Big).
$$

已知 $T(3) = 12$、$T(4) \equiv 24881925 \pmod {123456789}$、$T(100)\equiv 14416749 \pmod {123456789}$。

求 $T(10^8)$ 模 $123456789$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
