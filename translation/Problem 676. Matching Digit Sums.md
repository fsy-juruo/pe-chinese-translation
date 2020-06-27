### [676. Matching Digit Sums](https://projecteuler.net/problem=676)

Let $d(i,b)$ be the digit sum of the number $i$ in base $b$. For example $d(9,2)=2$, since $9=1001_2$. When using different bases, the respective digit sums most of the time deviate from each other, for example $d(9,4)=3 \ne d(9,2)$.

However, for some numbers $i$ there will be a match, like $d(17,4)=d(17,2)=2$. Let $ M(n,b_1,b_2)$ be the sum of all natural numbers $i \le n$ for which $d(i,b_1)=d(i,b_2)$. For example, $M(10,8,2)=18$, $M(100,8,2)=292$ and $M(10^6,8,2)=19173952$.

Find $\displaystyle \sum_{k=3}^6 \sum_{l=1}^{k-2}M(10^{16},2^k,2^l)$, giving the last 16 digits as the answer.

### 676. 匹配数位和

令 $d(i,b)$ 为 $i$ 在 $b$ 进制下的**数位和**。比如说，因为 $9=1001_2$，故 $d(9,2)=2$，当进制不同时，大多数情况下，这些进制下的数位和不相等。例如 $d(9,4)=3 \ne d(9,2)$。

但是，对于某些数字 $i$，在某些进制下，它们的数位和是相等的，就像 $d(17,4)=d(17,2)=2$。令 $M(n,b_1,b_2)$ 为所有满足 $d(i,b_1)=d(i,b_2)$，且 $i \leq n$ 的自然数之和。已知 $M(10,8,2)=18$，$M(100,8,2)=292$ 且 $M(10^6,8,2)=19173952$。

求出 $\displaystyle \sum_{k=3}^6 \sum_{l=1}^{k-2}M(10^{16},2^k,2^l)$，你只需给出答案的最后 16 位。
