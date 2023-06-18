###  [770. Delphi Flip](https://projecteuler.net/problem=770)

A and B play a game. A has originally $1$ gram of gold and B has an unlimited amount.
Each round goes as follows:

* A chooses and displays, $x$, a nonnegative real number no larger than the amount of gold that A has.
* Either B chooses to TAKE. Then A gives B $x$ grams of gold.
* Or B chooses to GIVE. Then B gives A $x$ grams of gold.

B TAKEs $n$ times and GIVEs $n$ times after which the game finishes.

Define $g(X)$ to be the smallest value of $n$ so that A can guarantee to have at least $X$ grams of gold at the end of the game. You are given $g(1.7) = 10$.

Find $g(1.9999)$.

### 770. 德尔斐赌徒谜题 [^1] [^2]

A、B 两人在玩一个游戏。游戏开始时，A 持有 $1$ 克黄金而 B 持有无限量的黄金。游戏每一轮的流程如下：

* A 选择一个非负实数 $x$ 并向 B 展示。$x$ 需要不大于 A 目前持有黄金的克数。
* B 要么选择*拿取*，让 A 给他 $x$ 克黄金；要么选择*给予*，则他会给 A $x$ 克黄金。

在 B 恰好进行了 $n$ 次*拿取*和 $n$ 次*给予*后，游戏结束。

记 $g(X)$ 为满足以下条件的最小的 $n$：不论 B 如何操作，在游戏结束时，A 都可以保证至少持有 $X$ 克黄金。已知：$g(1.7) = 10$。

求 $g(1.9999)$。

[^1]: 本题取自 Dennis E. Shasha 于 2001 年 8 月投稿在《科学美国人（*Scientific American*）》上的[同名题目](https://www.scientificamerican.com/article/the-delphi-flip/)。由于某些原因，我们在这里借用 R. T. Koether 和 John K. Osoinach, JR. 的[《*Outwitting the Lying Oracle*》](https://www.maa.org/sites/default/files/pdf/upload_library/22/Allendoerfer/koether98.pdf)对该谜题的描述：「神抛掷三次硬币，赌徒赌硬币落地一面的正反。神知道、并且也会告诉赌徒每一次硬币落下时落地一面的正反。但神在这三轮中会至多说一次谎。而赌徒也必须告诉神他每轮的赌注。试找到赌徒的最优策略。」

[^2]: 考虑到本题的背景是赌黄金的克数，所以译作「德尔斐赌徒谜题」，而非字面意义上的「德尔斐抛硬币谜题」。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。