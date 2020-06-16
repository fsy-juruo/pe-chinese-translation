### [719. Number Splitting](https://projecteuler.net/problem=719)

We define an $S$-number to be a natural number, $n$, that is a perfect square and its square root can be obtained by splitting the decimal representation of $n$ into $2$ or more numbers then adding the numbers.

For example, 81 is an $S$-number because $\sqrt{81}=8+1$.  
6724 is an $S$-number: $\sqrt{6724}=6+72+4$.   
8281 is an $S$-number: $\sqrt{8281}=82+8+1=8+2+81$.  
9801 is an $S$-number: $\sqrt{9801}=98+0+1$.  

Further we define $T(N)$ to be the sum of all $S$ numbers $n \leq N$. You are given $T(10^4)=41333$.

Find $T(10^{12})$

### 719. 数字分裂

定义 $S$-数为满足该数为完全平方数，且其平方根能通过将该数分成 $2$ 个及以上的部分之和得到的自然数。

比如说，$\sqrt{81}=8+1$，故 $81$ 是 $S$-数。$6724$，$8281$，$9801$ 也是 $S$-数，因为 $\sqrt{6724}=6+72+4$，$\sqrt{8281}=82+8+1=8+2+81$，$\sqrt{9801}=98+0+1$。

更进一步的，定义 $T(N)$ 为所有小于等于 $N$ 的 $S$-数之和。已知 $T(10^4)=41333$。

计算 $T(10^{12})$。
