# SlimRAG：一种通过基于实体感知的上下文选择实现的无需图结构的检索方法

发布时间：2025年06月15日

`RAG` `问答系统`

> SlimRAG: Retrieval without Graphs via Entity-Aware Context Selection

# 摘要

> 检索增强生成（RAG）通过在推理时融合外部知识来提升语言模型的能力。然而，基于图的RAG系统常常面临结构开销大和检索不精准的问题：它们需要耗费大量资源构建实体链接和关系抽取的流水线，却常常返回充斥着 loosely related 或者 tangential 内容的子图。这一问题源于一个根本性缺陷——语义相似性并不等同于语义相关性。我们提出了SlimRAG，一种轻量级的无图检索框架。SlimRAG用一个简单但有效的基于实体的机制取代了结构繁重的组件。在索引阶段，它基于语义嵌入构建一个紧凑的实体到文本块的映射表。在查询阶段，它识别关键实体，检索并评分相关文本块，组装出一个简洁且语境相关的输入——无需图遍历或边构建。为了量化检索效率，我们提出了相对索引令牌利用率（RITU），一个衡量检索内容紧凑性的指标。在多个问答基准测试中，SlimRAG在准确率上超越了强大的平面和基于图的基线模型，同时减少了索引大小和RITU（例如16.31 vs. 56+），凸显了无结构、以实体为中心的上下文选择的价值。代码即将发布。https://github.com/continue-ai-company/SlimRAG

> Retrieval-Augmented Generation (RAG) enhances language models by incorporating external knowledge at inference time. However, graph-based RAG systems often suffer from structural overhead and imprecise retrieval: they require costly pipelines for entity linking and relation extraction, yet frequently return subgraphs filled with loosely related or tangential content. This stems from a fundamental flaw -- semantic similarity does not imply semantic relevance. We introduce SlimRAG, a lightweight framework for retrieval without graphs. SlimRAG replaces structure-heavy components with a simple yet effective entity-aware mechanism. At indexing time, it constructs a compact entity-to-chunk table based on semantic embeddings. At query time, it identifies salient entities, retrieves and scores associated chunks, and assembles a concise, contextually relevant input -- without graph traversal or edge construction. To quantify retrieval efficiency, we propose Relative Index Token Utilization (RITU), a metric measuring the compactness of retrieved content. Experiments across multiple QA benchmarks show that SlimRAG outperforms strong flat and graph-based baselines in accuracy while reducing index size and RITU (e.g., 16.31 vs. 56+), highlighting the value of structure-free, entity-centric context selection. The code will be released soon. https://github.com/continue-ai-company/SlimRAG

[Arxiv](https://arxiv.org/abs/2506.17288)