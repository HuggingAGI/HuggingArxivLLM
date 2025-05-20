# # 摘要
深入解析基于LLM的检索增强生成中的知识利用原理

发布时间：2025年05月17日

`RAG` `问答系统` `智能助手`

> Unveiling Knowledge Utilization Mechanisms in LLM-based Retrieval-Augmented Generation

# 摘要

> 针对大型语言模型（LLMs）参数化知识的局限性，检索增强生成（RAG）作为一种有效手段被广泛应用，显著扩展了模型的知识边界。在开放域问答等知识密集型任务中，RAG已展现出巨大潜力，并逐步在复杂任务和智能助手中得到更广泛应用。尽管RAG技术取得了显著进展，但其在LLM中的知识利用机制仍有待深入探索。本研究系统性地揭示了LLMs在RAG场景中整合内部（参数化）与外部（检索）知识的核心机制。通过宏观层面的知识流分析和微观层面的模块功能研究，我们首次将知识利用过程分解为LLM层内的四个关键阶段：知识精炼、提取、表达和竞争。研究发现，段落的相关性主导了知识在这些阶段的流动路径。我们创新性地提出知识激活概率熵（KAPE）方法，用于识别与内部或外部知识相关的神经元。通过选择性停用特定神经元，我们实现了模型对知识源依赖的定向调整。此外，研究发现多头注意力和多层感知机层在知识形成过程中具有独特且互补的作用。这些发现为提升RAG增强型LLMs的可解释性和可靠性提供了理论基础，为开发更强大、更透明的知识密集型生成解决方案指明了方向。

> Considering the inherent limitations of parametric knowledge in large language models (LLMs), retrieval-augmented generation (RAG) is widely employed to expand their knowledge scope. Since RAG has shown promise in knowledge-intensive tasks like open-domain question answering, its broader application to complex tasks and intelligent assistants has further advanced its utility. Despite this progress, the underlying knowledge utilization mechanisms of LLM-based RAG remain underexplored. In this paper, we present a systematic investigation of the intrinsic mechanisms by which LLMs integrate internal (parametric) and external (retrieved) knowledge in RAG scenarios. Specially, we employ knowledge stream analysis at the macroscopic level, and investigate the function of individual modules at the microscopic level. Drawing on knowledge streaming analyses, we decompose the knowledge utilization process into four distinct stages within LLM layers: knowledge refinement, knowledge elicitation, knowledge expression, and knowledge contestation. We further demonstrate that the relevance of passages guides the streaming of knowledge through these stages. At the module level, we introduce a new method, knowledge activation probability entropy (KAPE) for neuron identification associated with either internal or external knowledge. By selectively deactivating these neurons, we achieve targeted shifts in the LLM's reliance on one knowledge source over the other. Moreover, we discern complementary roles for multi-head attention and multi-layer perceptron layers during knowledge formation. These insights offer a foundation for improving interpretability and reliability in retrieval-augmented LLMs, paving the way for more robust and transparent generative solutions in knowledge-intensive domains.

[Arxiv](https://arxiv.org/abs/2505.11995)