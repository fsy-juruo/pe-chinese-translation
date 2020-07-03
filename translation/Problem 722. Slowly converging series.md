### [722. Slowly converging series](https://projecteuler.net/problem=722)

For a non-negative integer $k$, define

$E_k(q) = \sum\limits_{n = 1}^\infty \sigma_k(n)q^n$

where $\sigma_k(n) = \sum_{d \mid n} d^k$ is the sum of the $k$-th powers of the positive divisors of $n$.

It can be shown that, for every $k$, the series $E_k(q)$ converges for any $0 &lt; q &lt; 1$.

For example,

$E_1(1 - \frac{1}{2^4}) = \mathrm{3.872155809243e2}$

$E_3(1 - \frac{1}{2^8}) = \mathrm{2.767385314772e10}$

$E_7(1 - \frac{1}{2^{15}}) = \mathrm{6.725803486744e39}$

All the above values are given in scientific notation rounded to twelve digits after the decimal point.

Find the value of $E_{15}(1 - \frac{1}{2^{25}})$.

Give the answer in scientific notation rounded to twelve digits after the decimal point.

### 722. 缓慢收敛的级数

对于一个非负整数 $k$，定义：

$E_k(q) = \sum\limits_{n = 1}^\infty \sigma_k(n)q^n$

其中 $\sigma_k(n) = \sum_{d \mid n} d^k$ 等于 $n$ 的正约数的 $k$ 次方之和。

可以证明，对于任意 $k$，只要 $0 < q < 1$ 时，该级数 $E_k(q)$ 收敛。

比如说：

$E_1(1 - \frac{1}{2^4}) = \mathrm{3.872155809243e2}$

$E_3(1 - \frac{1}{2^8}) = \mathrm{2.767385314772e10}$

$E_7(1 - \frac{1}{2^{15}}) = \mathrm{6.725803486744e39}$

以上所有数值以科学计数法给出，四舍五入至小数点 12 位。

计算 $E_{15}(1 - \frac{1}{2^{25}})$。将答案表示为科学计数法，四舍五入至小数点后 12 位。
