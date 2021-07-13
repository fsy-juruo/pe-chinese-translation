### [761. Runner and Swimmer](https://projecteuler.net/problem=761)

Two friends, a runner and a swimmer, are playing a sporting game: The swimmer is swimming within a circular pool while the runner moves along the pool edge.
While the runner tries to catch the swimmer at the very moment that the swimmer leaves the pool, the swimmer tries to reach the edge before the runner arrives there. They start the game with the swimmer located in the middle of the pool, while the runner is located anywhere at the edge of the pool.

We assume that the swimmer can move with any velocity up to $1$ in any direction and the runner can move with any velocity up to $v$ in either direction around the edge of the pool. Moreover we assume that both players can react immediately to any change of movement of their opponent.

Assuming optimal strategy of both players, it can be shown that the swimmer can always win by escaping the pool at some point at the edge before the runner gets there, if $v$ is less than the critical speed $V_{Circle} \approx 4.60333885$ and can never win if $v > V_{Circle}$.

Now the two players play the game in a perfectly square pool. Again the swimmer starts in the middle of the pool, while the runner starts at the midpoint of one of the edges of the pool. It can be shown that the critical maximal speed of the runner below which the swimmer can always escape and above which the runner can always catch the swimmer when trying to leave the pool is $V_{Square} \approx 5.78859314$.

At last, both players decide to play the game in a pool in the form of regular hexagon. Giving the same conditions as above, with the swimmer starting in the middle of the pool and the runner at the midpoint of one of the edges of the pool, find the critical maximal speed $V_{Hexagon}$ of the runner, below which the swimmer can always escape and above which the runner can always catch the swimmer.
Give your answer rounded to 8 digits after the decimal point.

### 761. 跑者与游泳者

某日，两名好友，一位是跑者，一位是游泳者，正在玩一个运动游戏：游泳者在一个圆形水池中游泳，而那名跑者在岸上，绕着水池边缘跑动。

跑者的目标是在游泳者刚上岸时抓到他，而游泳者需要确保上岸时跑者还没跑到那里。游戏开始前，游泳者在水池正中间，而跑者在水池边缘任意位置。我们假令游泳者可以以不超过 $1$ 的速度向任意方向游动，而跑者可以以不超过 $v$ 的速度在水池边缘沿正方向或反方向跑动。假设两个人都可以瞬间察觉到对手的一举一动并且做出反应。

假设二人都采用最佳策略，则可以证明，若 $v <$ 临界速度 $V_{Circle} \approx 4.60333885$ 时，不管游泳者在何处上岸，他都能做到避开跑者，故游泳者必胜。若 $v > V_{Circle}$，则游泳者必败。

后来，这两人在一个正四边形水池中玩这个游戏。游戏开始前，游泳者仍然在水池中心，而跑者则位于水池边缘任意一边的中点上。其余假设不变。可以发现此时的临界速度 $V_{Square} \approx 5.78859314$。

最终，这两人决定在一个正六边形水池中玩这个游戏。同样，除了「游戏开始前，游泳者仍然在水池中心，而跑者则位于水池边缘任意一边的中点上」这一个改变之外，其余假设不变。计算此时的临界速度 $V_{Hexagon}$。将答案四舍五入至小数点后第 8 位。
