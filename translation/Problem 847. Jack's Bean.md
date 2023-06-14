### [847. Jack's Bean](https://projecteuler.net/problem=847)

Jack has three plates in front of him. The giant has $N$ beans that he distributes to the three plates. All the beans look the same, but one of them is a magic bean. Jack doesn't know which one it is, but the giant knows.

Jack can ask the giant questions of the form: "Does this subset of the beans contain the magic bean?" In each question Jack may choose any subset of beans from a single plate, and the giant will respond truthfully.

If the three plates contain $a$, $b$ and $c$ beans respectively, we let $h(a, b, c)$ be the minimal number of questions Jack needs to ask in order to guarantee he locates the magic bean. For example, $h(1, 2, 3) = 3$ and $h(2, 3, 3) = 4$.

Let $H(N)$ be the sum of $h(a, b, c)$ over all triples of non-negative integers $a$, $b$, $c$ with $1 \leq a + b + c \leq N$.
You are given: $H(6) = 203$ and $H(20) = 7718$.

A **repunit**, $R_n$, is a number made up with $n$ digits all '1'. For example, $R_3 = 111$ and $H(R_3) = 1634144$.

Find $H(R_{19})$. Give your answer modulo  $1\,000\,000\,007$.

### 847. 杰克的豆子

杰克面前有三个空盘子。一位巨人将 $N$ 粒外表完全一样的豆子随机分至这三个盘中。这 $N$ 粒豆子中有一粒“魔法豆”，杰克并不知道“魔法豆”是哪一粒，但巨人知道。

杰克每一次可以从一个盘子中挑出一部分豆子，并询问巨人：”这一部分豆子中有‘魔法豆’吗？”而巨人会如实回答。

记 $h(a, b, c)$ 为：当三个盘子分别盛有 $a, b, c$ 粒豆子时，为了保证找到“魔法豆”，杰克最少需要询问的问题数。已知：$h(1, 2, 3) = 3$，$h(2, 3, 3) = 4$。

进一步记 $H(n)$ 为：对于所有满足 $1 \leq a + b + c \leq N$ 的非负整数三元组 $(a, b, c)$，$h(a, b, c)$ 之和。已知：$H(6) = 203$，$H(20) = 7718$。

第 $n$ 个 **全一数（repunit）** $R_n$ 的十进制表达由 $n$ 个 1 组成。已知：$R_3 = 111$，$H(R_3) = 1634144$。

求 $H(R_{19})$ 模 $1 \, 000 \, 000 \, 007$ 之值。

