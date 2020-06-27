### [696. Mahjong](https://projecteuler.net/problem=696)

The game of Mahjong is played with tiles belonging to $s$ *suits*. Each tile also has a *number* in the range $1\ldots n$, and for each suit/number combination there are exactly four indistinguishable tiles with that suit and number. (The real Mahjong game also contains other bonus tiles, but those will not feature in this problem.)

A *winning hand* is a collection of $3t+2$ Tiles (where $t$ is a fixed integer) that can be arranged as $t$ *Triples* and one *Pair*, where:

- A *Triple* is either a *Chow* or a *Pung*
- A *Chow* is three tiles of the same suit and consecutive numbers
- A *Pung* is three identical tiles (same suit and same number)
- A *Pair* is two identical tiles (same suit and same number)

For example, here is a winning hand with $n=9$, $s=3$, $t=4$, consisting in this case of two Chows, two Pungs, and one Pair:

![](https://projecteuler.net/project/images/p696_mahjong_1.png)

Note that sometimes the same collection of tiles can be represented as $t$ Triples and one Pair in more than one way. This only counts as one winning hand. For example, this is considered to be the same winning hand as above, because it consists of the same tiles:

![](https://projecteuler.net/project/images/p696_mahjong_2.png)

Let $w(n, s, t)$ be the number of distinct winning hands formed of $t$ Triples and one Pair, where there are $s$ suits available and tiles are numbered up to $n$.

For example, with a single suit and tiles numbered up to 4, we have $w(4, 1, 1) = 20$: there are 12 winning hands consisting of a Pung and a Pair, and another 8 containing a Chow and a Pair. You are also given that $w(9, 1, 4) = 13259$, $w(9, 3, 4) = 5237550$, and $w(1000, 1000, 5) \equiv 107662178 \pmod{1\,000\,000\,007}$.

Find $w(10^8, 10^8, 30)$. Give your answer modulo $1\,000\,000\,007$.

### 696. 麻将

麻将游戏的牌共有 $s$ 种*花色*，每一张牌上都有 $1...n$ 范围内的一个数字，称为*点数*。对于任意花色-点数的组合，都有恰好四张完全相同的牌。（原本的麻将游戏中有奖励牌，但是在这道题里面，就装作它不存在吧）

当玩家拥有了一副由 $3t+2$ 张牌的牌组，且这个牌组能被整理为 $t$ 个*三对子*与一个*杠*，玩家就可以*胡牌*。其中定义：

- *三对子*要么是一*吃*，要么是一*碰*。
- 三张点数连续，花色相同的牌称作一*吃*
- 三张点数相同，花色相同的牌称作一*碰*
- 两张点数相同，花色相同的牌称作一*杠*

下图的牌组满足 $n=9$，$s=3$，$t=4$，且能胡牌。（由两吃，两碰，一杠组成）

![](https://projecteuler.net/project/images/p696_mahjong_1.png)

注意到有时候相同的一副牌可以通过不同的方式被整理为 $t$ 个三对子与一个杠，重复的牌组只计一次。下图的牌组也能胡牌，但由于与上图中的牌完全一致，所以被认为与上图重复：

![](https://projecteuler.net/project/images/p696_mahjong_2.png)

令 $w(n, s, t)$ 为由 $t$ 个三对子与一杠组成的，有 $s$ 个可用花色，最大点数为 $n$ 的可以胡牌的不同的牌组数。

比如 $w(4, 1, 1) = 20$：有 12 个由一碰，一杠组成的可胡牌的牌组，8 个由一吃，一杠组成的可胡牌的牌组。已知 $w(9, 1, 4) = 13259$，$w(9, 3, 4) = 5237550$ 且 $w(1000, 1000, 5) \equiv 107662178 \pmod{1\,000\,000\,007}$。

求 $w(10^8, 10^8, 30)$ 模 $1\,000\,000\,007$。