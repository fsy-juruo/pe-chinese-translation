### [865. Triplicate Numbers](https://projecteuler.net/problem=865)

A *triplicate number* is a positive integer such that, after repeatedly removing three consecutive identical digits from it, all its digits can be removed.

For example, the integer $122555211$ is a triplicate number:
$$
122{\color{red}555}211 \rightarrow 1{\color{red}222}11\rightarrow{\color{red}111}\rightarrow.
$$
On the other hand, neither $663633$ nor $9990$ are triplicate numbers.

Let $T(n)$ be how many triplicate numbers are less than $10^n$.

For example, $T(6) = 261$ and $T(30) = 5576195181577716$.

Find $T(10^4)$. Give your answer modulo $998244353$.

### 865. 三连数

若可以通过不断删去三个连续、相同的数位，将某正整数的所有数位删去，则称这个正整数是 *三连数*。

例如，通过下述删数位的方式，可以证明 $122555211$ 是一个三连数：

$$
122{\color{red}555}211 \rightarrow 1{\color{red}222}11\rightarrow{\color{red}111}\rightarrow.
$$

反之，$663633$、$9990$ 都不是三连数。

记 $T(n)$ 为 $< 10^n$ 的三连数的个数。例如：$T(6) = 261$、$T(30) = 5576195181577716$。

求 $T(10^4)$ 模 $998244353$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。