# 基于强化学习的检索增强型大型语言模型可信对齐

发布时间：2024年10月22日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）中的可信度问题，并提出了基于强化学习的Trustworthy-Alignment算法来解决幻觉问题。论文的核心内容围绕如何通过外部证据增强语言模型的可信度，属于检索增强生成（RAG）的研究范畴。` `可信计算`

> Trustworthy Alignment of Retrieval-Augmented Large Language Models via Reinforcement Learning

# 摘要

> 可信度是大型语言模型实际应用的关键前提。本文聚焦于语言模型在检索增强方面的可信度。尽管检索增强生成有外部证据支持，但仍存在幻觉问题，主要源于上下文知识与参数知识的冲突。我们认为，检索增强语言模型具备根据上下文和参数知识提供响应的内在能力。受语言模型与人类偏好对齐的启发，我们首次尝试将检索增强语言模型对齐到仅依赖外部证据、忽略参数知识干扰的状态。为此，我们提出了基于强化学习的Trustworthy-Alignment算法，从理论和实验上证明，大型语言模型无需明确监督即可达到可信状态。我们的研究揭示了大型语言模型通过自身探索内在能力的潜力，并将对齐的应用场景从满足人类偏好扩展到创建可信代理。

> Trustworthiness is an essential prerequisite for the real-world application of large language models. In this paper, we focus on the trustworthiness of language models with respect to retrieval augmentation. Despite being supported with external evidence, retrieval-augmented generation still suffers from hallucinations, one primary cause of which is the conflict between contextual and parametric knowledge. We deem that retrieval-augmented language models have the inherent capabilities of supplying response according to both contextual and parametric knowledge. Inspired by aligning language models with human preference, we take the first step towards aligning retrieval-augmented language models to a status where it responds relying merely on the external evidence and disregards the interference of parametric knowledge. Specifically, we propose a reinforcement learning based algorithm Trustworthy-Alignment, theoretically and experimentally demonstrating large language models' capability of reaching a trustworthy status without explicit supervision on how to respond. Our work highlights the potential of large language models on exploring its intrinsic abilities by its own and expands the application scenarios of alignment from fulfilling human preference to creating trustworthy agents.

[Arxiv](https://arxiv.org/abs/2410.16843)