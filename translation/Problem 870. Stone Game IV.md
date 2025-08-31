### [870. Stone Game IV](https://projecteuler.net/problem=870)

Two players play a game with a single pile of stones of initial size $n$. They take stones from the pile in turn, according to the following rules which depend on a fixed real number $r > 0$:

- In the first turn, the first player may take $k$ stones with $1 \le k \lt n$.
- If a player takes $m$ stones in a turn, then in the next turn the opponent may take $k$ stones with $1 \le k \le \lfloor r \cdot m \rfloor$.

Whoever cannot make a legal move loses the game.

Let $L(r)$ be the set of initial pile sizes $n$ for which the second player has a winning strategy. For example, $L(0.5) = \{1\}$, $L(1) = \{1, 2, 4, 8, 16, \dots\}$, $L(2) = \{1, 2, 3, 5, 8, \dots\}$.

A real number $q \gt 0$ is a <i>transition value</i> if $L(s)$ is different from $L(t)$ for all $s < q < t$.  
Let $T(i)$ be the $i$-th transition value. For example, $T(1) = 1$, $T(2) = 2$, $T(22) \approx 6.3043478261$.

Find $T(123456)$ and give your answer rounded to $10$ digits after the decimal point.

### 870. 取石子游戏 4

两位玩家正在玩取石子游戏，它们须轮流从初始时含 $n$ 枚石子的石堆中取石子。取石子的规则如下，固定实数 $r > 0$：

- 第一轮中，先手可以取走任意多枚石子，但不能不取。
- 如果某玩家在某一轮中取走了 $m$ 枚石子，那下一轮中，其对手取走的石子数 $k$ 须满足 $1 \leq k \leq \lfloor r \cdot m \rfloor$。

无法行动者输。

记 $L(r)$ 为：能使得后手有必胜策略的 $n$ 构成的集合。例如，$L(0.5) = \{1\}$、$L(1) = \{1, 2, 4, 8, 16, \dots\}$、$L(2) = \{1, 2, 3, 5, 8, \dots\}$。

若实数 $q > 0$ 满足：对诸 $s < q < t$，$L(s) \neq L(t)$，则称 $q$ 是一个 *过渡值*。并记 $T(i)$ 为第 $i$ 个过渡值。例如，$T(1) = 1$、$T(2) = 2$、$T(22) \approx 6.3043478261$。

求 $T(123456)$，并将答案四舍五入至小数点后第 10 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
