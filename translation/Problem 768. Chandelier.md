### [768. Chandelier](https://projecteuler.net/problem=768)

A certain type of chandelier contains a circular ring of $n$ evenly spaced candleholders.  
If only one candle is fitted, then the chandelier will be imbalanced. However, if a second identical candle is placed in the opposite candleholder (assuming $n$ is even) then perfect balance will be achieved and the chandelier will hang level.

Let $f(n,m)$ be the number of ways of arranging $m$ identical candles in distinct sockets of a chandelier with $n$ candleholders such that the chandelier is perfectly balanced.

For example, $f(4, 2) = 2$: assuming the chandelier's four candleholders are aligned with the compass points, the two valid arrangements are "North & South" and "East & West". Note that these are considered to be different arrangements even though they are related by rotation.

You are given that $f(12,4) = 15$ and $f(36, 6) = 876$.

Find $f(360, 20)$.

### 768. 吊灯[^1]

某枝形吊灯上均匀分布了 $n$ 盏烛台。如果只放置 1 根蜡烛，这吊灯必定受力不平衡；但是 $n$ 为偶数时，只要把 2 根蜡烛分别放在两个在环状吊灯上相对的烛台中时，吊灯就受力平衡了。

记 $f(n, m)$ 为在某含有 $n$ 盏烛台的环形吊灯中放置 $m$ 根完全一样的蜡烛，且能使吊灯受力平衡的方案数。

例如 $f(4, 2)$ 为 2：将吊灯的 4 盏烛台与指南针的 4 个方向对齐，那么这两根蜡烛可以放在代表南、北，或者代表东、西的烛台中。虽然这两种摆放方式在旋转后是一致的，但在本题中我们认为这两种方案是不同的。

已知 $f(12, 4) = 15$、$f(36, 6) = 876$。

求 $f(360, 20)$。

---

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/) 回到源站。

点 [这个链接](https://fsy-juruo.github.io/pe-chinese-translation/detailed_content_archives.html) 回到详细版题目目录。

[^1]: chandelier: a branched often ornate lighting fixture suspended from a ceiling。韦氏词典对此给出了配图，可前往[链接](https://www.merriam-webster.com/dictionary/chandelier#art-1)查看。