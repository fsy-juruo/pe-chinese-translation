### [824. Chess Sliders](https://pe.xiaoyaowudi.com/problem=824)

A *Slider* is a chess piece that can move one square left or right.

This problem uses a cylindrical chess board where the left hand edge of the board is connected to the right hand edge. This means that a Slider that is on the left hand edge of the chess board can move to the right hand edge of the same row and vice versa.

Let $L(N,K)$ be the number of ways $K$ non-attacking Sliders can be placed on an $N \times N$ cylindrical chess-board.

For example, $L(2,2)=4$ and $L(6,12)=4204761$.

Find $L(10^9,10^{15}) \bmod \left(10^7+19\right)^2$.

### 824. 滑块棋子

我们用一个圆柱形的国际象棋棋盘来玩一个游戏——这也就说明这个棋盘的最左端和最右端是连通的。在游戏时，我们可以让一个 *滑块* 棋子在棋盘上向左或向右移动一格。对于圆柱形棋盘来说，在棋盘最左端的滑块可以移动到最右端同一行上的位置，而反之亦然。

记 $L(N,K)$ 为在 $N \times N$ 的圆柱形的国际象棋棋盘上，放置 $K$ 个互不攻击的滑块的方案数。例如，$L(2,2)=4$ 且 $L(6,12)=4204761$。

求 $L(10^9,10^{15}) \bmod \left(10^7+19\right)^2$。
