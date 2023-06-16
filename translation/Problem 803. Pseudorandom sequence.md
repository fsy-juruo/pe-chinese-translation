### [803. Pseudorandom sequence](https://projecteuler.net/problem=803)

**Rand48** is a pseudorandom number generator used by some programming languages. It generates a sequence from any given integer $0 \le a_0 < 2^{48}$ using the rule $a_n = (25214903917 \cdot a_{n - 1} + 11) \bmod 2^{48}$.

Let $b_n = \lfloor a_n / 2^{16} \rfloor \bmod 52$.
The sequence $b_0, b_1, \dots$ is translated to an infinite string $c = c_0c_1\dots$ via the rule:
$0 \rightarrow$ a, $1\rightarrow$ b, $\dots$, $25 \rightarrow$ z, $26 \rightarrow$ A, $27 \rightarrow$ B, $\dots$, $51 \rightarrow$ Z.

For example, if we choose $a_0 = 123456$, then the string $c$ starts with: "bQYicNGCY$\dots$".
Moreover, starting from index $100$, we encounter the substring "RxqLBfWzv" for the first time.

Alternatively, if $c$ starts with "EULERcats$\dots$", then $a_0$ must be $78580612777175$.

Now suppose that the string $c$ starts with "PuzzleOne$\dots$".
Find the starting index of the first occurrence of the substring "LuckyText" in $c$.

### 803. 伪随机序列

某些编程语言会使用 **Rand48** 这种伪随机数生成器。给定整数 $0 \le a_0 < 2^{48}$，Rand48 通过 $a_n = (25214903917 \cdot a_{n - 1} + 11) \bmod 2^{48}$ 这个递推关系生成一个序列。

令 $b_n = \lfloor a_n / 2^{16} \rfloor \bmod 52$。我们通过如下规则将无限长数列 $\{b_0, b_1, \dots \}$ 转换成无限长字符串 $c = c_0c_1\dots$：$0 \rightarrow$ a，$1\rightarrow$ b，$\dots$，$25 \rightarrow$ z，$26 \rightarrow$ A，$27 \rightarrow$ B，$\dots$，$51 \rightarrow$ Z。

例如，我们取 $a_0 = 123456$，则字符串 $c$ 的前几位是 "bQYicNGCY$\dots$"。在 $c$ 下标为 100 的位置第一次出现子串 "RxqLBfWzv"。
同样，如果 $c$ 的前几位是 "EULERcats$\dots$"，可以验证 $a_0$ 只能是 $78580612777175$。

现在，我们假设 $c$ 以 "PuzzleOne$\dots$" 开头，求：$c$ 中第一次出现子串 "LuckyText" 的起始位的下标。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。