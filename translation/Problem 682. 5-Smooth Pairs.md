### [682. 5-Smooth Pairs](https://projecteuler.net/problem=682)

5-smooth numbers are numbers whose largest prime factor doesn't exceed 5.  
5-smooth numbers are also called Hamming numbers.

Let $\Omega(a)$ be the count of prime factors of $a$ (counted with multiplicity).  
Let $s(a)$ be the sum of the prime factors of $a$ (with multiplicity).  
For example, $\Omega(300) = 5$ and $s(300) = 2+2+3+5+5 = 17$.

Let $f(n)$ be the number of pairs, $(p,q)$, of Hamming numbers such that $\Omega(p)=\Omega(q)$ and $s(p)+s(q)=n$.  
You are given $f(10)=4$ (the pairs are $(4,9),(5,5),(6,6),(9,4)$) and $f(10^2)=3629$.

Find $f(10^7) \bmod 1\,000\,000\,007$.

### 682. 5-光滑数对

5-光滑数，又称 Hamming 数，是最大质因数不超过 5 的数。  

令 $\Omega(a)$ 为 $a$ 质因数分解后，质因数的个数，相同的质因数计算多次。  
令 $s(a)$ 为 $a$ 质因数分解后，质因数之和，相同的质因数计算多次。  
例如，$\Omega(300) = 5$，$s(300) = 2+2+3+5+5 = 17$。

令 $f(n)$ 为满足 $p$，$q$ 均为 5-光滑数，且 $\Omega(p)=\Omega(q)$，$s(p)+s(q)=n$ 的 $(p,q)$ 数对的个数。  
已知 $f(10)=4$ (4 个数对分别是 $(4,9),(5,5),(6,6),(9,4)$) 且 $f(10^2)=3629$。

求 $f(10^7) \bmod 1\,000\,000\,007$。
