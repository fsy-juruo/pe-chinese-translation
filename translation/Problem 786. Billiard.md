### [786. Billiard](https://projecteuler.net/problem=786)

The following diagram shows a billiard table of a special quadrilateral shape.
The four angles $A, B, C, D$ are $120^\circ, 90^\circ, 60^\circ, 90^\circ$ respectively, and the lengths $AB$ and $AD$ are equal.

![](https://pe.xiaoyaowudi.com/project/images/p786_billiard_shape.jpg)

The diagram on the left shows the trace of an infinitesimally small billiard ball, departing from point $A$, bouncing twice on the edges of the table, and finally returning back to point $A$. The diagram on the right shows another such trace, but this time bouncing eight times:

![](https://pe.xiaoyaowudi.com/project/images/p786_billiard_traces.jpg)

The table has no friction and all bounces are perfect elastic collisions.
Note that no bounce should happen on any of the corners, as the behaviour would be unpredictable.

Let $B(N)$ be the number of possible traces of the ball, departing from point $A$, bouncing at most $N$ times on the edges and returning back to point $A$.

For example, $B(10) = 6$, $B(100) = 478$, $B(1000) = 45790$.

Find $B(10^9)$.

### 786. 台球桌

下图是一个四边形台球桌。它的形状比较特殊，其四个内角 $A, B, C, D$ 分别为 $120^\circ, 90^\circ, 60^\circ, 90^\circ$，且 $AB = AD$。

![](https://pe.xiaoyaowudi.com/project/images/p786_billiard_shape.jpg)

左图是某无限小的台球，从 $A$ 点出发，被台球桌边界反弹两次后回到 $A$ 点的轨迹。而右图同样是某无限小的台球从 $A$ 点出发在台球桌上弹射的轨迹，但这一次它反弹了八次才回到 $A$ 点。

![](https://pe.xiaoyaowudi.com/project/images/p786_billiard_traces.jpg)

我们忽略台球桌的摩擦，并认为一切碰撞皆为弹性碰撞。注意，碰撞不能发生在顶点处，不然台球的轨迹就很难预测了。

记 $B(N)$ 为某无限小台球从 $A$ 点出发，被台球桌边界反弹至多 $N$ 次后刚好回到 $A$ 点的可能轨迹数量。已知 $B(10) = 6$、$B(100) = 478$、$B(1000) = 45790$。

求 $B(10^9)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。