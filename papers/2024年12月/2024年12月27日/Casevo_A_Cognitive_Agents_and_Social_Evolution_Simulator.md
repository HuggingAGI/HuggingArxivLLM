# Casevo：认知代理与社会进化模拟器

发布时间：2024年12月27日

`Agent

理由：这篇论文介绍了一个多智能体模拟框架 Casevo，它结合了大型语言模型（LLMs）来模拟复杂的社会现象和决策过程。该框架具备智能体驱动的特性，并且支持动态社会建模，适用于社交网络分析、舆论动态和复杂社会系统中的行为预测等场景。因此，这篇论文主要关注的是智能体（Agent）的应用和开发，属于Agent分类。` `社交网络分析` `社会行为模拟`

> Casevo: A Cognitive Agents and Social Evolution Simulator

# 摘要

> 本文提出了一种多智能体模拟框架 Casevo（认知智能体与社会演化模拟器），它结合大型语言模型（LLMs）来模拟复杂的社会现象和决策过程。Casevo 是一个由智能体驱动的离散事件模拟器，具备思维链（CoT）、检索增强生成（RAG）和可定制记忆机制等特性，支持动态社会建模，适用于社交网络分析、舆论动态和复杂社会系统中的行为预测等场景。我们以 2020 年美国中期选举电视辩论为例，验证了 Casevo 的有效性。实验表明，Casevo 能够实现更真实、灵活的智能体交互，显著提升动态社会现象模拟的质量。该研究通过提供基于先进 LLM 驱动智能体的大规模、高保真社会行为模拟系统，扩展了传统基于智能体的建模（ABM）能力。Casevo 的开源代码仓库地址为 https://github.com/rgCASS/casevo。

> In this paper, we introduce a multi-agent simulation framework Casevo (Cognitive Agents and Social Evolution Simulator), that integrates large language models (LLMs) to simulate complex social phenomena and decision-making processes. Casevo is designed as a discrete-event simulator driven by agents with features such as Chain of Thoughts (CoT), Retrieval-Augmented Generation (RAG), and Customizable Memory Mechanism. Casevo enables dynamic social modeling, which can support various scenarios such as social network analysis, public opinion dynamics, and behavior prediction in complex social systems. To demonstrate the effectiveness of Casevo, we utilize one of the U.S. 2020 midterm election TV debates as a simulation example. Our results show that Casevo facilitates more realistic and flexible agent interactions, improving the quality of dynamic social phenomena simulation. This work contributes to the field by providing a robust system for studying large-scale, high-fidelity social behaviors with advanced LLM-driven agents, expanding the capabilities of traditional agent-based modeling (ABM). The open-source code repository address of casevo is https://github.com/rgCASS/casevo.

[Arxiv](https://arxiv.org/abs/2412.19498)