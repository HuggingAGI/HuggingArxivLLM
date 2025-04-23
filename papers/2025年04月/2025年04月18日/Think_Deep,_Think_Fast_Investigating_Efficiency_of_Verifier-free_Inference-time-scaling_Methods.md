# # 深入思考，快速推理：探究无验证器推理时间缩放方法的高效性
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月18日

`LLM应用` `人工智能` `机器学习`

> Think Deep, Think Fast: Investigating Efficiency of Verifier-free Inference-time-scaling Methods

# 摘要

> 探究推理时间计算（ITC）如何提升大型语言模型（LLM）能力是当前研究热点。近期，推理模型如Deepseek-R1的突破为强化学习提升LLM推理技能开辟了新机遇。深入理解ITC在不同模型中的推理机制，将为推进LLM前沿提供重要指导。本研究对推理和非推理模型在复杂推理任务上的推理时间缩放方法进行了全面分析。我们专注于无需验证器的推理时间缩放方法，因其无需奖励模型即可实现广泛适用性。研究发现，非推理模型即使拥有极高的推理预算，仍显著落后于推理模型。对于推理模型，多数投票证明是一种稳健的推理策略，通常与最佳的N（best-of-N）和序列修订等更复杂的ITC方法持平或更优。我们进一步深入分析了关键响应特征（长度和语言标记）与响应质量的关联，发现推理模型的正确响应通常比错误响应更简短，且较少使用犹豫和思考标记（但更多使用 discourse markers）。

> There is intense interest in investigating how inference time compute (ITC) (e.g. repeated sampling, refinements, etc) can improve large language model (LLM) capabilities. At the same time, recent breakthroughs in reasoning models, such as Deepseek-R1, unlock the opportunity for reinforcement learning to improve LLM reasoning skills. An in-depth understanding of how ITC interacts with reasoning across different models could provide important guidance on how to further advance the LLM frontier. This work conducts a comprehensive analysis of inference-time scaling methods for both reasoning and non-reasoning models on challenging reasoning tasks. Specifically, we focus our research on verifier-free inference time-scaling methods due to its generalizability without needing a reward model. We construct the Pareto frontier of quality and efficiency. We find that non-reasoning models, even with an extremely high inference budget, still fall substantially behind reasoning models. For reasoning models, majority voting proves to be a robust inference strategy, generally competitive or outperforming other more sophisticated ITC methods like best-of-N and sequential revisions, while the additional inference compute offers minimal improvements. We further perform in-depth analyses of the association of key response features (length and linguistic markers) with response quality, with which we can improve the existing ITC methods. We find that correct responses from reasoning models are typically shorter and have fewer hedging and thinking markers (but more discourse markers) than the incorrect responses.

[Arxiv](https://arxiv.org/abs/2504.14047)