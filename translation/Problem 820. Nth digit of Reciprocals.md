### [820. $N$<sup>th</sup> digit of Reciprocals](https://pe.xiaoyaowudi.com/problem=820)

Let $d_n(x)$ be the $n$<sup>th</sup> decimal digit of the fractional part of $x$, or $0$ if the fractional part has fewer than $n$ digits.

For example:

* $d_7 \mathopen{}\left( 1 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 2 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 4 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 5 \right)\mathclose{} = 0$
* $d_7 \mathopen{}\left( \frac 1 3 \right)\mathclose{} = 3$ since $\frac 1 3 =$ 0.333333<span style="color:#FF0000;font-weight:bold;">3</span>333...
* $d_7 \mathopen{}\left( \frac 1 6 \right)\mathclose{} = 6$ since $\frac 1 6 =$ 0.166666<span style="color:#FF0000;font-weight:bold;">6</span>666...
* $d_7 \mathopen{}\left( \frac 1 7 \right)\mathclose{} = 1$ since $\frac 1 7 =$ 0.142857<span style="color:#FF0000;font-weight:bold;">1</span>428...

Let $\displaystyle  S(n) = \sum_{k=1}^n d_n \mathopen{}\left( \frac 1 k \right)\mathclose{}$.
You are given:

* $S(7) = 0 + 0 + 3 + 0 + 0 + 6 + 1 = 10$
* $S(100) = 418$

Find $S(10^7)$.

### 820. 倒数的小数点后第 $N$ 位

记 $d_n(x)$ 为 $x$ 十进制表示下小数点后第 $n$ 位。如果 $x$ 小数点后少于 $n$ 位，则记 $d_n(x) = 0$。

例如：

* $d_7 \mathopen{}\left( 1 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 2 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 4 \right)\mathclose{} = d_7 \mathopen{}\left( \frac 1 5 \right)\mathclose{} = 0$
* 因为 $\frac 1 3 =$ 0.333333<span style="color:#FF0000;font-weight:bold;">3</span>333...，故 $d_7 \mathopen{}\left( \frac 1 3 \right)\mathclose{} = 3$
* 因为 $\frac 1 6 =$ 0.166666<span style="color:#FF0000;font-weight:bold;">6</span>666...，故 $d_7 \mathopen{}\left( \frac 1 6 \right)\mathclose{} = 6$
* 因为 $\frac 1 7 =$ 0.142857<span style="color:#FF0000;font-weight:bold;">1</span>428...，故 $d_7 \mathopen{}\left( \frac 1 7 \right)\mathclose{} = 1$

记 $\displaystyle S(n) = \sum_{k=1}^n d_n \mathopen{}\left( \frac 1 k \right)\mathclose{}$。已知：

* $S(7) = 0 + 0 + 3 + 0 + 0 + 6 + 1 = 10$
* $S(100) = 418$

求 $S(10^7)$。