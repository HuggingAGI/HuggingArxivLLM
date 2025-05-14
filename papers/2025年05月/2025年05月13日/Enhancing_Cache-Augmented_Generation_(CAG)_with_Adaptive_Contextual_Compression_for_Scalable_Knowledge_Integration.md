# 通过自适应上下文压缩提升缓存增强生成（CAG），实现可扩展知识整合

发布时间：2025年05月13日

`LLM应用` `信息检索` `知识管理`

> Enhancing Cache-Augmented Generation (CAG) with Adaptive Contextual Compression for Scalable Knowledge Integration

# 摘要

> 大型语言模型 (LLMs) 的快速发展为知识密集型任务带来了全新的解决方案。其中，缓存增强生成 (CAG) 作为一种有前景的替代方案，逐渐取代了检索增强生成 (RAG)。CAG 通过预先将知识加载到模型的上下文中，最大限度地减少了检索延迟并简化了系统设计。然而，将 CAG 扩展到大规模且动态变化的知识库仍然面临挑战。本文介绍了自适应上下文压缩 (ACC)，这是一种创新技术，旨在动态压缩和管理上下文输入，从而充分利用现代 LLM 的扩展内存能力。为了进一步克服独立 CAG 的局限性，我们提出了一种混合 CAG-RAG 框架，该框架通过选择性检索来增强预加载的上下文，在需要额外信息的情况下提供支持。在多样化的数据集上进行的全面评估凸显了所提方法在提升可扩展性、优化效率以及改进多跳推理性能方面的有效性，为现实世界的知识整合挑战提供了切实可行的解决方案。

> The rapid progress in large language models (LLMs) has paved the way for novel approaches in knowledge-intensive tasks. Among these, Cache-Augmented Generation (CAG) has emerged as a promising alternative to Retrieval-Augmented Generation (RAG). CAG minimizes retrieval latency and simplifies system design by preloading knowledge into the model's context. However, challenges persist in scaling CAG to accommodate large and dynamic knowledge bases effectively. This paper introduces Adaptive Contextual Compression (ACC), an innovative technique designed to dynamically compress and manage context inputs, enabling efficient utilization of the extended memory capabilities of modern LLMs. To further address the limitations of standalone CAG, we propose a Hybrid CAG-RAG Framework, which integrates selective retrieval to augment preloaded contexts in scenarios requiring additional information. Comprehensive evaluations on diverse datasets highlight the proposed methods' ability to enhance scalability, optimize efficiency, and improve multi-hop reasoning performance, offering practical solutions for real-world knowledge integration challenges.

[Arxiv](https://arxiv.org/abs/2505.08261)