# 批量自适应网络构建

发布时间：2025年07月25日

`其他` `网络科学`

> Batched Adaptive Network Formation

# 摘要

> 网络在众多经济与组织应用场景中扮演核心角色，涵盖职场团队构建、社交平台推荐及课堂友谊发展等领域。在这些情境下，网络以图的形式呈现，个体为节点，个体间关系为边，边的权重则反映了两两互动的成果。本文提出了一种自适应的在线策略，随着数据的不断积累，该策略能够逐步优化网络结构，以提升整体网络输出，具体表现为边权重总和的增加。

我们的研究基于加权随机块模型（WSBM），该模型通过离散潜在类型捕捉个体间不可观测的异质性，并以灵活的非参数方式建模个体间的互补性。我们将在线网络构建问题视为一种非标准的批量多臂老虎机问题，其中每种类型组合对应一个臂，而每对的回报则由类型互补性决定。这种设定在探索——学习潜在类型与互补性——与利用——构建高权重网络之间实现了平衡。我们得出了两项关键结论：WSBM的批量局部渐近正态性结果，以及不可计算似然的最大似然估计与变分估计之间的渐近等价性。这些发现共同为将变分估计视为正态信号提供了理论依据，从而支持了跨批次的贝叶斯更新。随后，我们将得到的后验分布融入定制的最大权重匹配问题，以制定下一阶段的策略。仿真结果表明，我们的算法在几个批次内显著提升了网络性能，参数估计日益精确，并在个体池动态变化的非平稳环境中依然表现优异。

> Networks are central to many economic and organizational applications, including workplace team formation, social platform recommendations, and classroom friendship development. In these settings, networks are modeled as graphs, with agents as nodes, agent pairs as edges, and edge weights capturing pairwise production or interaction outcomes. This paper develops an adaptive, or \textit{online}, policy that learns to form increasingly effective networks as data accumulates over time, progressively improving total network output measured by the sum of edge weights.
  Our approach builds on the weighted stochastic block model (WSBM), which captures agents' unobservable heterogeneity through discrete latent types and models their complementarities in a flexible, nonparametric manner. We frame the online network formation problem as a non-standard \textit{batched multi-armed bandit}, where each type pair corresponds to an arm, and pairwise reward depends on type complementarity. This strikes a balance between exploration -- learning latent types and complementarities -- and exploitation -- forming high-weighted networks. We establish two key results: a \textit{batched local asymptotic normality} result for the WSBM and an asymptotic equivalence between maximum likelihood and variational estimates of the intractable likelihood. Together, they provide a theoretical foundation for treating variational estimates as normal signals, enabling principled Bayesian updating across batches. The resulting posteriors are then incorporated into a tailored maximum-weight matching problem to determine the policy for the next batch. Simulations show that our algorithm substantially improves outcomes within a few batches, yields increasingly accurate parameter estimates, and remains effective even in nonstationary settings with evolving agent pools.

[Arxiv](https://arxiv.org/abs/2507.18961)