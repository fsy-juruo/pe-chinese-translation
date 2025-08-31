### [866. Tidying Up B](https://projecteuler.net/problem=866)

A small child has a “number caterpillar” consisting of $N$ jigsaw pieces, each with one number on it, which, when connected together in a line, reveal the numbers $1$ to $N$ in order.

Every night, the child's father has to pick up the pieces of the caterpillar that have been scattered across the play room. He picks up the pieces at random and places them in the correct order.  
As the caterpillar is built up in this way, it forms distinct segments that gradually merge together.

Any time the father places a new piece in its correct position, a segment of length $k$ is formed and he writes down the $k$^th^ hexagonal number $k\cdot(2k-1)$. Once all pieces have been placed and the full caterpillar constructed he calculates the product of all the numbers written down. Interestingly, the expected value of this product is always an integer. For example if $N=4$ then the expected value is $994$.

Find the expected value of the product for a caterpillar of $N=100$ pieces.
Give your answer modulo $987654319$.

### 866. 收拾拼图 2 [^1]

一个小朋友有一副由 $N$ 块拼图组成的 “数字毛毛虫” 玩具，每块拼图上都标有一个数字。这些拼图按正确顺序连成一条线后，会按顺序显现出 $1$ 至 $N$ 中的数字。

[^1]: 收拾拼图 1 见 [253 题](https://fsy-juruo.github.io/pe-chinese-translation/problems/253.html)。如果对下文连续段的形成、合并过程有疑惑，可参见该题的例子和注释。

每天晚上，小朋友的父亲须把散落于游戏室中的拼图收拾好。他会不断完全随机的捡起一片拼图，将其放到正确的位置上，直到所有拼图全部归位。  
上述过程中，已归位的拼图会形成若干不相连的连续段，而后逐渐被合并，最终形成一条完整的毛毛虫。  

父亲每归位一块拼图，就会记住该拼图所在的连续段的长度 $k$，并写下第 $k$ 个六边形数 $k \cdot (2k - 1)$。当所有拼图都已归位，形成完整的毛毛虫后，父亲会算出写下的所有数的乘积。有趣的是，这个乘积的期望永远是一个整数。例如，$N = 4$ 时，这个期望值是 $994$。

若 $N = 100$，求此乘积的期望模 $987654319$ 的值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。