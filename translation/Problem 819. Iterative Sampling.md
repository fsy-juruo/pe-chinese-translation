### [819. Iterative Sampling](https://projecteuler.net/problem=819)

Given an $n$-tuple of numbers another $n$-tuple is created where each element of the new $n$-tuple is chosen randomly from the numbers in the previous $n$-tuple. For example, given $(2,2,3)$ the probability that $2$ occurs in the first position in the next 3-tuple is $2/3$. The probability of getting all $2$'s would be $8/27$ while the probability of getting the same 3-tuple (in any order) would be $4/9$.

Let $E(n)$ be the expected number of steps starting with $(1,2,\ldots,n)$ and ending with all numbers being the same.

You are given $E(3) = 27/7$ and $E(5) = 468125/60701 \approx 7.711982$ rounded to 6 digits after the decimal place.

Find $E(10^3)$. Give the answer rounded to 6 digits after the decimal place.

### 819. 迭代取样法

给定一组初始的 $n$ 元集，随后我们利用它再生成一个新的 $n$ 元集。新的 $n$ 元集中的每一个元素都是从先前的 $n$ 元集中等概率随机选择的。例如：给定初始三元集 $(2,2,3)$，则下一个集合中，在第一个位置出现 $2$ 的概率就是 $2/3$、生成全 $2$ 三元集的概率是 $8/27$ 而再次生成 $(2,2,3)$ 的概率是 $4/9$。

给定初始 $n$ 元集 $(1,2,\ldots,n)$，其经若干次上述操作后重新变回初始的 $n$ 元集。我们记 $E(n)$ 为这操作次数的期望。你已知 $E(3) = 27/7$ 且 $E(5) = 468125/60701 \approx 7.711982$（四舍五入至小数点后第 6 位）。

求 $E(10^3)$。将你的答案四舍五入至小数点后第 6 位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。