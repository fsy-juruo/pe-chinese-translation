### [851. SOP and POS](https://projecteuler.net/problem=851)

Let $n$ be a positive integer and let $E_n$ be the set of $n$-tuples of strictly positive integers.

For $u = (u_1, \cdots, u_n)$ and $v = (v_1, \cdots, v_n)$ two elements of $E_n$, we define:

- the *Sum Of Products* of $u$ and $v$, denoted by $\langle u, v\rangle$, as the sum $\displaystyle\sum_{i = 1}^n u_i v_i$;
- the *Product Of Sums* of $u$ and $v$, denoted by $u \star v$, as the product $\displaystyle\prod_{i = 1}^n (u_i + v_i)$.

Let $R_n(M)$ be the sum of $u \star v$ over all ordered pairs $(u, v)$ in $E_n$ such that $\langle u, v\rangle = M$.  
For example: $R_1(10) = 36$, $R_2(100) = 1873044$, $R_2(100!) \equiv 446575636 \bmod 10^9 + 7$.

Find $R_6(10000!)$. Give your answer modulo $10^9+7$.

### 851. 积之和与和之积

对于某正整数 $n$，记 $E_n$ 为所有 $n$ 元正整数元组的集合。

对于 $E_n$ 中的两元素 $u = (u_1, \cdots, u_n)$ 与 $v = (v_1, \cdots, v_n)$，记：

* $u$ 与 $v$ 的 *积之和* $\langle u, v \rangle = \displaystyle\sum_{i=1}^{n} u_iv_i$。 

* $u$ 与 $v$ 的 *和之积* $u \star v = \displaystyle\prod_{i=1}^{n} (u_i + v_i)$。

记 $R_n(M)$ 为：$E_n$ 中所有满足 $\langle u, v \rangle = M$ 的数对 $(u, v)$ 的 $u \star v$ 之和。已知 $R_1(10) = 36$、$R_2(100) = 1873044$、$R_2(100!) \equiv 446575636 \pmod {10^9+7}$。

求 $R_6(10000!)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。