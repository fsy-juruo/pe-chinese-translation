### [862. Larger Digit Permutation](https://pe.xiaoyaowudi.com/problem=862)

For a positive integer $n$ define $T(n)$ to be the number of strictly larger integers which can be formed by permuting the digits of $n$.

Leading zeros are not allowed and so for $n = 2302$ the total list of permutations would be:

$$
2023,2032,2203,2230,\mathbf{2302},2320,3022,3202,3220
$$

giving $T(2302)=4$.

Further define $S(k)$ to be the sum of $T(n)$ for all $k$-digit numbers $n$. You are given $S(3) = 1701$.

Find $S(12)$.

### 862. 更大的数位排列数

对某正整数 $n$，我们记 $T(n)$ 为：通过排列 $n$ 的数位，可以得到的严格大于 $n$ 的数的个数。排列数位时，不允许前导零。所以对 $n = 2302$，所有可以通过排列 $n$ 的数位得到的数有：

$$
2023,2032,2203,2230,\mathbf{2302},2320,3022,3202,3220
$$

故 $T(2302) = 4$。

再记 $S(k)$ 为全体 $k$ 位十进制数 $n$ 的 $T(n)$ 之和。已知 $S(3) = 1701$。

求 $S(12)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。
