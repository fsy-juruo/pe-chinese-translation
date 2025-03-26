### [910. L-expressions II](https://projecteuler.net/problem=910)

An *L-expression* is defined as any one of the following:

- a natural number;
- the symbol $A$;
- the symbol $Z$;
- the symbol $S$;
- a pair of L-expressions $u, v$, which is written as $u(v)$.

An L-expression can be transformed according to the following rules:

- $A(x) \to x + 1$ for any natural number $x$;
- $Z(u)(v) \to v$ for any L-expressions $u, v$;
- $S(u)(v)(w) \to v(u(v)(w))$ for any L-expressions $u, v, w$.

For example, after applying all possible rules, the L-expression $S(Z)(A)(0)$ is transformed to the number $1$:

$$
S(Z)(A)(0) \to A(Z(A)(0)) \to A(0) \to 1.
$$

Similarly, the L-expression $S(S)(S(S))(S(Z))(A)(0)$ is transformed to the number $6$ after applying all possible rules.

Define the following L-expressions:

- $C_0 = Z$;
- $C_i = S(C_{i - 1})$ for $i \ge 1$;
- $D_i = C_i(S)(S)$.

For natural numbers $a, b, c, d, e$, let $F(a, b, c, d, e)$ denote the result of the L-expression $D_a(D_b)(D_c)(C_d)(A)(e)$ after applying all possible rules.

Find the last nine digits of $F(12, 345678, 9012345, 678, 90)$.

**Note:** it can be proved that the L-expression in question can only be transformed a finite number of times, and the final result does not depend on the order of the transformations.

### 910. L-表达式 2

我们按如下规则递归定义 *L-表达式*：

- 一个自然数是 L-表达式。
- 符号 $A$ 是 L-表达式。
- 符号 $Z$ 是 L-表达式。
- 符号 $S$ 是 L-表达式。
- 一对 L-表达式 $u, v$ 是 L-表达式，这个 L-表达式记作 $u(v)$。

我们可以按如下规则对 L-表达式进行转化：

- 对诸自然数 $x$，$A(x) \to x + 1$；
- 对任意 L-表达式 $u, v$，$Z(u)(v) \to v$；
- 对任意 L-表达式 $u, v, w$，$S(u)(v)(w) \to v(u(v)(w))$。

例如，不断使用上述规则可以将 L-表达式 $S(Z)(A)(0)$ 转化为数字 $1$：

$$
S(Z)(A)(0) \to A(Z(A)(0)) \to A(0) \to 1.
$$

同样的，不断使用上述规则可以将 L-表达式 $S(S)(S(S))(S(Z))(A)(0)$ 转化为数字 $6$。

定义如下 L-表达式：

- $C_0 = Z$；
- 对诸 $i \ge 1$，$C_i = S(C_{i - 1})$；
- $D_i = C_i(S)(S)$。

对自然数 $a, b, c, d, e$，令 $F(a, b, c, d, e)$ 为：不断使用上述规则转化，L-表达式 $D_a(D_b)(D_c)(C_d)(A)(e)$ 对应的数字。

求 $F(12, 345678, 9012345, 678, 90)$ 的末 9 位。

**注释：** 可以证明，本题中涉及的 L-表达式只能被转化有限次，且转化的最终结果和转化的顺序无关。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。