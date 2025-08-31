### [958. Euclid's Labour](https://projecteuler.net/problem=958)

The **Euclidean algorithm** can be used to find the **greatest common divisor** of two positive integers. At each step of the algorithm the smaller number is subtracted from the larger one. The algorithm terminates when the numbers are equal, which is then the greatest common divisor of the original numbers.

For two numbers $n$ and $m$, let $d(n, m)$ be the number of subtraction steps used by the Euclidean algorithm for computing the greatest common divisor of $n$ and $m$.

For a number $n$, let $f(n)$ be the positive number $m$ coprime to $n$ that minimizes $d(n, m)$. If more than one number attains the minimum, the minimal $m$ is chosen.

For example, at least four steps are needed for computing the GCD of $7$ and any positive number $m$ coprime to $7$. This number of steps is obtained by $m=2,3,4,5$, yielding $f(7)=2$. You are also given $f(89)=34$ and $f(8191) = 1856$.

Find $f(10^{12}+39)$.

### 958. 欧几里得的劳动

欲求解两个正整数的 **最大公约数**，可以使用 **欧几里得算法**：不断将两数中较大的一个减去两数中较小的一个，直至二者相等，此时得到的就是原来两个数的最大公约数。

对两个整数 $n, m$，我们记 $d(n, m)$ 为：使用欧几里得算法计算 $n, m$ 的最大公约数时，进行的减法次数。

对某整数 $n$，我们记 $f(n)$ 为：所有与 $n$ 互质的正整数中，能使 $d(n, m)$ 取得最小值的正整数 $m$。若有多个符合要求的整数，则取最小的一个 $m$。

例如，对任何与 $7$ 互质的整数 $m$，计算  $\gcd(7, m)$ 至少需要 $4$ 次减法，且最小次数在 $m=2,3,4,5$ 时取到，因而 $f(7) = 2$。你已知 $f(89)=34$、$f(8191) = 1856$。

求 $f(10^{12}+39)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
