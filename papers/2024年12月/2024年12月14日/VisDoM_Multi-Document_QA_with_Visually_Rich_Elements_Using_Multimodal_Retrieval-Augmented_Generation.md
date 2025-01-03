# VisDoM: 基于多模态检索增强生成的多文档问答系统，专为视觉丰富元素设计

发布时间：2024年12月14日

`RAG

理由：这篇论文介绍了VisDoMRAG，一种创新的多模态检索增强生成（RAG）方法，结合了视觉与文本的检索增强生成技术。该方法通过多步推理和一致性约束的模态融合机制，提升了多模态文档问答系统的性能。因此，这篇论文主要关注的是检索增强生成（RAG）技术在多模态文档问答中的应用，属于RAG分类。` `文档处理` `问答系统`

> VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation

# 摘要

> # 摘要
理解多文档集合中的信息，尤其是包含丰富视觉元素的文档，对基于文档的问答系统至关重要。本文推出VisDoMBench，首个评估多文档环境下问答系统的综合基准，涵盖表格、图表和演示文稿等丰富多模态内容。我们提出VisDoMRAG，一种创新的多模态检索增强生成（RAG）方法，融合视觉与文本RAG，结合强大的视觉检索与复杂语言推理。VisDoMRAG采用多步推理，包括证据整理和思维链推理，并行处理文本与视觉RAG管道。其核心创新在于一致性约束的模态融合机制，推理时对齐跨模态推理过程，生成一致答案。这不仅提升了关键信息跨模态分布场景的准确性，还通过隐式上下文归因增强了答案可验证性。通过开源与专有大型语言模型的广泛实验，我们在VisDoMBench上对顶尖文档QA方法进行基准测试。结果显示，VisDoMRAG在端到端多模态文档QA中表现优异，超越单模态和长上下文LLM基线12-20%。

> Understanding information from a collection of multiple documents, particularly those with visually rich elements, is important for document-grounded question answering. This paper introduces VisDoMBench, the first comprehensive benchmark designed to evaluate QA systems in multi-document settings with rich multimodal content, including tables, charts, and presentation slides. We propose VisDoMRAG, a novel multimodal Retrieval Augmented Generation (RAG) approach that simultaneously utilizes visual and textual RAG, combining robust visual retrieval capabilities with sophisticated linguistic reasoning. VisDoMRAG employs a multi-step reasoning process encompassing evidence curation and chain-of-thought reasoning for concurrent textual and visual RAG pipelines. A key novelty of VisDoMRAG is its consistency-constrained modality fusion mechanism, which aligns the reasoning processes across modalities at inference time to produce a coherent final answer. This leads to enhanced accuracy in scenarios where critical information is distributed across modalities and improved answer verifiability through implicit context attribution. Through extensive experiments involving open-source and proprietary large language models, we benchmark state-of-the-art document QA methods on VisDoMBench. Extensive results show that VisDoMRAG outperforms unimodal and long-context LLM baselines for end-to-end multimodal document QA by 12-20%.

[Arxiv](https://arxiv.org/abs/2412.10704)