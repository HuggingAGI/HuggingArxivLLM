# # UniversalRAG: Retrieval-Augmented Generation over Multiple Corpora with Diverse Modalities and Granularities
# 跨多语料库的多模态多粒度检索增强生成

发布时间：2025年04月29日

`RAG` `跨模态处理`

> UniversalRAG: Retrieval-Augmented Generation over Multiple Corpora with Diverse Modalities and Granularities

# 摘要

> 检索增强生成（RAG）通过结合外部知识显著提升了生成内容的事实准确性，然而现有方法大多局限于单一文本语料库。尽管已有研究尝试将RAG扩展到图像和视频等其他模态，但这些方法通常只能在单一模态的语料库上运行。然而，现实中的查询往往需要多样化的知识类型，单一模态的知识来源难以满足需求。

为解决这一问题，我们提出了UniversalRAG——一个全新的跨模态知识整合框架。该框架能够从多种异构来源中检索和整合不同模态和粒度的知识。通过观察发现，将所有模态强制映射到一个统一的表示空间会导致模态差距，即检索结果往往倾向于与查询相同模态的内容。针对这一问题，我们设计了一种模态感知路由机制，能够动态识别最合适的模态语料库，并在其中进行精准检索。

此外，我们还对每个模态进行了多粒度划分，使检索能够根据查询的复杂性和范围进行自适应调整。在涵盖文本、图像、视频等多模态的8个基准测试中，UniversalRAG展现了显著的性能优势，超越了现有特定模态和统一表示的基线方法。

> Retrieval-Augmented Generation (RAG) has shown substantial promise in improving factual accuracy by grounding model responses with external knowledge relevant to queries. However, most existing RAG approaches are limited to a text-only corpus, and while recent efforts have extended RAG to other modalities such as images and videos, they typically operate over a single modality-specific corpus. In contrast, real-world queries vary widely in the type of knowledge they require, which a single type of knowledge source cannot address. To address this, we introduce UniversalRAG, a novel RAG framework designed to retrieve and integrate knowledge from heterogeneous sources with diverse modalities and granularities. Specifically, motivated by the observation that forcing all modalities into a unified representation space derived from a single combined corpus causes a modality gap, where the retrieval tends to favor items from the same modality as the query, we propose a modality-aware routing mechanism that dynamically identifies the most appropriate modality-specific corpus and performs targeted retrieval within it. Also, beyond modality, we organize each modality into multiple granularity levels, enabling fine-tuned retrieval tailored to the complexity and scope of the query. We validate UniversalRAG on 8 benchmarks spanning multiple modalities, showing its superiority over modality-specific and unified baselines.

[Arxiv](https://arxiv.org/abs/2504.20734)