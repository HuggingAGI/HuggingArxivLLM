# 以查询为中心的图检索增强生成

发布时间：2025年09月25日

`RAG` `基础理论`

> Query-Centric Graph Retrieval Augmented Generation

# 摘要

> 基于图的检索增强生成（RAG）为大型语言模型（LLMs）补充外部知识，助力长上下文理解与多跳推理，但现有方法存在粒度困境：细粒度实体级图不仅token成本高昂，还会丢失上下文；而粗粒度文档级图则难以捕捉细微关系。为此，我们提出以查询为中心的图RAG框架QCG-RAG，实现查询粒度的索引与多跳块检索。该方法借助Doc2Query和Doc2Query--构建粒度可控的以查询为中心的图，提升了图的质量与可解释性。随后，定制化多跳检索机制基于生成的查询筛选相关块。在LiHuaWorld与MultiHop-RAG数据集上的实验结果显示，QCG-RAG在问答准确性上持续优于现有基于块和图的RAG方法，为多跳推理开辟了新范式。

> Graph-based retrieval-augmented generation (RAG) enriches large language models (LLMs) with external knowledge for long-context understanding and multi-hop reasoning, but existing methods face a granularity dilemma: fine-grained entity-level graphs incur high token costs and lose context, while coarse document-level graphs fail to capture nuanced relations. We introduce QCG-RAG, a query-centric graph RAG framework that enables query-granular indexing and multi-hop chunk retrieval. Our query-centric approach leverages Doc2Query and Doc2Query{-}{-} to construct query-centric graphs with controllable granularity, improving graph quality and interpretability. A tailored multi-hop retrieval mechanism then selects relevant chunks via the generated queries. Experiments on LiHuaWorld and MultiHop-RAG show that QCG-RAG consistently outperforms prior chunk-based and graph-based RAG methods in question answering accuracy, establishing a new paradigm for multi-hop reasoning.

[Arxiv](https://arxiv.org/abs/2509.21237)