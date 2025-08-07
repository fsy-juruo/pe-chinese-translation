### [956. Super Duper Sum](https://projecteuler.net/problem=956)

The total number of prime factors of $n$, counted with multiplicity, is denoted $\Omega(n)$.  
For example, $\Omega(12)=3$, counting the factor $2$ twice, and the factor $3$ once.

Define $D(n, m)$ to be the sum of all divisors $d$ of $n$ where $\Omega(d)$ is divisible by $m$.   
For example, $D(24, 3)=1+8+12=21$.

The **superfactorial** of $n$, often written as $n\$$, is defined as the product of the first $n$ factorials:
$$
n\$=1!\times 2! \times\cdots\times n!
$$
The **superduperfactorial** of $n$, we write as $n\bigstar$, is defined as the product of the first $n$ superfactorials:
$$
n\bigstar=1\$ \times 2\$ \times\cdots\times n\$
$$

You are given $D(6\bigstar, 6)=6368195719791280$.

Find $D(1\,000\bigstar, 1\,000)$. 
Give your answer modulo $999\,999\,001$.

### 956. 超酷阶乘的求和

记 $\Omega(n)$ 为 $n$ 的质因子的数量（重复质因数计多次）。例如，因为 $12 = 2^2 \times 3$，所以 $\Omega(12) = 3$。

记 $D(n, m)$ 为：所有满足 $d$ 能整除 $n$、$m$ 能整除 $\Omega(d)$ 的整数 $d$ 的和。例如：$D(24, 3)=1+8+12=21$。

我们将前 $n$ 个阶乘之积称作 $n$ 的 **超阶乘**，记作 $n \$$：

$$
n\$=1!\times 2! \times\cdots\times n!
$$


我们将前 $n$ 个超阶乘之积称作 $n$ 的 **超酷阶乘**，记作 $n \bigstar$：

$$
n\bigstar=1\$ \times 2\$ \times\cdots\times n\$
$$

已知 $D(6\bigstar, 6)=6368195719791280$。

求 $D(1\,000\bigstar, 1\,000)$ 模 $999\,999\,001$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
