# 联邦多智能体系统中的隐私增强范式

发布时间：2025年03月11日

`Agent` `多智能体系统` `隐私保护`

> Privacy-Enhancing Paradigms within Federated Multi-Agent Systems

# 摘要

> 基于LLM的多智能体系统（MAS）在解决复杂问题方面表现出色，但面临敏感领域的隐私挑战。本文提出联邦MAS概念，与传统联邦学习（FL）有显著差异。我们识别了开发联邦MAS的三大关键挑战：智能体间的异构隐私协议、多方对话的结构差异以及动态对话网络结构。为解决这些挑战，我们提出了嵌入式隐私增强智能体（EPEAgent），它无缝集成到检索增强生成（RAG）和上下文检索阶段，仅共享任务相关、特定于智能体的信息。我们设计了全面的数据集来评估该方案。实验表明，EPEAgent在增强隐私保护的同时保持了系统性能。代码将在https://github.com/ZitongShi/EPEAgent上提供。


> LLM-based Multi-Agent Systems (MAS) have proven highly effective in solving complex problems by integrating multiple agents, each performing different roles. However, in sensitive domains, they face emerging privacy protection challenges. In this paper, we introduce the concept of Federated MAS, highlighting the fundamental differences between Federated MAS and traditional FL. We then identify key challenges in developing Federated MAS, including: 1) heterogeneous privacy protocols among agents, 2) structural differences in multi-party conversations, and 3) dynamic conversational network structures. To address these challenges, we propose Embedded Privacy-Enhancing Agents (EPEAgent), an innovative solution that integrates seamlessly into the Retrieval-Augmented Generation (RAG) phase and the context retrieval stage. This solution minimizes data flows, ensuring that only task-relevant, agent-specific information is shared. Additionally, we design and generate a comprehensive dataset to evaluate the proposed paradigm. Extensive experiments demonstrate that EPEAgent effectively enhances privacy protection while maintaining strong system performance. The code will be availiable at https://github.com/ZitongShi/EPEAgent

[Arxiv](https://arxiv.org/abs/2503.08175)