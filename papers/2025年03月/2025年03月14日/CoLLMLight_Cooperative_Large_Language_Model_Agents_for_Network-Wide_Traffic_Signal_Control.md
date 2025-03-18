# CoLLMLight：全网交通信号控制的协作大型语言模型代理

发布时间：2025年03月14日

`Agent

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来设计和优化交通信号控制（TSC）系统，特别是通过构建合作型LLM代理框架来解决不同代理间的协调问题。虽然LLMs在其中被用作工具，但论文的核心贡献在于提出了一种新的代理框架和相关机制，以实现更高效的交通信号控制。因此，这篇论文更偏向于Agent类别，因为它专注于智能体的设计和应用，而不仅仅是LLMs本身的应用或理论。` `交通管理` `智能交通系统`

> CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control

# 摘要

> 交通信号控制（TSC）在城市交通管理中至关重要，它通过优化交通流和缓解拥堵来提升整体效率。尽管大型语言模型（LLMs）因其强大的问题解决和泛化能力，最近成为TSC领域的热门工具，但现有方法未能有效解决不同代理间的协调问题，这限制了它们在实现全网优化方面的潜力。为了解决这一问题，我们提出了CoLLMLight，一个专为TSC设计的合作型LLM代理框架。

具体而言，我们首先构建了一个结构化的时空图，用于捕捉实时交通动态和相邻交叉口之间的空间关系，从而帮助LLM更好地理解和推理复杂的交通互动。此外，我们引入了一个复杂度感知的推理机制，能够根据实时交通状况动态调整推理深度，确保在不牺牲决策质量的同时，实现最优的计算效率。我们还提出了一种创新的微调策略，通过迭代的模拟驱动数据收集和环境反馈，构建了一个专门用于合作型TSC的轻量化LLM。

在合成数据集和真实世界数据集上的大量实验表明，CoLLMLight在各种交通场景下均优于现有最优方法，充分展示了其有效性、可扩展性和鲁棒性。这一研究为基于LLMs的交通信号控制提供了新的思路和解决方案，为未来智能交通系统的发展奠定了坚实基础。

> Traffic Signal Control (TSC) plays a critical role in urban traffic management by optimizing traffic flow and mitigating congestion. While Large Language Models (LLMs) have recently emerged as promising tools for TSC due to their exceptional problem-solving and generalization capabilities, existing approaches fail to address the essential need for inter-agent coordination, limiting their effectiveness in achieving network-wide optimization. To bridge this gap, we propose CoLLMLight, a cooperative LLM agent framework for TSC. Specifically, we first construct a structured spatiotemporal graph to capture real-time traffic dynamics and spatial relationships among neighboring intersections, enabling the LLM to reason about complex traffic interactions. Moreover, we introduce a complexity-aware reasoning mechanism that dynamically adapts reasoning depth based on real-time traffic conditions, ensuring optimal computational efficiency without sacrificing decision quality. Besides, we propose a fine-tuning strategy that leverages iterative simulation-driven data collection and environmental feedback to build a lightweight LLM tailored for cooperative TSC. Extensive experiments on both synthetic and real-world datasets demonstrate that CoLLMLight outperforms state-of-the-art methods in diverse traffic scenarios, showcasing its effectiveness, scalability, and robustness.

[Arxiv](https://arxiv.org/abs/2503.11739)