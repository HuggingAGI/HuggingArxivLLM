# # RADIANT: 检索增强实体上下文对齐（Retrieval Augmented Entity-context Alignment）——引入RAG能力和实体上下文差异

发布时间：2025年06月28日

`RAG` `知识图谱` `问答系统`

> RADIANT: Retrieval AugmenteD entIty-context AligNmenT -- Introducing RAG-ability and Entity-Context Divergence

# 摘要

> 随着大语言模型（LLMs）的不断突破，检索增强生成（RAG）通过将外部知识融入生成过程，成为提升事实准确性的重要技术。然而，LLMs 在将检索到的证据准确融入生成内容方面表现欠佳，导致事实不一致的问题。为量化这一差距，我们提出了实体-上下文差异（ECD）指标，用于评估检索信息在模型输出中的准确反映程度。通过对当代 LLMs 在检索增强场景下事实一致性能力的系统性评估，我们发现大多数模型的 RAG 能力仍有待提升，尤其是在实体保留和上下文保真方面。本文提出的 Radiant 框架，通过将 RAG 与对齐机制相结合，提供了一个优化检索证据与生成内容交互的全新方案。Radiant 基于直接偏好优化（DPO）进行拓展，教导 LLMs 更有效地将额外信息融入生成内容。作为一种行为校正机制，Radiant 在噪声网络上下文、知识冲突以及幻觉减少等多种检索场景中均能显著提升 RAG 的表现，从而生成更加可靠、上下文相关且事实连贯的内容。

> As Large Language Models (LLMs) continue to advance, Retrieval-Augmented Generation (RAG) has emerged as a vital technique to enhance factual accuracy by integrating external knowledge into the generation process. However, LLMs often fail to faithfully integrate retrieved evidence into their generated responses, leading to factual inconsistencies. To quantify this gap, we introduce Entity-Context Divergence (ECD), a metric that measures the extent to which retrieved information is accurately reflected in model outputs. We systematically evaluate contemporary LLMs on their ability to preserve factual consistency in retrieval-augmented settings, a capability we define as RAG-ability. Our empirical analysis reveals that RAG-ability remains low across most LLMs, highlighting significant challenges in entity retention and context fidelity. This paper introduces Radiant (Retrieval AugmenteD entIty-context AligNmenT), a novel framework that merges RAG with alignment designed to optimize the interplay between retrieved evidence and generated content. Radiant extends Direct Preference Optimization (DPO) to teach LLMs how to integrate provided additional information into subsequent generations. As a behavior correction mechanism, Radiant boosts RAG performance across varied retrieval scenarios, such as noisy web contexts, knowledge conflicts, and hallucination reduction. This enables more reliable, contextually grounded, and factually coherent content generation.

[Arxiv](https://arxiv.org/abs/2507.02949)