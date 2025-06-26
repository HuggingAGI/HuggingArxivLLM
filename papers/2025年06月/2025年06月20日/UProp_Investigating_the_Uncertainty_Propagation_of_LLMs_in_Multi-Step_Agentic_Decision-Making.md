# UProp：研究大型语言模型（LLMs）在多步骤智能体决策过程中的不确定性传播机制。

发布时间：2025年06月20日

`LLM应用` `智能系统` `决策支持系统`

> UProp: Investigating the Uncertainty Propagation of LLMs in Multi-Step Agentic Decision-Making

# 摘要

> 随着大型语言模型（LLMs）在涉及现实世界顺序决策的安全关键应用中得到应用，了解何时信任LLM的决策变得至关重要。然而，现有的LLM不确定性量化（UQ）方法主要针对单轮问答场景，导致在多步决策场景，例如LLM智能系统中，相关研究仍显不足。本文提出了一种基于信息论的框架，将LLM的顺序决策不确定性分解为两部分：（i）与当前决策内在相关的内部不确定性，这是现有UQ方法的重点；（ii）外部不确定性，一个描述应从先前决策中继承多少不确定性的互信息（MI）量。我们还提出了UProp，一种高效且有效的外部不确定性估计器，它通过将互信息的直接估计转换为对多个轨迹依赖决策过程（TDPs）的点互信息（PMI）的估计来实现这一目标。UProp在AgentBench和HotpotQA等多步决策基准测试中，使用GPT-4.1和DeepSeek-V3等最先进的LLMs进行了评估。实验结果表明，UProp显著优于现有配备深思熟虑聚合策略的单轮UQ基线。此外，我们对UProp进行了全面分析，涵盖采样效率、潜在应用和中间不确定性传播，以展示其有效性。代码将在https://github.com/jinhaoduan/UProp上提供。

> As Large Language Models (LLMs) are integrated into safety-critical applications involving sequential decision-making in the real world, it is essential to know when to trust LLM decisions. Existing LLM Uncertainty Quantification (UQ) methods are primarily designed for single-turn question-answering formats, resulting in multi-step decision-making scenarios, e.g., LLM agentic system, being underexplored. In this paper, we introduce a principled, information-theoretic framework that decomposes LLM sequential decision uncertainty into two parts: (i) internal uncertainty intrinsic to the current decision, which is focused on existing UQ methods, and (ii) extrinsic uncertainty, a Mutual-Information (MI) quantity describing how much uncertainty should be inherited from preceding decisions. We then propose UProp, an efficient and effective extrinsic uncertainty estimator that converts the direct estimation of MI to the estimation of Pointwise Mutual Information (PMI) over multiple Trajectory-Dependent Decision Processes (TDPs). UProp is evaluated over extensive multi-step decision-making benchmarks, e.g., AgentBench and HotpotQA, with state-of-the-art LLMs, e.g., GPT-4.1 and DeepSeek-V3. Experimental results demonstrate that UProp significantly outperforms existing single-turn UQ baselines equipped with thoughtful aggregation strategies. Moreover, we provide a comprehensive analysis of UProp, including sampling efficiency, potential applications, and intermediate uncertainty propagation, to demonstrate its effectiveness. Codes will be available at https://github.com/jinhaoduan/UProp.

[Arxiv](https://arxiv.org/abs/2506.17419)