# 尊重时序-因果一致性：实体-事件知识图谱助力检索增强生成

发布时间：2025年06月06日

`RAG

摘要中详细讨论了RAG方法的改进，特别是针对时间结构文档的处理，提出了新的框架E²RAG，并构建了新的基准测试ChronoQA。这些贡献集中在RAG技术本身，因此属于RAG类别。` `问答系统`

> Respecting Temporal-Causal Consistency: Entity-Event Knowledge Graphs for Retrieval-Augmented Generation

# 摘要

> 基于大型语言模型的检索增强生成（RAG）在处理具有时间结构的叙述性文档时常常表现不佳。标准的无结构RAG方法仅依赖嵌入相似性匹配，缺乏处理时间信息的机制，而知识图谱RAG（KG-RAG）框架将实体压缩为单一节点，忽略了驱动查询的上下文演变。为了 formalize 这一挑战并引起社区关注，我们构建了ChronoQA，这是一个强大的且具有区分度的QA基准，用于在RAG设置下衡量对叙述性文档（如小说）中时间、因果和角色一致性理解的能力。随后我们引入了实体-事件RAG（E²RAG），这是一个双图框架，通过二分映射保持独立的实体和事件子图，从而保留了细粒度推理所需的时间和因果方面。在ChronoQA上，我们的方法优于现有的无结构和基于KG的RAG基线，在因果和角色一致性查询上取得了显著提升。因此，E²RAG为需要基于时间信息的精确答案的任务提供了一条实现更上下文感知检索的实用路径。


> Retrieval-augmented generation (RAG) based on large language models often falters on narrative documents with inherent temporal structures. Standard unstructured RAG methods rely solely on embedding-similarity matching and lack any general mechanism to encode or exploit chronological information, while knowledge graph RAG (KG-RAG) frameworks collapse every mention of an entity into a single node, erasing the evolving context that drives many queries. To formalize this challenge and draw the community's attention, we construct ChronoQA, a robust and discriminative QA benchmark that measures temporal, causal, and character consistency understanding in narrative documents (e.g., novels) under the RAG setting. We then introduce Entity-Event RAG (E^2RAG), a dual-graph framework that keeps separate entity and event subgraphs linked by a bipartite mapping, thereby preserving the temporal and causal facets needed for fine-grained reasoning. Across ChronoQA, our approach outperforms state-of-the-art unstructured and KG-based RAG baselines, with notable gains on causal and character consistency queries. E^2RAG therefore offers a practical path to more context-aware retrieval for tasks that require precise answers grounded in chronological information.

[Arxiv](https://arxiv.org/abs/2506.05939)