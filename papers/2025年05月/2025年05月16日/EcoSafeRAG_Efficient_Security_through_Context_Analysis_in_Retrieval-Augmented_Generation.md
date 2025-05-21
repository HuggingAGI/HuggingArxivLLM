# # EcoSafeRAG：通过上下文分析实现高效安全性在检索增强生成模型中的应用

发布时间：2025年05月16日

`RAG`

> EcoSafeRAG: Efficient Security through Context Analysis in Retrieval-Augmented Generation

# 摘要

> RAG通过整合外部知识，弥补了LLMs静态知识的局限性，生成的响应更具事实正确性和针对性。然而，它同时也引入了新的攻击面，例如语料投毒。现有防御方法多依赖模型内部知识，这与RAG设计理念相悖。EcoSafeRAG采用句子级处理和诱饵引导的上下文多样性检测，通过分析候选文档的上下文多样性识别恶意内容，无需依赖LLM内部知识。实验表明，EcoSafeRAG实现了即插即用的最先进安全性，同时提升了清洁场景下RAG的性能，运营成本保持在合理范围（相较于 Vanilla RAG，延迟增加1.2倍，token减少48%-80%）。

> Retrieval-Augmented Generation (RAG) compensates for the static knowledge limitations of Large Language Models (LLMs) by integrating external knowledge, producing responses with enhanced factual correctness and query-specific contextualization. However, it also introduces new attack surfaces such as corpus poisoning at the same time. Most of the existing defense methods rely on the internal knowledge of the model, which conflicts with the design concept of RAG. To bridge the gap, EcoSafeRAG uses sentence-level processing and bait-guided context diversity detection to identify malicious content by analyzing the context diversity of candidate documents without relying on LLM internal knowledge. Experiments show EcoSafeRAG delivers state-of-the-art security with plug-and-play deployment, simultaneously improving clean-scenario RAG performance while maintaining practical operational costs (relatively 1.2$\times$ latency, 48\%-80\% token reduction versus Vanilla RAG).

[Arxiv](https://arxiv.org/abs/2505.13506)