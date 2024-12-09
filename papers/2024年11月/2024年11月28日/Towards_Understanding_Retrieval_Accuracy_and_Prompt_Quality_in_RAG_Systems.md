# 探究 RAG 系统中的检索准确性与提示质量

发布时间：2024年11月28日

`RAG` `软件工程`

> Towards Understanding Retrieval Accuracy and Prompt Quality in RAG Systems

# 摘要

> 检索增强生成（RAG）是提升大型语言模型（LLMs）能力的关键技术，在众多任务中成效显著。然而，由 LLM 驱动的 RAG 系统虽性能出色，但在稳定性和可靠性上存在独特挑战。其复杂性给开发人员设计、维护和优化有效的 RAG 系统带来阻碍。所以，搞清楚 RAG 的设计如何影响其性能至关重要。在本次工作中，我们针对更好地理解 RAG 系统的机制展开早期探索性研究，涵盖三个代码数据集、三个问答数据集和两个 LLM。我们聚焦四个设计因素：检索文档类型、检索召回率、文档选择和提示技术。我们的研究揭示了每个因素对系统正确性和置信度的影响，为开发精准可靠的 RAG 系统提供了宝贵见解。基于这些发现，我们给出九条可操作的指南，用于检测缺陷和优化 RAG 系统的性能。我们期望我们的早期探索能推动工程领域的进一步发展，改进和维护由 LLM 驱动的智能软件系统，从而提升效率和可靠性。

> Retrieval-Augmented Generation (RAG) is a pivotal technique for enhancing the capability of large language models (LLMs) and has demonstrated promising efficacy across a diverse spectrum of tasks. While LLM-driven RAG systems show superior performance, they face unique challenges in stability and reliability. Their complexity hinders developers' efforts to design, maintain, and optimize effective RAG systems. Therefore, it is crucial to understand how RAG's performance is impacted by its design. In this work, we conduct an early exploratory study toward a better understanding of the mechanism of RAG systems, covering three code datasets, three QA datasets, and two LLMs. We focus on four design factors: retrieval document type, retrieval recall, document selection, and prompt techniques. Our study uncovers how each factor impacts system correctness and confidence, providing valuable insights for developing an accurate and reliable RAG system. Based on these findings, we present nine actionable guidelines for detecting defects and optimizing the performance of RAG systems. We hope our early exploration can inspire further advancements in engineering, improving and maintaining LLM-driven intelligent software systems for greater efficiency and reliability.

[Arxiv](https://arxiv.org/abs/2411.19463)