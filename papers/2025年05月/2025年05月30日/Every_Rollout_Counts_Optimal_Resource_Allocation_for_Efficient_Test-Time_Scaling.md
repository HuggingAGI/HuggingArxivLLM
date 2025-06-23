# 每一次部署都至关重要：面向高效测试时扩展的最优资源分配

发布时间：2025年05月30日

`LLM应用` `人工智能` `数学推理`

> Every Rollout Counts: Optimal Resource Allocation for Efficient Test-Time Scaling

# 摘要

> 测试时缩放（TTS）通过在推理时使用额外的计算来探索多个推理路径，从而提高了大型语言模型（LLMs）的性能。然而，如何在搜索过程中最有效地分配固定数量的展开预算仍是一个未充分研究的问题，常常导致测试时计算资源的低效使用。为了填补这一空白，我们将测试时搜索建模为一个资源分配问题，并推导出在固定展开预算下最大化获得正确解概率的最优分配策略。在这一框架下，我们揭示了现有搜索方法的一个核心局限性：基于解决方案的分配倾向于支持候选数量更多的推理方向，这在理论上会导致计算资源的次优和低效使用。为了解决这一问题，我们提出了方向导向的资源分配（DORA），这是一种可证明最优的方法，通过将方向质量与候选数量解耦，并在方向级别上分配资源来缓解这一偏差。为了展示DORA的有效性，我们在具有挑战性的数学推理基准测试中进行了大量实验，包括MATH500、AIME2024和AIME2025。实证结果表明，DORA在与强基线相当的计算成本下始终表现更优，达到了最先进的准确性。我们希望我们的发现能够增进对LLMs最优TTS的广泛理解。


> Test-Time Scaling (TTS) improves the performance of Large Language Models (LLMs) by using additional inference-time computation to explore multiple reasoning paths through search. Yet how to allocate a fixed rollout budget most effectively during search remains underexplored, often resulting in inefficient use of compute at test time. To bridge this gap, we formulate test-time search as a resource allocation problem and derive the optimal allocation strategy that maximizes the probability of obtaining a correct solution under a fixed rollout budget. Within this formulation, we reveal a core limitation of existing search methods: solution-level allocation tends to favor reasoning directions with more candidates, leading to theoretically suboptimal and inefficient use of compute. To address this, we propose Direction-Oriented Resource Allocation (DORA), a provably optimal method that mitigates this bias by decoupling direction quality from candidate count and allocating resources at the direction level. To demonstrate DORA's effectiveness, we conduct extensive experiments on challenging mathematical reasoning benchmarks including MATH500, AIME2024, and AIME2025. The empirical results show that DORA consistently outperforms strong baselines with comparable computational cost, achieving state-of-the-art accuracy. We hope our findings contribute to a broader understanding of optimal TTS for LLMs.

[Arxiv](https://arxiv.org/abs/2506.15707)