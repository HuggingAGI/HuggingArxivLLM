# 从莱顿到欢乐岛：社区检测的常Potts模型——一种享乐博弈

发布时间：2025年09月03日

`Agent` `基础理论`

> From Leiden to Pleasure Island: The Constant Potts Model for Community Detection as a Hedonic Game

# 摘要

> 社区检测是数据科学的基础问题之一，核心是将节点划分为不相交的社区。本文从博弈论视角重新解读常数波特模型（CPM）在网络社区划分中的应用，并重点分析其效率、稳健性与准确性。效率方面，我们通过将CPM的全局哈密顿量分解为局部效用函数，将其重新诠释为潜在享乐博弈——此时每个智能体的局部效用增益与全局效用的增量完全匹配。基于这一等价性，我们证明：通过更好响应动态对CPM目标进行局部优化，可在伪多项式时间内收敛至平衡划分。稳健性方面，我们提出并关联了两个稳定性准则：一是基于全新稳健性概念的严格准则，要求节点在社区内同时最大化邻居数、最小化非邻居数；二是基于这些目标加权和的松弛效用函数，由分辨率参数调控。准确性方面，在社区跟踪场景中（初始划分用于利用部分真实信息引导Leiden算法），实验表明稳健划分能更精准地恢复真实社区结构。

> Community detection is one of the fundamental problems in data science which consists of partitioning nodes into disjoint communities. We present a game-theoretic perspective on the Constant Potts Model (CPM) for partitioning networks into disjoint communities, emphasizing its efficiency, robustness, and accuracy. Efficiency: We reinterpret CPM as a potential hedonic game by decomposing its global Hamiltonian into local utility functions, where the local utility gain of each agent matches the corresponding increase in global utility. Leveraging this equivalence, we prove that local optimization of the CPM objective via better-response dynamics converges in pseudo-polynomial time to an equilibrium partition. Robustness: We introduce and relate two stability criteria: a strict criterion based on a novel notion of robustness, requiring nodes to simultaneously maximize neighbors and minimize non-neighbors within communities, and a relaxed utility function based on a weighted sum of these objectives, controlled by a resolution parameter. Accuracy: In community tracking scenarios, where initial partitions are used to bootstrap the Leiden algorithm with partial ground-truth information, our experiments reveal that robust partitions yield higher accuracy in recovering ground-truth communities.

[Arxiv](https://arxiv.org/abs/2509.03834)