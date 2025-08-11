# # 构建本质上更安全的AGI框架：基于语言中介的主动推断方法
通过语言中介主动推断机制，我们构建了一个致力于实现本质上更安全的AGI的框架。这一框架深入探讨了语言在主动推断过程中的中介作用，为实现更安全的AGI提供了坚实的理论基础和实用的指导方法。

发布时间：2025年08月07日

`Agent` `人工智能` `计算机科学`

> A Framework for Inherently Safer AGI through Language-Mediated Active Inference

# 摘要

> # 摘要
本文提出了一种结合主动推断原理与大型语言模型（LLMs）的创新框架，致力于开发更安全的人工通用智能（AGI）。传统AI安全方法主要依赖事后可解释性和奖励工程，但这些方法存在根本性局限。我们提出了一种全新的架构，通过透明的信念表示和层级价值对齐，将安全机制深度嵌入系统核心设计。我们的框架以自然语言为媒介，既实现了人类对AI思维过程的直接监督，又保持了计算上的可行性。

该架构构建了一个多主体系统，主体间基于主动推断原理实现自我组织，偏好与安全约束则通过层级马尔可夫毯进行传递。本文重点阐述了三项关键安全机制：第一，自然语言环境下信念与偏好的明确分离；第二，基于资源感知的自由能最小化实现有界理性；第三，模块化主体结构确保组合安全。最后，我们以抽象与推理语料库（ARC）基准为核心，提出了未来研究议程，并设计了验证框架安全属性的实验方案。这一方法为AGI的开发开辟了一条从根本上更安全的发展路径，而非简单地在现有系统上附加安全模块。

> This paper proposes a novel framework for developing safe Artificial General Intelligence (AGI) by combining Active Inference principles with Large Language Models (LLMs). We argue that traditional approaches to AI safety, focused on post-hoc interpretability and reward engineering, have fundamental limitations. We present an architecture where safety guarantees are integrated into the system's core design through transparent belief representations and hierarchical value alignment. Our framework leverages natural language as a medium for representing and manipulating beliefs, enabling direct human oversight while maintaining computational tractability. The architecture implements a multi-agent system where agents self-organize according to Active Inference principles, with preferences and safety constraints flowing through hierarchical Markov blankets. We outline specific mechanisms for ensuring safety, including: (1) explicit separation of beliefs and preferences in natural language, (2) bounded rationality through resource-aware free energy minimization, and (3) compositional safety through modular agent structures. The paper concludes with a research agenda centered on the Abstraction and Reasoning Corpus (ARC) benchmark, proposing experiments to validate our framework's safety properties. Our approach offers a path toward AGI development that is inherently safer, rather than retrofitted with safety measures.

[Arxiv](https://arxiv.org/abs/2508.05766)