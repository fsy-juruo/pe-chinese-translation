### [709. Even Stevens](https://projecteuler.net/problem=709)

Every day for the past $n$ days Even Stevens brings home his groceries in a plastic bag. He stores these plastic bags in a cupboard. He either puts the plastic bag into the cupboard with the rest, or else he takes an **even** number of the existing bags (which may either be empty or previously filled with other bags themselves) and places these into the current bag.

After 4 days there are 5 possible packings and if the bags are numbered 1 (oldest), 2, 3, 4, they are:

- Four empty bags,
- 1 and 2 inside 3, 4 empty,
- 1 and 3 inside 4, 2 empty,
- 1 and 2 inside 4, 3 empty,
- 2 and 3 inside 4, 1 empty.

Note that 1, 2, 3 inside 4 is invalid because every bag must contain an even number of bags.

Define $f(n)$ to be the number of possible packings of $n$ bags. Hence $f(4)=5$. You are also given $f(8)=1\,385$.

Find $f(24\,680)$ giving your answer modulo $1\,020\,202\,009$.

### 709. 伊文·史蒂芬斯 [^1]

过去 $n$ 天里，伊文·史蒂芬斯都会提着塑料袋把买的杂货提回家。他把用过的塑料袋存放在碗柜中。他每次要么把新塑料袋直接放入碗柜，与已有塑料袋并列；要么从碗柜中取出 **偶数** 个塑料袋（这些袋子可以是空的，也可以已装有其他袋子），将它们装入当天的新塑料袋中，再一并放回碗柜。

四天之后，若将塑料袋按使用时间先后标为 $1$ 至 $4$，那么碗柜里的塑料袋共有 $5$ 种嵌套方式，分别是：

- 四个均是空的塑料袋；
- $3$ 号塑料袋中装有 $1$、$2$ 号袋，$4$ 号塑料袋为空；
- $4$ 号塑料袋中装有 $1$、$2$ 号袋，$3$ 号塑料袋为空；
- $4$ 号塑料袋中装有 $1$、$3$ 号袋，$2$ 号塑料袋为空；
- $4$ 号塑料袋中装有 $2$、$3$ 号袋，$1$ 号塑料袋为空；

注意：$4$ 号塑料袋中装有 $1$、$2$、$3$ 号袋这种情况是非法的，因为每个塑料袋中只能装有偶数个袋子。

记 $f(n)$ 为 $n$ 天后碗柜里的塑料袋的不同嵌套方式数，则有 $f(4)=5$。亦已知 $f(8)=1\,385$。

求 $f(24\,680)$ 模 $1\,020\,202\,009$ 的值。

[^1]: even steven (even stephen) 是美式英语中的俚语，意指「（两队的比分、分出的两堆等）相同的；平分秋色的；互不欠债的；机会均等的」。此处主要是玩了一个 even 的双关。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
