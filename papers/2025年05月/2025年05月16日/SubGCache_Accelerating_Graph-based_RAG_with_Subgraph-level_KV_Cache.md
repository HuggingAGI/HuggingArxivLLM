# SubGCache：基于子图键值缓存加速图基RAG实现

发布时间：2025年05月16日

`RAG` `人工智能` `大型语言模型`

> SubGCache: Accelerating Graph-based RAG with Subgraph-level KV Cache

# 摘要

> 基于图的检索增强生成（RAG）通过图检索使大型语言模型（LLMs）能够将结构化知识作为上下文输入，从而提升推理的准确性和情境感知能力。我们发现，不同查询可能会检索到相似的子图作为提示，因此提出了SubGCache，旨在通过重用具有相似结构提示（即子图）的查询间的计算来减少推理延迟。具体而言，SubGCache基于子图嵌入对查询进行聚类，为每个簇构建代表子图，并预计算该代表子图的键值（KV）缓存。对于每个查询，如果其检索到的子图属于某个簇，则重用该簇代表子图的预计算KV缓存，从而无需再次计算KV张量，节省计算资源。我们在两个新数据集上进行了实验，涵盖了多个LLM后端和图基RAG框架，结果表明SubGCache能够显著降低推理延迟，同时生成质量相当甚至更优，时间到首令牌（TTFT）时间最多减少了6.68倍。

> Graph-based retrieval-augmented generation (RAG) enables large language models (LLMs) to incorporate structured knowledge via graph retrieval as contextual input, enhancing more accurate and context-aware reasoning. We observe that for different queries, it could retrieve similar subgraphs as prompts, and thus we propose SubGCache, which aims to reduce inference latency by reusing computation across queries with similar structural prompts (i.e., subgraphs). Specifically, SubGCache clusters queries based on subgraph embeddings, constructs a representative subgraph for each cluster, and pre-computes the key-value (KV) cache of the representative subgraph. For each query with its retrieved subgraph within a cluster, it reuses the pre-computed KV cache of the representative subgraph of the cluster without computing the KV tensors again for saving computation. Experiments on two new datasets across multiple LLM backbones and graph-based RAG frameworks demonstrate that SubGCache consistently reduces inference latency with comparable and even improved generation quality, achieving up to 6.68$\times$ reduction in time-to-first-token (TTFT).

[Arxiv](https://arxiv.org/abs/2505.10951)