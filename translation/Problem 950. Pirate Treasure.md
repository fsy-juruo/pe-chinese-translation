### [950. Pirate Treasure](https://projecteuler.net/problem=950)

A band of pirates has come into a hoard of treasure, and must decide how to distribute it amongst themselves. The treasure consists of identical, indivisible gold coins.

According to pirate law, the distribution of treasure must proceed as follows:

1. The most senior pirate proposes a distribution of the coins.
2. All pirates, including the most senior, vote on whether to accept the distribution.
3. If at least half of the pirates vote to accept, the distribution stands.
4. Otherwise, the most senior pirate must walk the plank, and the process resumes from step 1 with the next most senior pirate proposing another distribution.

The *happiness* of a pirate is equal to $-\infty$ if he doesn't survive; otherwise, it is equal to $c + p\cdot w$, where $c$ is the number of coins that pirate receives in the distribution, $w$ is the total number of pirates who were made to walk the plank, and $p$ is the *bloodthirstiness* of the pirate.

The pirates have a number of characteristics:

- Greed: to maximise their happiness.
- Ruthlessness: incapable of cooperation, making promises or maintaining any kind of reputation.
- Shrewdness: perfectly rational and logical.

Consider the happiness $c(n,C,p) + p\cdot w(n,C,p)$ of the most senior surviving pirate in the situation where $n$ pirates, all with equal bloodthirstiness $p$, have found $C$ coins. For example, $c(5,5,\frac{1}{10}) = 3$ and $w(5,5,\frac{1}{10})=0$ because it can be shown that if the most senior pirate proposes a distribution of $3,0,1,0,1$ coins to the pirates (in decreasing order of seniority), the three pirates receiving coins will all vote to accept. On the other hand, $c(5,1,\frac{1}{10}) = 0$ and $w(5,1,\frac{1}{10}) = 1$: the most senior pirate cannot survive with any proposal, and then the second most senior pirate must give the only coin to another pirate in order to survive.

Define $\displaystyle T(N,C,p) = \sum_{n=1}^N \left ( c(n,C,p) + w(n,C,p) \right )$. You are given that $T(30,3,\frac{1}{\sqrt{3}}) = 190$, $T(50,3,\frac{1}{\sqrt{31}}) = 385$, and $T(10^3, 101, \frac{1}{\sqrt{101}}) = 142427$.

Find $\displaystyle \sum_{k=1}^6 T(10^{16},10^k+1,\tfrac{1}{\sqrt{10^k+1}})$.  Give the last 9 digits as your answer.

### 950. 海盗的宝藏

一帮海盗得到了秘藏的宝藏——若干完全相同、不可再分的金币！他们必须决定如何分赃了。

根据海盗间的规章，分配宝藏的过程须按如下过程进行：

1. 地位最高的一位海盗提出一种分配金币的方案。
2. 所有海盗（包括地位最高的这位海盗）将投票表决是否同意这种分配方案。
3. 如果至少半数海盗投出同意票，则该分配方案获得通过。
4. 否则，这名海盗须走跳板自尽。整个过程从头开始，剩余海盗中地位最高的一位将重新提出一种分配金币的方案，以此类推。

如果某名海盗没有活下来，那他的 *愉悦度* 是 $-\infty$；否则，他的愉悦度是 $c + p\cdot w$，其中 $c$ 是这名海盗分得的金币数、$w$ 是走跳板自尽的海盗的数量、$p$ 是这位海盗的 *嗜血度*。

这帮海盗有如下特征：

- 贪婪：他们都希望最大化自己的愉悦度。
- 无情：他们不会寻求合作、做出承诺或维护名誉。
- 精明：他们都是完全理性、讲求逻辑的人。

若现在有 $n$ 位海盗、每位海盗的嗜血度都是 $p$、宝藏中有 $C$ 枚金币，我们考虑存活下来的海盗中，地位最高的一位海盗的愉悦度 $c(n,C,p) + p\cdot w(n,C,p)$。例如，$c(5,5,\frac{1}{10}) = 3$、$w(5,5,\frac{1}{10})=0$，因为地位最高的海盗可按地位从高到低的顺序，分别分配 $3$、$0$、$1$、$0$、$1$ 枚硬币给各位海盗，此时拿到金币的海盗都会投赞成票。另一方面，$c(5,1,\frac{1}{10}) = 0$、$w(5,1,\frac{1}{10}) = 1$，因为不管地位最高的海盗如何分配金币，他都活不下来，而地位第二高的海盗为了活命，必须把仅有的一枚硬币分给另一位海盗。

定义 $\displaystyle T(N,C,p) = \sum_{n=1}^N \left ( c(n,C,p) + w(n,C,p) \right )$，已知 $T(30,3,\frac{1}{\sqrt{3}}) = 190$、$T(50,3,\frac{1}{\sqrt{31}}) = 385$、$T(10^3, 101, \frac{1}{\sqrt{101}}) = 142427$。

求 $\displaystyle \sum_{k=1}^6 T(10^{16},10^k+1,\tfrac{1}{\sqrt{10^k+1}})$，并将结果的末 9 位作为你的答案。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。