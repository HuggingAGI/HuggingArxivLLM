# OpenCity: 一个可扩展的平台，用于模拟大规模LLM代理的城市活动

发布时间：2024年10月11日

`Agent

理由：这篇论文主要讨论了基于代理的模型（ABMs）与大型语言模型（LLMs）的结合，提出了一个名为 OpenCity 的可扩展模拟平台，用于优化 LLM 代理在城市空间中的模拟效率。论文的核心内容围绕如何通过优化 LLM 代理的请求调度和提示策略来提高模拟的效率和扩展性。因此，这篇论文主要属于Agent类别，因为它聚焦于代理模型的设计和优化，特别是如何利用 LLM 代理来模拟复杂的社会现象。` `城市规划` `社会模拟`

> OpenCity: A Scalable Platform to Simulate Urban Activities with Massive LLM Agents

# 摘要

> # 摘要
基于代理的模型（ABMs）长期以来用于研究个体行为如何在城市空间中形成复杂的社会现象。与黑箱预测模型不同，ABMs 擅长揭示驱动这些涌现行为的微观-宏观联系。随着大型语言模型（LLMs）的崛起，LLM 代理能够以前所未有的真实感模拟城市活动。然而，LLMs 的高计算成本对扩展模拟提出了巨大挑战。为此，我们提出了 OpenCity，一个为系统和提示效率优化的可扩展模拟平台。我们设计了 LLM 请求调度器，通过 IO 多路复用并行化请求以减少通信开销，并采用“分组-蒸馏”提示优化策略，通过聚类具有相似静态属性的代理来最小化冗余。在六个全球城市的实验中，OpenCity 实现了每个代理模拟时间 600 倍的加速，LLM 请求减少 70%，令牌使用减少 50%。这些改进使得在普通硬件上 1 小时内模拟 10,000 个代理的日常活动成为可能。此外，OpenCity 的显著加速使我们首次为 LLM 代理建立了城市模拟基准，将模拟的城市活动与全球六个主要城市的真实数据进行比较。我们相信 OpenCity 平台为利用 LLMs 进行城市空间的跨学科研究提供了关键基础设施，推动了更广泛研究社区的集体努力。代码仓库可在 https://anonymous.4open.science/r/Anonymous-OpenCity-42BD 获取。

> Agent-based models (ABMs) have long been employed to explore how individual behaviors aggregate into complex societal phenomena in urban space. Unlike black-box predictive models, ABMs excel at explaining the micro-macro linkages that drive such emergent behaviors. The recent rise of Large Language Models (LLMs) has led to the development of LLM agents capable of simulating urban activities with unprecedented realism. However, the extreme high computational cost of LLMs presents significant challenges for scaling up the simulations of LLM agents. To address this problem, we propose OpenCity, a scalable simulation platform optimized for both system and prompt efficiencies. Specifically, we propose a LLM request scheduler to reduce communication overhead by parallelizing requests through IO multiplexing. Besides, we deisgn a "group-and-distill" prompt optimization strategy minimizes redundancy by clustering agents with similar static attributes. Through experiments on six global cities, OpenCity achieves a 600-fold acceleration in simulation time per agent, a 70% reduction in LLM requests, and a 50% reduction in token usage. These improvements enable the simulation of 10,000 agents' daily activities in 1 hour on commodity hardware. Besides, the substantial speedup of OpenCity allows us to establish a urban simulation benchmark for LLM agents for the first time, comparing simulated urban activities with real-world data in 6 major cities around the globe. We believe our OpenCity platform provides a critical infrastructure to harness the power of LLMs for interdisciplinary studies in urban space, fostering the collective efforts of broader research communities. Code repo is available at https://anonymous.4open.science/r/Anonymous-OpenCity-42BD.

[Arxiv](https://arxiv.org/abs/2410.21286)