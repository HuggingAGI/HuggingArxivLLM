# 组合多臂老虎机的离线学习

发布时间：2025年01月31日

`Agent

理由：这篇论文主要讨论的是组合多臂赌博机（CMAB）的离线学习框架，特别是提出了一个新的算法（CLCB）来处理离线数据。虽然论文中提到了LLM缓存，但核心内容是关于序列决策框架和离线学习算法，这更符合“Agent”分类，因为Agent通常涉及决策制定和学习策略的研究。` `机器学习` `决策系统`

> Offline Learning for Combinatorial Multi-armed Bandits

# 摘要

> 组合多臂赌博机（CMAB）是过去十年中广泛研究的序列决策框架。然而，现有研究多聚焦于在线场景，忽略了在线交互的高成本和现成的离线数据。为此，我们提出了首个CMAB离线学习框架——Off-CMAB。其核心是组合下界置信度（CLCB）算法，结合了悲观奖励估计与组合求解器。我们提出了两个新的数据覆盖条件来评估离线数据集的质量，并证明在这些条件下，CLCB能够实现接近最优的次优性差距，与理论下界仅相差一个对数因子。通过实际应用，如学习排序、LLM缓存和社交影响力最大化，我们验证了Off-CMAB处理非线性奖励函数、通用反馈模型及排除最优动作的分布外样本的能力。大量实验进一步证明了CLCB的卓越性能。

> The combinatorial multi-armed bandit (CMAB) is a fundamental sequential decision-making framework, extensively studied over the past decade. However, existing work primarily focuses on the online setting, overlooking the substantial costs of online interactions and the readily available offline datasets. To overcome these limitations, we introduce Off-CMAB, the first offline learning framework for CMAB. Central to our framework is the combinatorial lower confidence bound (CLCB) algorithm, which combines pessimistic reward estimations with combinatorial solvers. To characterize the quality of offline datasets, we propose two novel data coverage conditions and prove that, under these conditions, CLCB achieves a near-optimal suboptimality gap, matching the theoretical lower bound up to a logarithmic factor. We validate Off-CMAB through practical applications, including learning to rank, large language model (LLM) caching, and social influence maximization, showing its ability to handle nonlinear reward functions, general feedback models, and out-of-distribution action samples that excludes optimal or even feasible actions. Extensive experiments on synthetic and real-world datasets further highlight the superior performance of CLCB.

[Arxiv](https://arxiv.org/abs/2501.19300)