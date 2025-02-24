# PathRAG：通过关系路径优化的基于图检索增强生成方法。

发布时间：2025年02月18日

`RAG` `问答系统`

> PathRAG: Pruning Graph-based Retrieval Augmented Generation with Relational Paths

# 摘要

> 检索增强生成（RAG）通过从外部数据库中检索知识，显著提升了大型语言模型（LLMs）的响应质量。传统RAG方法将文本数据库分割成小块，并采用扁平化结构组织以便高效搜索。为了更好地捕捉文本数据库中的固有依赖关系和结构化关系，研究者提出将文本信息组织成索引图，即基于图的RAG。然而，我们认为当前基于图的RAG方法的局限性在于检索信息的冗余，而非信息不足。此外，以往方法在提示中采用扁平化结构组织检索信息，导致性能不佳。为克服这些限制，我们提出PathRAG，它从索引图中检索关键关系路径，并将这些路径转换为文本形式用于提示LLMs。具体而言，PathRAG通过基于流的剪枝有效减少冗余信息，同时通过基于路径的提示引导LLMs生成更具逻辑性和连贯性的响应。实验结果表明，PathRAG在六个数据集和五个评估维度上持续超越现有最优基线。代码可在以下链接获取：https://github.com/BUPT-GAMMA/PathRAG

> Retrieval-augmented generation (RAG) improves the response quality of large language models (LLMs) by retrieving knowledge from external databases. Typical RAG approaches split the text database into chunks, organizing them in a flat structure for efficient searches. To better capture the inherent dependencies and structured relationships across the text database, researchers propose to organize textual information into an indexing graph, known asgraph-based RAG. However, we argue that the limitation of current graph-based RAG methods lies in the redundancy of the retrieved information, rather than its insufficiency. Moreover, previous methods use a flat structure to organize retrieved information within the prompts, leading to suboptimal performance. To overcome these limitations, we propose PathRAG, which retrieves key relational paths from the indexing graph, and converts these paths into textual form for prompting LLMs. Specifically, PathRAG effectively reduces redundant information with flow-based pruning, while guiding LLMs to generate more logical and coherent responses with path-based prompting. Experimental results show that PathRAG consistently outperforms state-of-the-art baselines across six datasets and five evaluation dimensions. The code is available at the following link: https://github.com/BUPT-GAMMA/PathRAG

[Arxiv](https://arxiv.org/abs/2502.14902)