# 兼得鱼与熊掌的保障，带来更公平的结果

发布时间：2025年07月21日

`其他` `公平分配` `博弈论`

> Best-of-Both-Worlds Guarantees with Fairer Endings

# 摘要

> 不可分物品的公平分配是经济学与计算机科学交叉领域中的一个基本问题。传统方法要么关注基于期望公平的随机分配，要么关注近似公平的确定性分配。近期研究通过“双优”保证将这两种方法统一起来，即寻求一种随机分配，它在事前是公平的（ex-ante公平），同时在事后又基于近似公平的分配（ex-post公平）。已有研究表明，在加法偏好下，总存在一种随机分配，它在事前是sd-EF的，事后则是EF1的。

我们的研究旨在实现更强的事后公平保证，例如“任意物品上的 envy-freeness”（EFX），同时保持有意义的事前保证。我们做出了以下贡献：
1) 我们首先考虑字典序偏好，这是加法偏好下的一个子领域，其中事后EFX分配总存在且可高效计算。消极方面，我们发现事前sd-EF与事后EFX从根本上是不兼容的，这促使我们放松了事前基准。然后，我们提出了一种多项式时间算法，该算法同时实现事后EFX和PO，以及事前9/10-EF。我们的算法采用相关轮换，并利用EFX和PO分配的结构特性。
2) 对于单调偏好，我们研究了EFX-with-charity，这是EFX的一种放松，其中某些物品未被分配，且无代理羡慕未分配的物品池。我们证明，事后EFX-with-charity可与事前0.5-EF同时实现。
3) 最后，对于次加性偏好，我们将事后的保证加强到EFX-with-bounded-charity，其中最多n-1件物品（n=代理数）未被分配，代价是将事前保证减弱到0.5-proportionality。


> Fair allocation of indivisible goods is a fundamental problem at the interface of economics and computer science. Traditional approaches focus either on randomized allocations that are fair in expectation or deterministic allocations that are approximately fair. Recent work reconciles both these approaches via best-of-both-worlds guarantees, wherein one seeks randomized allocations that are fair in expectation (ex-ante fair) while being supported on approximately fair allocations (ex-post fair). Prior work has shown that under additive valuations, there always exists a randomized allocation that is ex-ante stochastic-dominance envy-free (sd-EF) and ex-post envy-free up to one good (EF1).
  Our work is motivated by the goal of achieving stronger ex-post fairness guarantees such as envy-freeness up to any good (EFX) along with meaningful ex-ante guarantees. We make the following contributions:
  1) We first consider lexicographic preferences, a subdomain of additive valuations where ex-post EFX allocations always exist and can be computed efficiently. On the negative side, we show that ex-ante sd-EF is fundamentally incompatible with ex-post EFX, prompting a relaxation of the ex-ante benchmark. We then present a poly. time algorithm that achieves ex-post EFX and PO together with ex-ante 9/10-EF. Our algorithm uses dependent rounding and leverages structural properties of EFX and PO allocations.
  2)For monotone valuations, we study EFX-with-charity: a relaxation of EFX where some goods remain unallocated, with no agent envying the unallocated pool. We show that ex-post EFX-with-charity can be achieved alongside ex-ante 0.5-EF.
  3)Finally, for subadditive valuations, we strengthen our previous ex-post guarantee to EFX-with-bounded-charity, where at most n-1 goods (n= no. of agents) remain unallocated, at the price of weakening the ex-ante guarantee to 0.5-proportionality.

[Arxiv](https://arxiv.org/abs/2507.16209)