### [882. Removing Bits](https://projecteuler.net/problem=882)

Dr. One and Dr. Zero are playing the following partisan game.  
The game begins with one $1$, two $2$'s, three $3$'s, ..., $n$ $n$'s. Starting with Dr. One, they make moves in turn.  
Dr. One chooses a number and changes it by removing a $1$ from its binary expansion.  
Dr. Zero chooses a number and changes it by removing a $0$ from its binary expansion.  
The player that is unable to move loses.  
Note that leading zeros are not allowed in any binary expansion; in particular nobody can make a move on the number $0$.

They soon realize that Dr. Zero can never win the game. In order to make it more interesting, Dr. Zero is allowed to "skip the turn" several times, i.e. passing the turn back to Dr. One without making a move.

For example, when $n = 2$, Dr. Zero can win the game if allowed to skip $2$ turns. A sample game:

$$
[1, 2, 2]\xrightarrow{\textrm{Dr. One}}[1, 0, 2]\xrightarrow{\textrm{Dr. Zero}}[1, 0, 1]\xrightarrow{\textrm{Dr. One}}[1, 0, 0]\xrightarrow[\textrm{skip}]{\textrm{Dr. Zero}}
[1, 0, 0]\xrightarrow{\textrm{Dr. One}}[0, 0, 0]\xrightarrow[\textrm{skip}]{\textrm{Dr. Zero}}[0, 0, 0].
$$

Let $S(n)$ be the minimal number of skips needed so that Dr. Zero has a winning strategy.  
For example, $S(2) = 2$, $S(5) = 17$, $S(10) = 64$.

Find $S(10^5)$.

### 882. 移除比特

零博士和壹博士在玩如下不公平游戏：初始时有一个包含 $1$ 个 $1$、$2$ 个 $2$、...、$n$ 个 $n$ 的序列。壹博士是先手，零博士是后手。壹博士每一轮可以任选序列中的一个数，并从其二进制表示中移去一个 $1$；零博士每一轮可以任选序列中的一个数，并从其二进制表示中移去一个 $0$。但是：零博士不能选择 $0$，也不能移除二进制表示中的前导零。第一个不能操作的人输。

但是他们很快发现零博士必败。为了让这游戏更有趣，零博士可以“跳过”某一轮。即，在某一轮中不做任何操作，让壹博士继续操作。例如，$n = 2$ 时，零博士可以通过如下操作，使用 2 次“跳过”获胜：

$$
[1, 2, 2]\xrightarrow{\textrm{壹博士}}[1, 0, 2]\xrightarrow{\textrm{零博士}}[1, 0, 1]\xrightarrow{\textrm{壹博士}}[1, 0, 0]\xrightarrow[\textrm{跳过}]{\textrm{零博士}}
[1, 0, 0]\xrightarrow{\textrm{壹博士}}[0, 0, 0]\xrightarrow[\textrm{跳过}]{\textrm{零博士}}[0, 0, 0].
$$

记 $S(n)$ 为：零博士为了必胜，需要“跳过”的轮数的最小值。已知：$S(2) = 2$、$S(5) = 17$、$S(10) = 64$。

求 $S(10^5)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

