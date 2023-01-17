### [817. Digits in Squares](https://pe.xiaoyaowudi.com/problem=817)

Define $m = M(n, d)$ to be the smallest positive integer such that when $m^2$ is written in base $n$ it includes the base $n$ digit $d$. For example, $M(10,7) = 24$ because if all the squares are written out in base 10 the first time the digit 7 occurs is in $24^2 = 576$. $M(11,10) = 19$ as $19^2 = 361=2A9_{11}$.

Find $\displaystyle \sum_{d = 1}^{10^5}M(p, p - d)$ where $p = 10^9 + 7$.

### 817. 平方数里的数位

令 $m = M(n, d)$ 为满足 $m^2$ 的 $n$ 进制表示下有数位 $d$ 的最小正整数 $m$。例如 $M(10,7) = 24$，因为在十进制下，平方数中第一次出现数位 7 是在 $24^2 = 576$ 时。同理 $M(11,10) = 19$，因为 $19^2 = 361=2A9_{11}$。

求 $\displaystyle \sum_{d = 1}^{10^5}M(p, p - d)$，其中 $p = 10^9 + 7$。