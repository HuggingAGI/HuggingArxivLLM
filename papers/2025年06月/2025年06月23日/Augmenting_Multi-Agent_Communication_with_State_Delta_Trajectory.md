# 基于状态增量轨迹提升多智能体通信效果

发布时间：2025年06月23日

`Agent` `人工智能`

> Augmenting Multi-Agent Communication with State Delta Trajectory

# 摘要

> 多智能体技术，如角色扮演或多轮辩论，已被证明能显著提升大型语言模型（LLMs）在下游任务中的性能。尽管现有基于LLM的多智能体系统的工作流程各异，但它们大多采用自然语言进行智能体间的通信。这种做法虽简单易懂，却也带来了信息损失的问题，因为一个模型需先将其连续状态向量下采样为具体令牌，再传递给另一个模型。当传输内容涉及推理逻辑或抽象思维而非简单事实时，这种损失尤为明显。为解决此问题，我们提出了一种新型通信协议，可在智能体间传递自然语言令牌及令牌级别的状态转换轨迹。与实际状态值相比，我们发现LLMs在生成每个令牌后状态变化的序列更能反映隐藏的推理信息。为此，我们提出了状态增量编码（SDE）方法来表征状态转换轨迹。实验结果表明，采用SDE的多智能体系统在复杂推理任务中表现最优，凸显了通信增强在基于LLM的多智能体系统中的潜力。


> Multi-agent techniques such as role playing or multi-turn debates have been shown to be effective in improving the performance of large language models (LLMs) in downstream tasks. Despite their differences in workflows, existing LLM-based multi-agent systems mostly use natural language for agent communication. While this is appealing for its simplicity and interpretability, it also introduces inevitable information loss as one model must down sample its continuous state vectors to concrete tokens before transferring them to the other model. Such losses are particularly significant when the information to transfer is not simple facts, but reasoning logics or abstractive thoughts. To tackle this problem, we propose a new communication protocol that transfers both natural language tokens and token-wise state transition trajectory from one agent to another. Particularly, compared to the actual state value, we find that the sequence of state changes in LLMs after generating each token can better reflect the information hidden behind the inference process, so we propose a State Delta Encoding (SDE) method to represent state transition trajectories. The experimental results show that multi-agent systems with SDE achieve SOTA performance compared to other communication protocols, particularly in tasks that involve complex reasoning. This shows the potential of communication augmentation for LLM-based multi-agent systems.

[Arxiv](https://arxiv.org/abs/2506.19209)