# 大型语言模型上下文工程的研究综述

发布时间：2025年07月17日

`LLM应用` `人工智能` `上下文工程`

> A Survey of Context Engineering for Large Language Models

# 摘要

> 大语言模型（LLMs）的表现从根本上取决于推理时提供的上下文信息。本文介绍了一门超越简单提示设计的正式学科——上下文工程，它系统性地优化了LLMs的信息负载。我们提出了一个全面的分类法，将上下文工程分解为基础组件及其在智能系统中的复杂实现。首先，我们探讨了基础组件：上下文检索与生成、上下文处理和上下文管理。然后，我们研究了这些组件如何在架构上集成，以创建复杂的系统实现：检索增强生成（RAG）、记忆系统和工具集成推理，以及多智能体系统。通过分析超过1300篇研究论文，本调查不仅为该领域奠定了技术路线图，还揭示了一个关键的研究空白：模型能力之间存在根本性的不对称。尽管当前模型通过先进的上下文工程增强了能力，在理解复杂上下文方面表现出色，但在生成同样复杂和长篇的输出方面却存在明显局限。解决这一空白是未来研究的关键优先事项。最终，本调查为推进上下文感知AI的研究人员和工程师提供了一个统一的框架。
    

> The performance of Large Language Models (LLMs) is fundamentally determined by the contextual information provided during inference. This survey introduces Context Engineering, a formal discipline that transcends simple prompt design to encompass the systematic optimization of information payloads for LLMs. We present a comprehensive taxonomy decomposing Context Engineering into its foundational components and the sophisticated implementations that integrate them into intelligent systems. We first examine the foundational components: context retrieval and generation, context processing and context management. We then explore how these components are architecturally integrated to create sophisticated system implementations: retrieval-augmented generation (RAG), memory systems and tool-integrated reasoning, and multi-agent systems. Through this systematic analysis of over 1300 research papers, our survey not only establishes a technical roadmap for the field but also reveals a critical research gap: a fundamental asymmetry exists between model capabilities. While current models, augmented by advanced context engineering, demonstrate remarkable proficiency in understanding complex contexts, they exhibit pronounced limitations in generating equally sophisticated, long-form outputs. Addressing this gap is a defining priority for future research. Ultimately, this survey provides a unified framework for both researchers and engineers advancing context-aware AI.

[Arxiv](https://arxiv.org/abs/2507.13334)