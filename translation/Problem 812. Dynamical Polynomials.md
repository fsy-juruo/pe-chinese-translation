### [812. Dynamical Polynomials](https://projecteuler.net/problem=812)

A *dynamical polynomial* is a **monic** polynomial $f(x)$ with integer coefficients such that $f(x)$ divides $f(x^2-2)$.

For example, $f(x) = x^2 - x - 2$ is a dynamical polynomial because $f(x^2-2) = x^4-5x^2+4 = (x^2 + x -2)f(x)$.

Let $S(n)$ be the number of dynamical polynomials of degree $n$.
For example, $S(2)=6$, as there are six dynamical polynomials of degree 2:
$$
x^2-4x+4 \quad,\quad x^2-x-2 \quad,\quad x^2-4 \quad,\quad x^2-1 \quad,\quad x^2+x-1 \quad,\quad x^2+2x+1
$$
Also, $S(5)=58$ and $S(20)=122087$.

Find $S(10\,000)$. Give your answer modulo $998244353$.

### 812. 壮悍多项式

若某整系数首 1 多项式 $f(x)$ 满足 $f(x)$ 整除 $f(x^2-2)$，则称其为*壮悍多项式*。

例如，$f(x) = x^2 - x - 2$ 是壮悍多项式，因为 $f(x^2-2) = x^4-5x^2+4 = (x^2 + x -2)f(x)$。

记 $S(n)$ 为度数为 $n$ 的壮悍多项式的个数。例如，有 6 个度数为 2 的壮悍多项式，故 $S(2)=6$：
$$
x^2-4x+4 \quad,\quad x^2-x-2 \quad,\quad x^2-4 \quad,\quad x^2-1 \quad,\quad x^2+x-1 \quad,\quad x^2+2x+1
$$

同理亦有 $S(5)=58$ 且 $S(20)=122087$。

求 $S(10\,000)$ 模 $998244353$ 之值。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。