### [790. Clock Grid](https://projecteuler.net/problem=790)

There is a grid of length and width 50515093 populated with a clock in each grid square. The clocks are all analogue showing a single hour hand initially pointing at 12.  

A sequence $S_t$ is created where:
$$
\begin{align}
S_0 &= 290797\\
S_t &= S_{t-1}^2 \bmod 50515093 \qquad t>0
\end{align}
$$
The four numbers $N_t = (S_{4t-4}, S_{4t-3}, S_{4t-2}, S_{4t-1})$ represent a range within the grid, with the first pair of numbers representing the x-bounds and the second pair representing the y-bounds. For example, if $N_t = (3,9,47,20)$, the range would be $3\le x\le 9$ and $20\le y\le47$, and would include 196 clocks.

For each $t$ $(t > 0)$, the clocks within the range represented by $N_t$ are moved to the next hour $12\rightarrow 1\rightarrow 2\rightarrow \cdots $.

We define $C(t)$ to be the sum of the hours that the clock hands are pointing to after timestep $t$.
You are given $C(0) = 30621295449583788$, $C(1) =  30613048345941659$, $C(10) = 21808930308198471$ and $C(100) = 16190667393984172$.

Find $C(10^5)$.

### 790. 时钟网格

现有一个长、宽均为 50515093 的网格。每一个小方格里均有一个初始指向 12 点的时钟。

定义序列 $\{S_t\}$ 满足：
$$
\begin{align}
S_0 &= 290797\\
S_t &= S_{t-1}^2 \bmod 50515093 \qquad t>0
\end{align}
$$

故我们可以用一个四元组 $N_t = (S_{4t-4}, S_{4t-3}, S_{4t-2}, S_{4t-1})$ 来表示网格内的一个子矩形；其中，这个四元组的前两个数代表 $x$ 坐标的范围，后两个数代表 $y$ 坐标的范围。例如，若四元组 $N_t = (3,9,47,20)$，则其表示网格中 $3\le x\le 9$ 且 $20\le y\le47$ 的一部分；这一部分有 196 个时钟。

对于每一个时刻 $t$ $(t > 0)$，在四元组 $N_t$ 所表示的子矩形范围内的时钟将按 $12\rightarrow 1\rightarrow 2\rightarrow \cdots $ 的规则向前移动 1 小时。

记 $C(t)$ 为在 $t$ 时刻后，所有时钟所指向的小时数之和。已知 $C(0) = 30621295449583788$，$C(1) = 30613048345941659$，$C(10) = 21808930308198471$，$C(100) = 16190667393984172$。

求 $C(10^5)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。