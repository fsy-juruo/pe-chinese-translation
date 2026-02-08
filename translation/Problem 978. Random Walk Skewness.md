### [978. Random Walk Skewness](https://projecteuler.net/problem=978)

In this problem we consider a **random walk** on the integers $\mathbb{Z}$, in which our position at time $t$ is denoted as $X_t$.

At time $0$ we start at position $0$. That is, $X_0=0$.  
At time $1$ we jump to position $1$. That is, $X_1=1$.  
Thereafter, at time $t=2,3,\dots$ we make a jump of size $|X_{t-2}|$ in either the positive or negative direction, with probability $1/2$ each way. If $X_{t-2}=0$ we stay put at time $t$.

At $t=5$ we find our position $X_5$ has the following distribution:

$$
X_5 =
\begin{cases}
-1 \quad & \text{with probability } 3/8 \\
1 \quad & \text{with probability } 3/8 \\
3 \quad & \text{with probability } 1/8 \\
5 \quad & \text{with probability } 1/8 \\
\end{cases}
$$

The **standard deviation** $\sigma$ of a **random variable** $X$ with **mean** $\mu$ is defined as
$$
\sigma=\sqrt{\mathbb{E}[X^2]-\mu^2}
$$
Furthermore the **skewness** of $X$ is defined as
$$
\text{Skew}(X)=\mathbb{E}\biggl[\Bigl(\frac{X-\mu}{\sigma}\Bigr)^3\biggr]
$$
For $X_5$, which has mean $1$ and standard deviation $2$, we find $\text{Skew}(X_5)=0.75$. You are also given $\text{Skew}(X_{10})\approx2.50997097$.

Find $\text{Skew}(X_{50})$. Give your answer rounded to eight digits after the decimal point.

### 978. 随机游走的偏度

本题中，我们考虑整数集 $\mathbb{Z}$ 上的 **随机游走**，并把第 $t$ 时刻所在位置记为 $X_t$。

第 $0$ 时刻，我们在 $0$ 处开始游走，也就是说 $X_0=0$。  
第 $1$ 时刻，我们游走至 $1$ 处，也就是说 $X_1=1$。
此后，在时刻 $t=2,3,\dots$，我们各以 $1/2$ 的概率，向数轴的负方向或者正方向游走 $|X_{t-2}|$ 步。若 $X_{t-2}=0$，则我们在该时刻保持不动。

$t=5$ 时，$X_5$ 的概率分布如下：

$$
X_5 =
\begin{cases}
-1 \quad & \text{with probability } 3/8 \\
1 \quad & \text{with probability } 3/8 \\
3 \quad & \text{with probability } 1/8 \\
5 \quad & \text{with probability } 1/8 \\
\end{cases}
$$

我们定义 **均值** 为 $\mu$ 的 **随机变量** $X$ 的 **标准差** $\sigma$ 为：
$$
\sigma=\sqrt{\mathbb{E}[X^2]-\mu^2}
$$

并进一步定义 $X$ 的 **偏度** 为：

$$
\text{Skew}(X)=\mathbb{E}\biggl[\Bigl(\frac{X-\mu}{\sigma}\Bigr)^3\biggr]
$$

对于 $X_5$，其均值为 $1$、标准差为 $2$，容易算得 $\text{Skew}(X_5)=0.75$。亦已知 $\text{Skew}(X_{10})\approx2.50997097$。

求 $\text{Skew}(X_{50})$，把答案四舍五入至小数点后第八位。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。