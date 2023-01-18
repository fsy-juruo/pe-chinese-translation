### [807. Loops of Ropes](https://pe.xiaoyaowudi.com/problem=807)

Given a circle $C$ and an integer $n > 1$, we perform the following operations.

In step $0$, we choose two uniformly random points $R_0$ and $B_0$ on $C$.
In step $i$ ($1 \leq i < n$), we first choose a uniformly random point $R_i$ on $C$ and connect the points $R_{i - 1}$ and $R_i$ with a red rope; then choose a uniformly random point $B_i$ on $C$ and connect the points $B_{i - 1}$ and $B_i$ with a blue rope.
In step $n$, we first connect the points $R_{n - 1}$ and $R_0$ with a red rope; then connect the points $B_{n - 1}$ and $B_0$ with a blue rope.
Each rope is straight between its two end points, and lies above all previous ropes.

After step $n$, we get a loop of red ropes, and a loop of blue ropes.
Sometimes the two loops can be separated, as in the left figure below; sometimes they are "linked", hence cannot be separated, as in the middle and right figures below.

![](https://pe.xiaoyaowudi.com/project/images/p807.jpg)

Let $P(n)$ be the probability that the two loops can be separated.
For example, $P(3) = \frac{11}{20}$ and $P(5) \approx 0.4304177690$.

Find $P(80)$, rounded to $10$ digits after decimal point.

### 807. 绳环

给定圆 $C$ 以及正整数 $n > 1$，随后我们进行如下操作：

第 $0$ 步时，我们在 $C$ 上均匀随机地选出两个点 $R_0$ 和 $B_0$。
第 $i$ ($1 \leq i < n$) 步中，我们在 $C$ 上均匀随机地选出一个点 $R_i$，然后用一根红色绳连接 $R_{i - 1}$ 和 $R_i$。随后，我们在 $C$ 上均匀随机地选出一个点 $B_i$，然后用一根蓝色绳连接 $B_{i - 1}$ 和 $B_i$。
第 $n$ 步时，我们将 $R_{n - 1}$ 和 $R_0$ 用一根红色绳连接，将 $B_{n - 1}$ 和 $B_0$ 用一根蓝色绳连接。
保证每根绳子均绷紧，并位于目前所有绳子的上方。

第 $n$ 步后，我们会得到两个绳环，一个红色的和一个蓝色的。有时这两个绳环能被分开，如左图所示。而有时这两个绳环会互锁，无法分开，如中间与右边两图所示。

![](https://pe.xiaoyaowudi.com/project/images/p807.jpg)

记 $P(n)$ 为两个绳环能被分开的概率。
如 $P(3) = \frac{11}{20}$ 且 $P(5) \approx 0.4304177690$。

求 $P(80)$，将你的答案四舍五入至小数点后第 $10$ 位。