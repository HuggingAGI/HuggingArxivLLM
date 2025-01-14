# 提升检索增强生成：最佳实践探索

发布时间：2025年01月13日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的设计和优化，包括查询扩展、检索策略、对比上下文学习等关键因素。论文的核心内容围绕如何提升RAG系统的性能和应用效果，因此应归类为RAG。` `信息检索`

> Enhancing Retrieval-Augmented Generation: A Study of Best Practices

# 摘要

> # 摘要
检索增强生成（RAG）系统通过将检索机制融入语言模型，显著提升了生成准确且上下文相关响应的能力。然而，RAG系统中各组件和配置的影响仍待深入探索。全面理解这些元素对于定制RAG系统以应对复杂检索任务并确保其在多样化应用中的最佳表现至关重要。本文提出了多种先进的RAG系统设计，包括查询扩展、新颖检索策略以及对比上下文学习RAG。我们系统研究了语言模型大小、提示设计、文档块大小、知识库规模、检索步长、查询扩展技术、对比上下文学习知识库、多语言知识库及句子级聚焦模式检索等关键因素。通过大量实验，我们详细分析了这些因素对响应质量的影响。研究结果为开发RAG系统提供了实用指导，平衡了上下文丰富性与检索生成效率，为在多样化现实场景中构建更具适应性和高性能的RAG框架奠定了基础。代码与实现细节已公开。

> Retrieval-Augmented Generation (RAG) systems have recently shown remarkable advancements by integrating retrieval mechanisms into language models, enhancing their ability to produce more accurate and contextually relevant responses. However, the influence of various components and configurations within RAG systems remains underexplored. A comprehensive understanding of these elements is essential for tailoring RAG systems to complex retrieval tasks and ensuring optimal performance across diverse applications. In this paper, we develop several advanced RAG system designs that incorporate query expansion, various novel retrieval strategies, and a novel Contrastive In-Context Learning RAG. Our study systematically investigates key factors, including language model size, prompt design, document chunk size, knowledge base size, retrieval stride, query expansion techniques, Contrastive In-Context Learning knowledge bases, multilingual knowledge bases, and Focus Mode retrieving relevant context at sentence-level. Through extensive experimentation, we provide a detailed analysis of how these factors influence response quality. Our findings offer actionable insights for developing RAG systems, striking a balance between contextual richness and retrieval-generation efficiency, thereby paving the way for more adaptable and high-performing RAG frameworks in diverse real-world scenarios. Our code and implementation details are publicly available.

[Arxiv](https://arxiv.org/abs/2501.07391)