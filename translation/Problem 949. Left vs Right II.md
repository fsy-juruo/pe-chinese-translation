### [949. Left vs Right II](https://projecteuler.net/problem=949)

Left and Right play a game with a number of words, each consisting of L's and R's, alternating turns. On Left's turn, **for each word**, Left can remove any number of letters (possibly zero), but not all the letters, from the left side of the word. However, at least one letter must be removed from at least one word. Right does the same on Right's turn except that Right removes letters from the right side of each word. The game continues until each word is reduced to a single letter. If there are more L's than R's remaining then Left wins; otherwise if there are more R's than L's then Right wins. In this problem we only consider games with an odd number of words, thus making ties impossible.

Let $G(n, k)$ be the number of ways of choosing $k$ words of length $n$, for which Right has a winning strategy when Left plays first. Different orderings of the same set of words are to be counted separately.

It can be seen that $G(2, 3)=14$ due to the following solutions (and their reorderings):
$$
\begin{align}
(\texttt{LL},\texttt{RR},\texttt{RR})&:3\text{ orderings}\\
(\texttt{LR},\texttt{LR},\texttt{LR})&:1\text{ ordering}\\
(\texttt{LR},\texttt{LR},\texttt{RR})&:3\text{ orderings}\\
(\texttt{LR},\texttt{RR},\texttt{RR})&:3\text{ orderings}\\
(\texttt{RL},\texttt{RR},\texttt{RR})&:3\text{ orderings}\\
(\texttt{RR},\texttt{RR},\texttt{RR})&:1\text{ ordering}
\end{align}
$$

You are also given $G(4, 3)=496$ and $G(8, 5)=26359197010$.

Find $G(20, 7)$ giving your answer modulo $1001001011$.

### 949. 小左对小右 2

小左和小右正用若干个只含 L、R 的词玩游戏。两人轮流进行操作。轮到小左操作时，**对于每一个词**，小左可以删去这个词左侧任意多个（包括 0 个）字符，但不能把该词删空。但是，小左必须要从至少 1 个词中删去至少 1 个字符。小右在他的轮次中，也进行相同的操作，只不过他只能删去一个词右侧若干个（包括 0 个）字符。当每个词都只剩一个字符时，游戏结束。如果 L 的数量多于 R 的数量，则小左获胜；如果 R 的数量多于 L 的数量，则小右获胜。本题中，我们只考虑有奇数个词的情况，所以该游戏不存在平局。

记 $G(n, k)$ 为：选出 $k$ 个长度为 $n$ 的 LR 串，使得小左先手时，小右有必胜策略的方案数。本题中，同一个 LR 串集合的不同的重排须计算多次。

下述合法的选择方案（以及它们的重排）表明 $G(2, 3)=14$：

$$
\begin{align}
(\texttt{LL},\texttt{RR},\texttt{RR})&:3\text{ 个不同重排}\\
(\texttt{LR},\texttt{LR},\texttt{LR})&:1\text{ 个不同重排}\\
(\texttt{LR},\texttt{LR},\texttt{RR})&:3\text{ 个不同重排}\\
(\texttt{LR},\texttt{RR},\texttt{RR})&:3\text{ 个不同重排}\\
(\texttt{RL},\texttt{RR},\texttt{RR})&:3\text{ 个不同重排}\\
(\texttt{RR},\texttt{RR},\texttt{RR})&:1\text{ 个不同重排}
\end{align}
$$

亦已知 $G(4, 3)=496$、$G(8, 5)=26359197010$。

求 $G(20, 7)$ 模 $1001001011$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。