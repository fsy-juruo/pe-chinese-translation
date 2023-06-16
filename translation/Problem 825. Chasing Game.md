### [825. Chasing Game](https://projecteuler.net/problem=825)

Two cars are on a circular track of total length $2n$, facing the same direction, initially distance $n$ apart.
They move in turn. At each turn, the moving car will advance a distance of $1$, $2$ or $3$, with equal probabilities.
The chase ends when the moving car reaches or goes beyond the position of the other car. The moving car is declared the winner.

Let $S(n)$ be the difference between the winning probabilities of the two cars.
For example, when $n = 2$, the winning probabilities of the two cars are $\frac 9 {11}$ and $\frac 2 {11}$, and thus $S(2) = \frac 7 {11}$.

Let $\displaystyle T(N) = \sum_{n = 2}^N S(n)$.

You are given that $T(10) = 2.38235282$ rounded to 8 digits after the decimal point.

Find $T(10^{14})$, rounded to 8 digits after the decimal point.

### 825. 追逐游戏

两辆车在一条总长为 $2n$ 的圆形赛道上同向而行。初始时两辆车相距 $n$ 个单位长度。

两辆车轮流移动，追逐对方。每一轮中，该轮的追逐车会等概率的选择沿赛道向前移动 $1$ 个、$2$ 个或 $3$ 个单位长度。若某一轮中，追逐车成功抵达或者超过被追逐车的位置，则追逐结束，此轮的追逐车获胜。

记 $S(n)$ 为两辆车获胜的概率之差。例如，$n = 2$ 时，两辆车获胜的概率分别为 $\frac 9 {11}$、$\frac 2 {11}$，故 $S(2) = \frac 7 {11}$。

再记 $\displaystyle T(N) = \sum_{n = 2}^N S(n)$。已知 $T(10)$ 在四舍五入至小数点后第 8 位后为 $2.38235282$。

求 $T(10^{14})$，将你的答案四舍五入至小数点后第 8 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。