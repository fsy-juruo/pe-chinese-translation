### [901. Well Drilling](https://projecteuler.net/problem=901)

A driller drills for water. At each iteration the driller chooses a depth $d$ (a positive real number), drills to this depth and then checks if water was found. If so, the process terminates. Otherwise, a new depth is chosen and a new drilling starts from the ground level in a new location nearby.

Drilling to depth $d$ takes exactly $d$ hours. The groundwater depth is constant in the relevant area and its distribution is known to be an [exponential random variable](https://en.wikipedia.org/wiki/Exponential_distribution) with expected value of $1$. In other words, the probability that the groundwater is deeper than $d$ is $e^{-d}$.

Assuming an optimal strategy, find the minimal expected drilling time in hours required to find water. Give your answer rounded to 9 places after the decimal point.

### 901. 钻井

一位钻井工人正在钻井。在每次，钻井工人任选一个正实数 $d$，钻井至距地表深度为 $d$ 的地方，并检查是否能找到水。如果没能找到水，钻井工人将回到地表，选择一处新地方并重复执行上述过程；否则，钻井过程即刻终止。

钻井至距地表深度为 $d$ 的地方需要 $d$ 小时。在钻井区域内，地下水深度恒定，其分布服从期望是 $1$ 的 [指数分布](https://zh.wikipedia.org/wiki/%E6%8C%87%E6%95%B0%E5%88%86%E5%B8%83)。换句话说，地下水的深度 $> d$ 的概率是 $\mathrm{e}^{-d}$。

若钻井工人采取最优策略，请问钻井工人为找到地下水，期望需要钻井多少小时？将你的答案四舍五入至小数点后第 9 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。


