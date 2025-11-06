### [852. Coins in a Box](https://projecteuler.net/problem=852)

This game has a box of $N$ unfair coins and $N$ fair coins. Fair coins have probability 50% of landing heads while unfair coins have probability 75% of landing heads.

The player begins with a score of 0 which may become negative during play.

At each round the player randomly picks a coin from the box and guesses its type: fair or unfair. Before guessing they may toss the coin any number of times; however, each toss subtracts 1 from their score. The decision to stop tossing and make a guess can be made at any time. After guessing the player's score is increased by 20 if they are right and decreased by 50 if they are wrong. Then the coin type is revealed to the player and the coin is discarded.

After $2N$ rounds the box will be empty and the game is over. Let $S(N)$ be the expected score of the player at the end of the game assuming that they play optimally in order to maximize their expected score.

You are given $S(1) = 20.558591$ rounded to 6 digits after the decimal point.

Find $S(50)$. Give your answer rounded to 6 digits after the decimal point.

### 852. 箱中的硬币

现有一个装有 $N$ 枚不公平硬币和 $N$ 枚公平硬币的箱子。抛掷一枚公平硬币，抛到正面的概率是 50%，而对于不公平硬币，这个概率是 75%。

一玩家将用这些硬币玩一个猜硬币游戏。初始时他的分数是 0，在游戏过程中，这个分数可能变为负数。

每一轮中，该玩家均匀随机的从箱子中拿出一枚硬币，并猜测该硬币是否是公平硬币。在做出猜测前，玩家可以抛掷这枚硬币任意多次，但玩家每抛一次硬币，就将被扣掉 1 分。玩家可以在任何时刻停止抛掷并作出猜测。若玩家作出正确的猜测，则会得到 20 分，否则会被扣掉 50 分。随后，玩家将得知这枚硬币是否公平，这枚硬币即刻被丢弃。

$2N$ 轮后，箱中已没有硬币，游戏即刻结束。记 $S(N)$ 为：在玩家采取能够最大化其分数的策略的情况下，该玩家最终的期望得分。

已知，将 $S(1)$ 四舍五入至小数点后第 6 位后，结果是 $20.558591$。

求 $S(50)$ 并将你的答案四舍五入至小数点后第 6 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。