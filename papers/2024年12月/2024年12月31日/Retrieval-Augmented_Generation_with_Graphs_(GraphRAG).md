# 图增强检索生成（GraphRAG）

发布时间：2024年12月31日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）与图结构数据结合的应用，即GraphRAG。论文详细介绍了GraphRAG的框架、关键组件以及在不同领域的应用，属于RAG领域的研究。` `信息检索` `图结构`

> Retrieval-Augmented Generation with Graphs (GraphRAG)

# 摘要

> # 摘要
检索增强生成（RAG）通过从外部来源获取额外信息（如知识、技能和工具）来提升下游任务的执行效果。图结构凭借其“节点与边相连”的特性，能够编码大量异构和关系信息，成为RAG在实际应用中的宝贵资源。因此，近年来将RAG与图结合（即GraphRAG）的研究备受关注。然而，与传统RAG不同，传统RAG的检索器、生成器和外部数据源可以在神经嵌入空间中统一设计，而图结构数据的独特性（如多样化的格式和领域特定的关系知识）在设计GraphRAG时带来了独特的挑战。鉴于其广泛适用性、设计挑战以及GraphRAG的快速发展，迫切需要对相关概念和技术进行系统且最新的梳理。基于此，我们提出了一个全面且最新的GraphRAG调查。我们首先定义了一个完整的GraphRAG框架，包括查询处理器、检索器、组织器、生成器和数据源等关键组件。此外，针对不同领域图结构的关系模式差异，我们回顾了为各领域量身定制的GraphRAG技术。最后，我们探讨了研究挑战并提出了跨学科的研究方向。我们的调查仓库公开维护于https://github.com/Graph-RAG/GraphRAG/。

> Retrieval-augmented generation (RAG) is a powerful technique that enhances downstream task execution by retrieving additional information, such as knowledge, skills, and tools from external sources. Graph, by its intrinsic "nodes connected by edges" nature, encodes massive heterogeneous and relational information, making it a golden resource for RAG in tremendous real-world applications. As a result, we have recently witnessed increasing attention on equipping RAG with Graph, i.e., GraphRAG. However, unlike conventional RAG, where the retriever, generator, and external data sources can be uniformly designed in the neural-embedding space, the uniqueness of graph-structured data, such as diverse-formatted and domain-specific relational knowledge, poses unique and significant challenges when designing GraphRAG for different domains. Given the broad applicability, the associated design challenges, and the recent surge in GraphRAG, a systematic and up-to-date survey of its key concepts and techniques is urgently desired. Following this motivation, we present a comprehensive and up-to-date survey on GraphRAG. Our survey first proposes a holistic GraphRAG framework by defining its key components, including query processor, retriever, organizer, generator, and data source. Furthermore, recognizing that graphs in different domains exhibit distinct relational patterns and require dedicated designs, we review GraphRAG techniques uniquely tailored to each domain. Finally, we discuss research challenges and brainstorm directions to inspire cross-disciplinary opportunities. Our survey repository is publicly maintained at https://github.com/Graph-RAG/GraphRAG/.

[Arxiv](https://arxiv.org/abs/2501.00309)