# T-GRAG：动态图RAG框架，解决知识检索中的时空冲突与冗余问题

发布时间：2025年08月03日

`RAG` `知识图谱` `问答系统`

> T-GRAG: A Dynamic GraphRAG Framework for Resolving Temporal Conflicts and Redundancy in Knowledge Retrieval

# 摘要

> 大型语言模型（LLMs）在自然语言生成方面表现优异，但在知识密集型任务中仍显不足，原因在于其内部知识可能存在过时或不完整的情况。RAG方法通过引入外部检索机制来解决这一问题，而GraphRAG则借助结构化的知识图谱和多跳推理进一步提升了性能。然而，现有GraphRAG方法大多忽略了知识的时间动态，导致时间模糊、检索不敏感及语义冗余等问题。为克服这些限制，我们提出了时间感知的GraphRAG框架——T-GRAG，该框架能够建模知识随时间的演变。T-GRAG包含五个关键组件：（1）时间知识图生成器，用于创建带有时间戳且动态演进的图结构；（2）时间查询分解机制，将复杂的时间查询拆分为可管理的子查询；（3）三层交互式检索器，逐步过滤和精炼跨时间子图的检索结果；（4）源文本提取器，用于降低噪声干扰；（5）基于LLM的生成器，能够合成上下文和时间上均准确的响应。我们还引入了Time-LongQA，这是一个基于真实企业年报的新基准数据集，旨在测试在动态知识背景下的时间推理能力。大量实验表明，T-GRAG在时间约束下，无论是检索准确性还是响应相关性均显著优于现有的RAG和GraphRAG基线模型，凸显了建模知识演进在强健长文本问答中的必要性。我们的代码已公开发布于T-GRAG

> Large language models (LLMs) have demonstrated strong performance in natural language generation but remain limited in knowle-
  dge-intensive tasks due to outdated or incomplete internal knowledge. Retrieval-Augmented Generation (RAG) addresses this by incorporating external retrieval, with GraphRAG further enhancing performance through structured knowledge graphs and multi-hop reasoning. However, existing GraphRAG methods largely ignore the temporal dynamics of knowledge, leading to issues such as temporal ambiguity, time-insensitive retrieval, and semantic redundancy. To overcome these limitations, we propose Temporal GraphRAG (T-GRAG), a dynamic, temporally-aware RAG framework that models the evolution of knowledge over time. T-GRAG consists of five key components: (1) a Temporal Knowledge Graph Generator that creates time-stamped, evolving graph structures; (2) a Temporal Query Decomposition mechanism that breaks complex temporal queries into manageable sub-queries; (3) a Three-layer Interactive Retriever that progressively filters and refines retrieval across temporal subgraphs; (4) a Source Text Extractor to mitigate noise; and (5) a LLM-based Generator that synthesizes contextually and temporally accurate responses. We also introduce Time-LongQA, a novel benchmark dataset based on real-world corporate annual reports, designed to test temporal reasoning across evolving knowledge. Extensive experiments show that T-GRAG significantly outperforms prior RAG and GraphRAG baselines in both retrieval accuracy and response relevance under temporal constraints, highlighting the necessity of modeling knowledge evolution for robust long-text question answering. Our code is publicly available on the T-GRAG

[Arxiv](https://arxiv.org/abs/2508.01680)