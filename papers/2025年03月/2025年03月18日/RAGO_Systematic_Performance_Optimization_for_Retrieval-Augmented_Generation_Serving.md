# RAGO：系统性优化检索增强生成服务性能

发布时间：2025年03月18日

`RAG` `人工智能` `系统优化`

> RAGO: Systematic Performance Optimization for Retrieval-Augmented Generation Serving

# 摘要

> 检索增强生成（RAG）通过结合大型语言模型（LLMs）与外部知识库的检索功能，正在成为一种可靠的LLM服务方式。然而，由于大量RAG变体的迅速涌现以及各变体之间工作负载特性的显著差异，高效的RAG服务仍面临诸多挑战。本文在推进RAG服务方面做出了三项基础性贡献。首先，我们提出了一种结构化的抽象框架RAGSchema，用于捕捉各种RAG算法的共同特征，为其性能优化奠定基础。其次，我们分析了多个具有不同RAGSchema特征的代表性RAG工作负载，揭示了这些工作负载在性能表现上的显著差异。最后，为了应对这种性能差异并满足多样化的性能需求，我们提出了RAGO（检索增强生成优化器），一个旨在实现高效RAG服务的系统优化框架。我们的评估结果显示，相较于基于LLM系统扩展构建的RAG系统，RAGO实现了每芯片QPS提升最高达2倍，以及首次令牌生成延迟降低55%。

> Retrieval-augmented generation (RAG), which combines large language models (LLMs) with retrievals from external knowledge databases, is emerging as a popular approach for reliable LLM serving. However, efficient RAG serving remains an open challenge due to the rapid emergence of many RAG variants and the substantial differences in workload characteristics across them. In this paper, we make three fundamental contributions to advancing RAG serving. First, we introduce RAGSchema, a structured abstraction that captures the wide range of RAG algorithms, serving as a foundation for performance optimization. Second, we analyze several representative RAG workloads with distinct RAGSchema, revealing significant performance variability across these workloads. Third, to address this variability and meet diverse performance requirements, we propose RAGO (Retrieval-Augmented Generation Optimizer), a system optimization framework for efficient RAG serving. Our evaluation shows that RAGO achieves up to a 2x increase in QPS per chip and a 55% reduction in time-to-first-token latency compared to RAG systems built on LLM-system extensions.

[Arxiv](https://arxiv.org/abs/2503.14649)