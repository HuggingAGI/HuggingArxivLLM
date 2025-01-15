# 智能体视角下的提示技术投射及其对LLM合成训练数据的启示

发布时间：2025年01月13日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）中的提示技术与多智能体系统的关系，并提出了一个框架来描述和比较提示技术。论文的核心内容涉及多智能体系统的架构和交互模式，以及如何通过提示技术来模拟这些系统。因此，这篇论文更符合“Agent”分类，因为它主要关注多智能体系统的设计和交互，而不是单纯的LLM应用或理论。` `人工智能` `多智能体系统`

> Agent-Centric Projection of Prompting Techniques and Implications for Synthetic Training Data for Large Language Models

# 摘要

> # 摘要
最近，大型语言模型（LLMs）的提示技术和多智能体系统取得了显著进展，催生了日益复杂的方法。然而，我们仍缺乏一个框架来系统性地描述和比较提示技术，或理解它们与多智能体LLM系统的关系。本文提出并解释了LLM系统中的线性上下文（单一、连续的交互序列）和非线性上下文（分支或多路径）概念。这些概念为开发以智能体为中心的提示技术投影奠定了基础，揭示提示策略与多智能体系统之间的深层联系。基于此框架，我们提出三个猜想：（1）非线性提示技术的结果可预测等效多智能体系统的结果，（2）多智能体系统架构可通过单LLM提示技术模拟等效交互模式来复制，（3）这些等价性为生成合成训练数据提供了新思路。我们认为，这一视角不仅促进了提示技术与多智能体领域的交叉融合，还为未来LLM系统的设计与训练开辟了新方向。

> Recent advances in prompting techniques and multi-agent systems for Large Language Models (LLMs) have produced increasingly complex approaches. However, we lack a framework for characterizing and comparing prompting techniques or understanding their relationship to multi-agent LLM systems. This position paper introduces and explains the concepts of linear contexts (a single, continuous sequence of interactions) and non-linear contexts (branching or multi-path) in LLM systems. These concepts enable the development of an agent-centric projection of prompting techniques, a framework that can reveal deep connections between prompting strategies and multi-agent systems. We propose three conjectures based on this framework: (1) results from non-linear prompting techniques can predict outcomes in equivalent multi-agent systems, (2) multi-agent system architectures can be replicated through single-LLM prompting techniques that simulate equivalent interaction patterns, and (3) these equivalences suggest novel approaches for generating synthetic training data. We argue that this perspective enables systematic cross-pollination of research findings between prompting and multi-agent domains, while providing new directions for improving both the design and training of future LLM systems.

[Arxiv](https://arxiv.org/abs/2501.07815)