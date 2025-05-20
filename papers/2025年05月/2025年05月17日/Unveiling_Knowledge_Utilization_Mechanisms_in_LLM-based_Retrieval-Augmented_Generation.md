# 揭示基于 LLM 的检索增强生成中的知识利用机制

发布时间：2025年05月17日

`RAG` `智能助手` `问答系统`

> Unveiling Knowledge Utilization Mechanisms in LLM-based Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）的参数化知识存在局限性，因此检索增强生成（RAG）被广泛应用以扩展其知识范围。RAG在开放领域问答等知识密集型任务中表现出色，进一步推动了其在复杂任务和智能助手中的应用。然而，基于LLMs的RAG的知识利用机制仍待深入研究。本文系统性地探讨了LLMs在RAG场景下整合内部（参数化）和外部（检索）知识的内在机制。我们从宏观层面进行知识流分析，并在微观层面研究各个模块的功能。通过知识流分析，我们将知识利用过程分解为LLM层内的四个阶段：知识精炼、知识提取、知识表达和知识竞争。我们发现，段落的相关性决定了知识流经这些阶段的方式。在模块层面，我们提出了一种新方法——知识激活概率熵（KAPE），用于识别与内部或外部知识相关的神经元。通过选择性停用这些神经元，我们实现了LLM对知识来源的定向依赖转移。此外，我们发现多头注意力层和多层感知机层在知识形成过程中具有互补作用。这些发现为提高检索增强型LLMs的可解释性和可靠性奠定了基础，为知识密集型领域提供了更强大、更透明的生成解决方案。

> Considering the inherent limitations of parametric knowledge in large language models (LLMs), retrieval-augmented generation (RAG) is widely employed to expand their knowledge scope. Since RAG has shown promise in knowledge-intensive tasks like open-domain question answering, its broader application to complex tasks and intelligent assistants has further advanced its utility. Despite this progress, the underlying knowledge utilization mechanisms of LLM-based RAG remain underexplored. In this paper, we present a systematic investigation of the intrinsic mechanisms by which LLMs integrate internal (parametric) and external (retrieved) knowledge in RAG scenarios. Specially, we employ knowledge stream analysis at the macroscopic level, and investigate the function of individual modules at the microscopic level. Drawing on knowledge streaming analyses, we decompose the knowledge utilization process into four distinct stages within LLM layers: knowledge refinement, knowledge elicitation, knowledge expression, and knowledge contestation. We further demonstrate that the relevance of passages guides the streaming of knowledge through these stages. At the module level, we introduce a new method, knowledge activation probability entropy (KAPE) for neuron identification associated with either internal or external knowledge. By selectively deactivating these neurons, we achieve targeted shifts in the LLM's reliance on one knowledge source over the other. Moreover, we discern complementary roles for multi-head attention and multi-layer perceptron layers during knowledge formation. These insights offer a foundation for improving interpretability and reliability in retrieval-augmented LLMs, paving the way for more robust and transparent generative solutions in knowledge-intensive domains.

[Arxiv](https://arxiv.org/abs/2505.11995)