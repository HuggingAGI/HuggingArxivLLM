# DoTA-RAG: 动态思想聚合增强生成

发布时间：2025年06月14日

`RAG` `大规模数据处理`

> DoTA-RAG: Dynamic of Thought Aggregation RAG

# 摘要

> 本文介绍了DoTA-RAG（Dynamic-of-Thought Aggregation RAG），一个专为高吞吐量和大规模网络知识索引优化的检索增强生成系统。传统RAG流水线在处理大规模、多样化数据时常常面临高延迟和准确性不足的问题。DoTA-RAG通过三阶段流水线解决了这些挑战：查询重写、动态路由到专用子索引以及多阶段检索和排序。我们进一步通过评估并选择更优的嵌入模型，重新嵌入大规模的FineWeb-10BT语料库，提升了检索效果。此外，我们创建了一个多样化的问答数据集，包含通过DataMorgana框架生成的500个问题，覆盖了广泛的WebOrganizer主题和格式。实验结果显示，DoTA-RAG在保持低延迟的同时，将答案正确性得分从0.752（基线，使用LiveRAG预建向量存储）提升到了1.478，并在Live Challenge Day上实现了0.929的正确性得分。这些结果凸显了DoTA-RAG在需要快速、可靠访问大规模且不断演变的知识源领域中进行实际部署的潜力。

> In this paper, we introduce DoTA-RAG (Dynamic-of-Thought Aggregation RAG), a retrieval-augmented generation system optimized for high-throughput, large-scale web knowledge indexes. Traditional RAG pipelines often suffer from high latency and limited accuracy over massive, diverse datasets. DoTA-RAG addresses these challenges with a three-stage pipeline: query rewriting, dynamic routing to specialized sub-indexes, and multi-stage retrieval and ranking. We further enhance retrieval by evaluating and selecting a superior embedding model, re-embedding the large FineWeb-10BT corpus. Moreover, we create a diverse Q&A dataset of 500 questions generated via the DataMorgana setup across a broad range of WebOrganizer topics and formats. DoTA-RAG improves the answer correctness score from 0.752 (baseline, using LiveRAG pre-built vector store) to 1.478 while maintaining low latency, and it achieves a 0.929 correctness score on the Live Challenge Day. These results highlight DoTA-RAG's potential for practical deployment in domains requiring fast, reliable access to large and evolving knowledge sources.

[Arxiv](https://arxiv.org/abs/2506.12571)