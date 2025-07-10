# # SlimCaching：分布式推理中的专家混合模型边缘缓存方案

发布时间：2025年07月09日

`LLM理论` `边缘计算` `分布式系统`

> SlimCaching: Edge Caching of Mixture-of-Experts for Distributed Inference

# 摘要

> 混合专家（MoE）模型通过仅激活与输入相关的少量专家，显著提升了大型语言模型（LLMs）的扩展性。然而，MoE模型中大量专家网络的存在为边缘设备带来了显著的存储负担。为应对这一挑战，我们提出了一种将专家分散在边缘网络中进行分布式推理的方案。基于流行的Top-$K$专家选择策略，我们在存储约束下优化专家缓存，从而制定了一个最小化延迟的问题。当$K=1$时，该问题简化为具有背包约束的单调次模最大化问题，为此我们设计了一个具有$(1 - 1/e)$近似保证的贪心算法。对于一般情况$K\geq1$，同一MoE层内专家的共同激活引入了非次模性，使得贪心方法失效。为解决这一问题，我们提出了一种连续的贪心分解方法，将原问题分解为一系列子问题，每个子问题通过动态规划方法求解。此外，我们还设计了一种基于最大卷积技术的加速算法，以在多项式时间内获得具有可证明保证的近似解。在各种MoE模型上的仿真结果表明，与现有基线相比，我们的方法显著降低了推理延迟。

> Mixture-of-Experts (MoE) models improve the scalability of large language models (LLMs) by activating only a small subset of relevant experts per input. However, the sheer number of expert networks in an MoE model introduces a significant storage burden for an edge device. To address this challenge, we consider a scenario where experts are dispersed within an edge network for distributed inference. Based on the popular Top-$K$ expert selection strategy, we formulate a latency minimization problem by optimizing expert caching on edge servers under storage constraints. When $K=1$, the problem reduces to a monotone submodular maximization problem with knapsack constraints, for which we design a greedy-based algorithm with a $(1 - 1/e)$-approximation guarantee. For the general case where $K\geq1$, expert co-activation within the same MoE layer introduces non-submodularity, causing greedy methods to be ineffective. To tackle this issue, we propose a successive greedy decomposition method to decompose the original problem into a series of subproblems, with each being solved by a dynamic programming approach. Furthermore, we design an accelerated algorithm based on the max-convolution technique to obtain the approximate solution with a provable guarantee in polynomial time. Simulation results on various MoE models demonstrate that our method significantly reduces inference latency compared to existing baselines.

[Arxiv](https://arxiv.org/abs/2507.06567)