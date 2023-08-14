### [775. Saving Paper](https://projecteuler.net/problem=775)

When wrapping several cubes in paper, it is more efficient to wrap them all together than to wrap each one individually. For example, with 10 cubes of unit edge length, it would take 30 units of paper to wrap them in the arrangement shown below, but 60 units to wrap them separately.

![](https://pe.xiaoyaowudi.com/project/images/p775_wrapping_cubes.png)


Define $g(n)$ to be the maximum amount of paper that can be saved by wrapping $n$ identical $1\times 1\times 1$ cubes in a compact arrangement, compared with wrapping them individually. We insist that the wrapping paper is in contact with the cubes at all points, without leaving a void.

With 10 cubes, the arrangement illustrated above is optimal, so $g(10)=60-30=30$. With 18 cubes, it can be shown that the optimal arrangement is as a $3\times 3\times 2$, using 42 units of paper, whereas wrapping individually would use 108 units of paper; hence $g(18) = 66$.

Define
$$
G(N) = \sum_{n=1}^N g(n)
$$
You are given that $G(18) = 530$, and $G(10^6) \equiv 951640919 \pmod {1\,000\,000\,007}$.

Find $G(10^{16})$. Give your answer modulo $1\,000\,000\,007$.

### 775. 省纸

用纸包裹一些正方体时，相较于单独用纸包裹它们，把正方体叠放在一起后用纸包裹它们更加省纸。如下图中有 10 个叠放在一起的单位正方体，包裹它们需要 30 单位面积的纸，而单独包裹则需 60 单位的纸。

![](https://pe.xiaoyaowudi.com/project/images/p775_wrapping_cubes.png)

记 $g(n)$ 为通过叠放 $n$ 个单位正方体后用纸包裹它们最多可以省去的纸的面积。注意，包裹时，我们要求纸与正方体完全叠合，也就是说，不能存在一部分纸，使得其不与任何一个正方体接触。

有 10 个单位正方体时，上图的方案是最优的，显然 $g(10) = 30$。有 18 个单位正方体时，最优的方式为将它们叠放为一个 $3\times 3\times 2$ 的大长方体，这只需耗费 42 单位面积的纸；而单独包裹需要 108 单位面积的纸，故 $g(18) = 66$。

记
$$
G(N) = \sum_{n=1}^N g(n)
$$

已知 $G(18) = 530$ 且 $G(10^6) \equiv 951640919 \pmod {1\,000\,000\,007}$。

求 $G(10^{16})$ 模 $1\,000\,000\,007$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。