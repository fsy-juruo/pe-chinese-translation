### [982. The Third Dice](https://projecteuler.net/problem=982)

Alice and Bob play the following game with two six-sided dice (numbered $1$ to $6$):

1. Alice rolls both dice; she can see the rolled values but Bob cannot
2. Alice chooses one of the dice and reveals it to Bob
3. Bob chooses one of the dice: either the one he can see, or the one he cannot
4. Alice pays Bob the value shown on Bob's chosen dice

Each player devises a (possibly non-deterministic) **strategy**. An example strategy for each player could be:

- Alice chooses to reveal the dice with value closest to $3.5$, or if both are equidistant she chooses randomly with equal probability
- Bob chooses the revealed dice if its value is at least $4$; otherwise he chooses the hidden dice

In fact, these two strategies together form a **Nash equilibrium**. That is, given that Bob is using his strategy, Alice's strategy **minimises** the expected payment; and given that Alice is using her strategy, Bob's strategy **maximises** the expected payment.

With these strategies the expected payment from Alice to Bob is $\frac{145}{36}\approx 4.027778$.

To make the game more interesting, they introduce a third (six-sided) dice:

1. Alice rolls **three** dice; she can see the rolled values but Bob cannot
2. Alice chooses **two** of the dice and reveals both to Bob
3. Bob chooses one of the three dice: either one of the two visible dice, or the one hidden dice
4. Alice pays Bob the value shown on Bob's chosen dice

Supposing they settle on a pair of strategies that form a Nash equilibrium, find the expected payment from Alice to Bob, and give your answer rounded to six digits after the decimal point.

### 982. 第三颗骰子

爱丽丝和鲍勃正在用两颗六面体骰子（六个面标有 $1$ 至 $6$ 的数字）进行下述博弈：

1. 爱丽丝掷出两颗骰子；她能看到掷出的点数，但鲍勃看不到。
2. 爱丽丝从中选择一颗骰子，并向鲍勃公开展示其点数。
3. 鲍勃从两颗骰子中选择一颗（已公开或未公开的骰子均可选）。
4. 爱丽丝向鲍勃支付的金额等于鲍勃所选骰子的点数。

两人需各自制订一个（可以是非确定性的）**策略**。例如，两人可以采取如下策略：

- 爱丽丝将点数最接近 $3.5$ 的骰子公开给鲍勃，若两颗骰子的点数与 $3.5$ 的差相同，则等概率选择一个公开。
- 若已公开的骰子的点数至少是 $4$，则鲍勃选择已公开的那颗骰子；否则鲍勃选择未公开的那颗骰子。

事实上，这两个策略共同构成了一个 **纳什均衡**。也就是说，若已知鲍勃采用对应策略，爱丽丝的策略能够 **最小化** 支付金额的期望；若已知爱丽丝采用对应策略，鲍勃的策略能够 **最大化** 支付金额的期望。

若双方采取如上策略，则爱丽丝付给鲍勃的金额的期望为 $\frac{145}{36}\approx 4.027778$。

为了使博弈更加有趣，两人向这个游戏中加入了第三颗（六面体）骰子，博弈规则改为：

1. 爱丽丝掷出 **三颗** 骰子；她能看到掷出的点数，但鲍勃看不到。
2. 爱丽丝从中选择 **两颗** 骰子，并向鲍勃公开展示其点数。
3. 鲍勃从三颗骰子中选择一颗（已公开或未公开的骰子均可选）。
4. 爱丽丝向鲍勃支付的金额等于鲍勃所选骰子的点数。

假设二人最终采取的策略构成纳什均衡，求爱丽丝付给鲍勃的金额的期望。将其四舍五入至小数点后第六位作为你的答案。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。