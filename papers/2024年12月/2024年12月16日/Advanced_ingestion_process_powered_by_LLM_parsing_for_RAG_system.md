# 基于LLM解析的RAG系统高级数据摄取流程

发布时间：2024年12月16日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统在处理多模态文档时的挑战，并提出了一种创新的多策略解析方法。该方法利用LLM驱动的OCR技术和基于节点的提取技术，显著提升了文档理解和检索能力。因此，这篇论文应归类为RAG。` `文档管理` `信息检索`

> Advanced ingestion process powered by LLM parsing for RAG system

# 摘要

> 检索增强生成（RAG）系统在处理结构复杂多变的多模态文档时存在困难。本文提出了一种创新的多策略解析方法，利用LLM驱动的OCR技术，从演示文稿、高文本密度文件等各类文档中提取内容，无论是否经过扫描。该方法采用基于节点的提取技术，建立不同信息类型之间的关联，并生成上下文感知的元数据。通过引入多模态组装代理和灵活的嵌入策略，系统显著提升了文档理解和检索能力。在多个知识库上的实验验证了该方法的有效性，显著提高了答案的相关性和信息的准确性。

> Retrieval Augmented Generation (RAG) systems struggle with processing multimodal documents of varying structural complexity. This paper introduces a novel multi-strategy parsing approach using LLM-powered OCR to extract content from diverse document types, including presentations and high text density files both scanned or not. The methodology employs a node-based extraction technique that creates relationships between different information types and generates context-aware metadata. By implementing a Multimodal Assembler Agent and a flexible embedding strategy, the system enhances document comprehension and retrieval capabilities. Experimental evaluations across multiple knowledge bases demonstrate the approach's effectiveness, showing improvements in answer relevancy and information faithfulness.

[Arxiv](https://arxiv.org/abs/2412.15262)