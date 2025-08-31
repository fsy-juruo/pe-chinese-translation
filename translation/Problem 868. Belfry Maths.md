### [868. Belfry Maths](https://projecteuler.net/problem=868)

There is a method that is used by Bell ringers to generate all variations of the order that bells are rung.

The same method can be used to create all permutations of a set of letters. Consider the letters to be permuted initially in order from smallest to largest. At each step swap the largest letter with the letter on its left or right whichever generates a permutation that has not yet been seen. If neither gives a new permutation then try the next largest letter and so on. This procedure continues until all permutations have been generated.

For example, $3$ swaps are required to reach the permutation CBA when starting with ABC.  
The swaps are ABC $\to$ ACB $\to$ CAB $\to$ CBA.  
Also $59$ swaps are required to reach BELFRY when starting with these letters in alphabetical order.

Find the number of swaps that are required to reach NOWPICKBELFRYMATHS when starting with these letters in alphabetical order.

### 868. 钟塔中的数学

鸣钟者有一种特别的方法，用于生成所有敲钟的顺序。而该方法亦可用于生成某字母集合的所有排列：

现有若干字母，初始时它们按字典序从小到大排列。在接下来的每一步中，字典序最大的字母会尝试和它相邻的两个字符交换位置，以生成新的排列。如果无法生成新的排列，我们就尝试让字典序第二大的字母和它相邻的两个字符交换位置，以此类推。当所有排列都已被生成时，停止如上过程。

例如，通过如上算法通过 ABC 得到 CBA 需要 $3$ 次交换，交换过程为：ABC $\to$ ACB $\to$ CAB $\to$ CBA。  
另外，从 BEFLRY 得到 BELFRY 需要 $59$ 次交换。

求：从字母按从小到大排列的初始状态，得到 NOWPICKBELFRYMATHS，需要多少次交换？

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。