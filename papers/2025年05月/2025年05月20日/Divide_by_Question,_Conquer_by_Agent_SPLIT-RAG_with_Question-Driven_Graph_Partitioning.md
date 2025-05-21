# 以问题划分，以智能体取胜：基于问题驱动的图划分SPLIT-RAG方法

发布时间：2025年05月20日

`RAG` `知识图谱` `问答系统`

> Divide by Question, Conquer by Agent: SPLIT-RAG with Question-Driven Graph Partitioning

# 摘要

> 检索增强生成（RAG）系统赋予大型语言模型（LLMs）外部知识的能力，但在扩展到大型知识图谱时，面临着效率与准确性之间的权衡问题。现有方法通常依赖整体化的图检索，导致简单查询出现不必要的延迟，而复杂多跳问题则出现碎片化推理。为了解决这些问题，本文提出SPLIT-RAG，一个多智能体RAG框架，通过问题驱动的语义图划分和协作子图检索来克服这些限制。

创新框架首先实现语义信息划分，然后利用类型专用知识库实现多智能体RAG。基于属性的图分割成功地将知识图谱划分为语义连贯的子图，确保子图与不同查询类型对齐，同时轻量级LLM代理被分配到划分后的子图中，并且仅在检索时激活相关分区，从而减少搜索空间并提高效率。最后，层次化合并模块通过逻辑验证解决子图衍生答案之间的不一致性。大量实验验证表明，与现有方法相比，SPLIT-RAG取得了显著改进。

> Retrieval-Augmented Generation (RAG) systems empower large language models (LLMs) with external knowledge, yet struggle with efficiency-accuracy trade-offs when scaling to large knowledge graphs. Existing approaches often rely on monolithic graph retrieval, incurring unnecessary latency for simple queries and fragmented reasoning for complex multi-hop questions. To address these challenges, this paper propose SPLIT-RAG, a multi-agent RAG framework that addresses these limitations with question-driven semantic graph partitioning and collaborative subgraph retrieval. The innovative framework first create Semantic Partitioning of Linked Information, then use the Type-Specialized knowledge base to achieve Multi-Agent RAG. The attribute-aware graph segmentation manages to divide knowledge graphs into semantically coherent subgraphs, ensuring subgraphs align with different query types, while lightweight LLM agents are assigned to partitioned subgraphs, and only relevant partitions are activated during retrieval, thus reduce search space while enhancing efficiency. Finally, a hierarchical merging module resolves inconsistencies across subgraph-derived answers through logical verifications. Extensive experimental validation demonstrates considerable improvements compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2505.13994)