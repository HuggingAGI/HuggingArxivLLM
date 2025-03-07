# AOLO: 面向低碳无线大语言模型服务的分析与优化

发布时间：2025年03月06日

`LLM应用

理由：这篇论文探讨了如何优化大型语言模型（LLMs）在实际应用中的能源消耗和碳排放，特别是在无线服务中的应用。它提出了一种框架AOLO，用于分析和优化低碳导向的LLM服务，涉及碳足迹模型和优化算法。这些内容属于LLMs的实际应用和优化，因此归类为LLM应用。` `环境科学` `无线通信`

> AOLO: Analysis and Optimization For Low-Carbon Oriented Wireless Large Language Model Services

# 摘要

> 近期，大型语言模型（LLMs）的突破性进展推动了其在各领域的广泛应用和大规模部署。然而，其在推理阶段的能源消耗和碳排放带来的环境影响日益引发关注。现有研究主要集中在推理计算本身，忽视了对网络辅助LLM服务系统中碳足迹的分析与优化。为填补这一空白，我们提出了AOLO框架，旨在为低碳导向的无线LLM服务提供分析与优化方案。AOLO引入了一个全面的碳足迹模型，量化了整个LLM服务链中的温室气体排放，涵盖计算推理和无线通信。此外，我们制定了一个优化问题，旨在最小化整体碳足迹，通过在体验质量和系统性能约束下联合优化推理输出和发射功率来求解。为实现这一联合优化，我们利用了脉冲神经网络（SNN）的能效优势，采用SNN作为演员网络，并提出了一种低碳导向的优化算法，即基于SNN的深度强化学习（SDRL）。全面的仿真表明，SDRL算法显著降低了整体碳足迹，与基准的软 actor-critic 相比，减少了18.77%，凸显了其在实现更可持续LLM推理服务方面的潜力。

> Recent advancements in large language models (LLMs) have led to their widespread adoption and large-scale deployment across various domains. However, their environmental impact, particularly during inference, has become a growing concern due to their substantial energy consumption and carbon footprint. Existing research has focused on inference computation alone, overlooking the analysis and optimization of carbon footprint in network-aided LLM service systems. To address this gap, we propose AOLO, a framework for analysis and optimization for low-carbon oriented wireless LLM services. AOLO introduces a comprehensive carbon footprint model that quantifies greenhouse gas emissions across the entire LLM service chain, including computational inference and wireless communication. Furthermore, we formulate an optimization problem aimed at minimizing the overall carbon footprint, which is solved through joint optimization of inference outputs and transmit power under quality-of-experience and system performance constraints. To achieve this joint optimization, we leverage the energy efficiency of spiking neural networks (SNNs) by adopting SNN as the actor network and propose a low-carbon-oriented optimization algorithm, i.e., SNN-based deep reinforcement learning (SDRL). Comprehensive simulations demonstrate that SDRL algorithm significantly reduces overall carbon footprint, achieving an 18.77% reduction compared to the benchmark soft actor-critic, highlighting its potential for enabling more sustainable LLM inference services.

[Arxiv](https://arxiv.org/abs/2503.04418)