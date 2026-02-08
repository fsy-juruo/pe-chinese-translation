### [758. Buckets of Water](https://projecteuler.net/problem=758)

There are 3 buckets labelled $S$ (small) of 3 litres, $M$ (medium) of 5 litres and $L$ (large) of 8 litres.  
Initially $S$ and $M$ are full of water and $L$ is empty.
By pouring water between the buckets exactly one litre of water can be measured.  
Since there is no other way to measure, once a pouring starts it cannot stop until either the source bucket is empty or the destination bucket is full.  
At least four pourings are needed to get one litre:

$$
(3,5,0)\xrightarrow{M\to L} (3,0,5) \xrightarrow{S\to M} (0,3,5) \xrightarrow{L\to S}(3,3,2)
\xrightarrow{S\to M}(1,5,2)
$$

After these operations, there is exactly one litre in bucket $S$.

In general the sizes of the buckets $S, M, L$ are $a$, $b$, $a + b$ litres, respectively. Initially $S$ and $M$ are full and $L$ is empty. If the above rule of pouring still applies and $a$ and $b$ are two coprime positive integers with $a\leq b$ then it is always possible to measure one litre in finitely many steps.

Let $P(a,b)$ be the minimal number of pourings needed to get one litre. Thus $P(3,5)=4$.  
Also, $P(7, 31)=20$ and $P(1234, 4321)=2780$.

Find the sum of $P(2^{p^5}-1, 2^{q^5}-1)$ for all pairs of prime numbers $p,q$ such that $p < q < 1000$.  
Give your answer modulo $1\,000\,000\,007$.

### 758. 水桶量水

现有三个水桶：标有 $S$ 的小桶（容量 $3$ 升）、标有 $M$ 的中桶（容量 $5$ 升）和标有 $L$ 的大桶（容量 $8$ 升）。  
初始时小桶、中桶中都装满了水，但大桶是空的。
通过在水桶之间倒水，我们可以精确地量出一升水。  
因为没有其它测量水量的方式，所以一旦开始倒水就不能停止，除非倒水的桶已空或者接水的桶已满。  
此时，为精确地量出一升水，至少需要倒四次水：

$$
(3,5,0)\xrightarrow{M\to L} (3,0,5) \xrightarrow{S\to M} (0,3,5) \xrightarrow{L\to S}(3,3,2)
\xrightarrow{S\to M}(1,5,2)
$$

如此倒完水后，小桶中恰有一升水。

现在考虑一般情况：小桶、中桶、大桶的容量分别是 $a$ 升、$b$ 升、$a + b$ 升。初始时小桶、中桶中都装满了水，但大桶是空的。若倒水时仍需遵守上述规则，且 $a, b (a \leq b)$ 是互质的正整数，那么我们一定能通过有限次倒水操作，精确地量出一升水。

记 $P(a, b)$ 为：为精确地量出一升水，最少需要的倒水次数，则有 $P(3,5)=4$。你还知道 $P(7, 31)=20$、$P(1234, 4321)=2780$。

求所有 $P(2^{p^5}-1, 2^{q^5}-1)$ 之和，其中 $p,q$ 取遍所有满足 $p < q < 1000$ 的质数对。  
给出答案模 $1\,000\,000\,007$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。