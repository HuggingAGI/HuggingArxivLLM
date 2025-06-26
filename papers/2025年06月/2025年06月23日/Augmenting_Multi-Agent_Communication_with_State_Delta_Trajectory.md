# # 基于状态增量轨迹的多智能体通信增强方法
利用状态增量轨迹提升多智能体通信能力

发布时间：2025年06月23日

`Agent` `多智能体系统` `大型语言模型`

> Augmenting Multi-Agent Communication with State Delta Trajectory

# 摘要

> 多智能体技术（如角色扮演或多轮辩论）在提升大型语言模型（LLMs）的下游任务性能方面表现突出。尽管这些系统在工作流程上有所不同，但现有的基于LLMs的多智能体系统大多依赖自然语言进行智能体间的通信。虽然这种方式简单直观且易于解释，但也带来了不可避免的信息损失，因为一个模型需要将其连续的状态向量降采样为具体的token，然后再传递给另一个模型。这种信息损失在传输的不是简单的事实，而是推理逻辑或抽象思维时尤为明显。

为了解决这一问题，我们提出了一种新的通信协议，将自然语言token和基于token的状态转换轨迹从一个智能体传递到另一个智能体。特别地，我们发现与实际状态值相比，LLMs在生成每个token后状态变化的序列更能反映推理过程背后隐藏的信息。因此，我们提出了一种状态增量编码（SDE）方法来表示状态转换轨迹。实验结果表明，与其它通信协议相比，采用SDE的多智能体系统在复杂推理任务中达到了SOTA（最先进）的性能水平。这表明，通过增强通信方式，基于LLMs的多智能体系统具有巨大的潜力。


> Multi-agent techniques such as role playing or multi-turn debates have been shown to be effective in improving the performance of large language models (LLMs) in downstream tasks. Despite their differences in workflows, existing LLM-based multi-agent systems mostly use natural language for agent communication. While this is appealing for its simplicity and interpretability, it also introduces inevitable information loss as one model must down sample its continuous state vectors to concrete tokens before transferring them to the other model. Such losses are particularly significant when the information to transfer is not simple facts, but reasoning logics or abstractive thoughts. To tackle this problem, we propose a new communication protocol that transfers both natural language tokens and token-wise state transition trajectory from one agent to another. Particularly, compared to the actual state value, we find that the sequence of state changes in LLMs after generating each token can better reflect the information hidden behind the inference process, so we propose a State Delta Encoding (SDE) method to represent state transition trajectories. The experimental results show that multi-agent systems with SDE achieve SOTA performance compared to other communication protocols, particularly in tasks that involve complex reasoning. This shows the potential of communication augmentation for LLM-based multi-agent systems.

[Arxiv](https://arxiv.org/abs/2506.19209)