### [960. Stone Game Solitaire](https://projecteuler.net/problem=960)

There are $n$ distinct piles of stones, each of size $n-1$. Starting with an initial score of $0$, the following procedure is repeated:

- Choose any two piles and remove exactly $n$ stones in total from the two piles.
- If the number of stones removed from the two piles were $a$ and $b$, add $\min(a,b)$ to the score.

If all piles are eventually emptied, the current score is confirmed as final. However, if one gets "stuck" and cannot empty all piles, the current score is discarded, resulting in a final score of $0$.

Three example sequences of turns are illustrated below for $n=4$, with each tuple representing pile sizes as one proceeds, and with additions to the score indicated above the arrows.
$$
\begin{align}
 & (3,3,3,3)\xrightarrow{+1}(0,3,2,3)\xrightarrow{+1}(0,3,1,0)\xrightarrow{+1}(0,0,0,0) & :\quad\text{final score }=3\\
 & (3,3,3,3)\xrightarrow{+1}(3,0,3,2)\xrightarrow{+2}(1,0,3,0)\xrightarrow{+1}(0,0,0,0) & :\quad\text{final score }=4\\
 & (3,3,3,3)\xrightarrow{+2}(1,3,1,3)\xrightarrow{+1}(1,2,1,0)\rightarrow\text{stuck!} & :\quad\text{final score }=0
\end{align}
$$

Define $F(n)$ to be the sum of the final scores achieved for every sequence of turns which successfully empty all piles.

You are given $F(3)=12$, $F(4)=360$, and $F(8)=16785941760$.

Find $F(100)$. Give your answer modulo $10^9+7$.

### 960. 单人取石子游戏

现有 $n$ 个互异、各含有 $n - 1$ 枚石子的石堆。初始时，你的得分是 $0$，随后你须重复如下过程：

- 任取两个石堆，并从这两个石堆中总共取走恰好 $n$ 枚石子。
- 如果你从两个石堆中分别取走了 $a$ 枚、$b$ 枚石子，那么本轮中你将得 $\min(a, b)$ 分。

若你最终取走了所有石子，那么你的最终得分就是先前所有轮得分的总和。然而，如果你在某一轮中无法取走石子，且仍有石子剩余时，则本次游戏作废，你的最终得分是 $0$。

如下是 $n = 4$ 时的三种可能的游戏过程，我们用四元组代表当前各堆剩余的石子数，并在箭头上方标明该轮得分：

$$
\begin{align}
 & (3,3,3,3)\xrightarrow{+1}(0,3,2,3)\xrightarrow{+1}(0,3,1,0)\xrightarrow{+1}(0,0,0,0) & :\quad\text{最终得分 }=3\\
 & (3,3,3,3)\xrightarrow{+1}(3,0,3,2)\xrightarrow{+2}(1,0,3,0)\xrightarrow{+1}(0,0,0,0) & :\quad\text{最终得分 }=4\\
 & (3,3,3,3)\xrightarrow{+2}(1,3,1,3)\xrightarrow{+1}(1,2,1,0)\rightarrow\text{无法操作！} & :\quad\text{最终得分 }=0
\end{align}
$$

记 $F(n)$ 为：所有能够取走所有石子的操作序列的最终得分的和。已知：$F(3)=12$、$F(4)=360$ 和 $F(8)=16785941760$。

求 $F(100)$ 模 $(10^9+7)$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。