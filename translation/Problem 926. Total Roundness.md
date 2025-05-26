### [926. Total Roundness](https://projecteuler.net/problem=926)

A **round number** is a number that ends with one or more zeros in a given base.

Let us define the *roundness* of a number $n$ in base $b$ as the number of zeros at the end of the base $b$ representation of $n$.  
For example, $20$ has roundness $2$ in base $2$, because the base $2$ representation of $20$ is $10100$, which ends with $2$ zeros.

Also define $R(n)$, the *total roundness* of a number $n$, as the sum of the roundness of $n$ in base $b$ for all $b > 1$.  
For example, $20$ has roundness $2$ in base $2$ and roundness $1$ in base $4$, $5$, $10$, $20$, hence we get $R(20)=6$.  
You are also given $R(10!) = 312$.

Find $R(10\,000\,000!)$. Give your answer modulo $10^9 + 7$.

### 926. 总舍入程度

若某数在某给定进制下以 0 结尾，则称这个数是一个 **舍入数**。

对于某个数 $n$，我们定义该数在 $b$ 进制下的 *舍入程度* 为该数的 $b$ 进制表示中末尾 0 的数量。例如 $20$ 在 $2$ 进制下的舍入程度为 $2$，因为 $20$ 的二进制表示是 $10100$，末尾有 $2$ 个 0。

我们继续定义一个数 $n$ 的 *总舍入程度* 为：对所有 $b > 1$，$n$ 在 $b$ 进制下的舍入程度的和。例如，$20$ 在 $2$ 进制下的舍入程度为 $2$，在 $4, 5, 10, 20$ 进制下的舍入程度是 $1$，故 $R(20) = 6$。

求 $R(10\,000\,000!)$ 模 $(10^9 + 7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。