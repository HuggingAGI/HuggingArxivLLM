# RTLSquad: 多智能体驱动的可解释RTL设计

发布时间：2025年01月05日

`Agent

理由：这篇论文描述了一个基于LLM的多智能体系统RTLSquad，用于生成可解释的RTL代码。该系统通过多个智能体协同工作，完成设计流程的不同阶段，并确保决策的透明性。因此，这篇论文主要涉及智能体（Agent）的应用和设计，属于Agent分类。` `硬件设计` `自动化`

> RTLSquad: Multi-Agent Based Interpretable RTL Design

# 摘要

> 优化RTL代码是提升硬件PPA性能的关键。LLMs为RTL代码的自动生成与优化开辟了新途径，但现有方法常因缺乏决策可解释性而难以获得硬件工程师的信任，阻碍了其融入设计流程。为此，我们推出了RTLSquad，一个基于LLM的多智能体系统，旨在生成可解释的RTL代码。RTLSquad将设计流程细分为探索、实现及验证评估三阶段，由专业智能体团队协同完成，不仅产出优化后的RTL代码，还通过智能体间的交流确保决策透明。实验验证，RTLSquad在确保代码功能正确与优化PPA性能上表现卓越，并能清晰展示决策路径，彰显了其实际应用价值。

> Optimizing Register-Transfer Level (RTL) code is crucial for improving hardware PPA performance. Large Language Models (LLMs) offer new approaches for automatic RTL code generation and optimization. However, existing methods often lack decision interpretability (sufficient, understandable justification for decisions), making it difficult for hardware engineers to trust the generated results, thus preventing these methods from being integrated into the design process. To address this, we propose RTLSquad, a novel LLM-Based Multi-Agent system for interpretable RTL code generation. RTLSquad divides the design process into exploration, implementation, and verification & evaluation stages managed by specialized agent squads, generating optimized RTL code through inter-agent collaboration, and providing decision interpretability through the communication process. Experiments show that RTLSquad excels in generating functionally correct RTL code and optimizing PPA performance, while also having the capability to provide decision paths, demonstrating the practical value of our system.

[Arxiv](https://arxiv.org/abs/2501.05470)