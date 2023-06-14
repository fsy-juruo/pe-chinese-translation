### [838. Not Coprime](https://projecteuler.net/problem=838)

Let $f(N)$ be the smallest positive integer that is not coprime to any positive integer $n \le N$ whose least significant digit is $3$.

For example $f(40)$ equals to $897 = 3 \cdot 13 \cdot 23$ since it is not coprime to any of $3,13,23,33$. By taking the [natural logarithm](https://en.wikipedia.org/wiki/Natural_logarithm) (log to base $e$) we obtain $\ln f(40) = \ln 897 \approx 6.799056$ when rounded to six digits after the decimal point.

You are also given $\ln f(2800) \approx 715.019337$.

Find $f(10^6)$. Enter its natural logarithm rounded to six digits after the decimal point.

### 838. 不互质

记 $f(N)$ 为满足：不与任何个位是 $3$ 且 $\leq N$ 的正整数 $n$ 互质的最小整数。例如：因为 $897 = 3 \cdot 13 \cdot 23$ 不与 $3, 13, 23, 33$ 中的任何一个互质，故 $f(40) = 897$。取 [自然对数](https://en.wikipedia.org/wiki/Natural_logarithm) 可得 $\ln f(40) = \ln 897 \approx 6.799056$（四舍五入至小数点后第 6 位）。已知：$\ln f(2800) \approx 715.019337$。

求 $f(10^6)$。将其取自然对数后四舍五入至小数点后第 6 位。