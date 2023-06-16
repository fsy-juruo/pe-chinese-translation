### [721. High powers of irrational numbers](https://projecteuler.net/problem=721)

Given is the function $f(a,n)=\lfloor{(\lceil{\sqrt{a}\:\rceil}+\sqrt{a}\:)^n}\rfloor$.

$\lfloor{.}\rfloor$ denotes the floor function and $\lceil{.}\rceil$ denotes the ceiling function.

$f(5,2)=27$ and $f(5,5)=3935$.

$G(n) = \displaystyle \sum_{a=1}^n f(a, a^2).$

$G(1000) \text{ mod  } 999\,999\,937=163861845. $

Find $G(5\,000\,000).$ Give your answer modulo $999\,999\,937$

### 721. 无理数的高次幂

记函数 $f(a,n)=\lfloor{(\lceil{\sqrt{a}\:\rceil}+\sqrt{a}\:)^n}\rfloor$，其中 $\lfloor{.}\rfloor$ 表示下取整函数，$\lceil{.}\rceil$ 表示上取整函数。已知：$f(5,2)=27$ 且 $f(5,5)=3935$。

记 $G(n) = \displaystyle \sum_{a=1}^n f(a, a^2)$，已知：$G(1000) \text{ mod  } 999\,999\,937=163861845$。

求 $G(5\,000\,000)$ 模 $999\,999\,937$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。