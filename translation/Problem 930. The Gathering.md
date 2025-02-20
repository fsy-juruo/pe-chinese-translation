### [930. The Gathering](https://projecteuler.net/problem=930)

Given $n\ge 2$ bowls arranged in a circle, $m\ge 2$ balls are distributed amongst them.

Initially the balls are distributed randomly: for each ball, a bowl is chosen equiprobably and independently of the other balls. After this is done, we start the following process:

- Choose one of the $m$ balls equiprobably at random.
- Choose a direction to move - either clockwise or anticlockwise - again equiprobably at random.
- Move the chosen ball to the neighbouring bowl in the chosen direction.
- Return to step 1.

This process stops when all the $m$ balls are located in the same bowl. Note that this may be after zero steps, if the balls happen to have been initially distributed all in the same bowl.

Let $F(n, m)$ be the expected number of times we move a ball before the process stops. For example, $F(2, 2) = \frac{1}{2}$, $F(3, 2) = \frac{4}{3}$, $F(2, 3) = \frac{9}{4}$, and $F(4, 5) = \frac{6875}{24}$.

Let $G(N, M) = \sum_{n=2}^N \sum_{m=2}^M F(n, m)$. For example, $G(3, 3) = \frac{137}{12}$ and $G(4, 5) = \frac{6277}{12}$. You are also given that $G(6, 6) \approx 1.681521567954e4$ in scientific format with 12 significant digits after the decimal point.

Find $G(12, 12)$. Give your answer in scientific format with 12 significant digits after the decimal point.

### 930. 小球集聚

现有 $n \geq 2$ 只碗排成一圈，有 $m \ge 2$ 个球等待被放入碗中。

初始时，我们将为每个球等概率地选择一个碗，并将其放入该碗，选碗过程对于每个球相互独立。之后开始执行如下过程：

- 等概率地在 $m$ 个球中选择一个。
- 在顺时针、逆时针中等概率选择一个移动方向。
- 将该球按所选方向移动到旁边的碗中。
- 返回第一步。

若 $m$ 个球都在同一个碗中，则此过程停止。如果一开始这 $m$ 个球就在同一个碗中，那么该过程无需进行，移球次数为 $0$。

令 $F(n, m)$ 为过程停止时，移动球次数的期望值。已知：$F(2, 2) = \frac{1}{2}$、$F(3, 2) = \frac{4}{3}$、$F(2, 3) = \frac{9}{4}$、$F(4, 5) = \frac{6875}{24}$。

再令 $G(N, M) = \sum_{n=2}^N \sum_{m=2}^M F(n, m)$。已知 $G(3, 3) = \frac{137}{12}$、$G(4, 5) = \frac{6277}{12}$。且 $G(6, 6)$ 用科学记数法表示，并在小数点后保留 $12$ 位有效数字的结果为 $1.681521567954e4$。

求 $G(12, 12)$。将你的答案用科学记数法表示，并在小数点后保留 $12$ 位有效数字。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

