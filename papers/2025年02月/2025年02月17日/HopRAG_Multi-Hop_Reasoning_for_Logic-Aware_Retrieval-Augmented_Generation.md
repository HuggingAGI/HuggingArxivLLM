# HopRAG：通过多跳推理实现逻辑感知的检索增强生成

发布时间：2025年02月17日

`RAG` `信息检索` `图结构`

> HopRAG: Multi-Hop Reasoning for Logic-Aware Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统常常面临检索不完美的问题，因为传统检索器侧重于词汇或语义相似性，而非逻辑相关性。为解决这一问题，我们提出了HopRAG，一个通过图结构知识探索增强检索的新型RAG框架。在索引阶段，HopRAG构建一个段落图，其中文本片段作为节点，通过LLM生成的伪查询建立逻辑连接作为边。在检索阶段，它采用检索-推理-剪枝机制：从词汇或语义相似的段落开始，系统通过伪查询和LLM推理引导多跳邻居探索，以识别真正相关的段落。大量实验表明，HopRAG表现出色，相比传统方法，答案准确率提高了76.78%，检索F1分数提升了65.07%。该仓库可在https://github.com/LIU-Hao-2002/HopRAG获取。

> Retrieval-Augmented Generation (RAG) systems often struggle with imperfect retrieval, as traditional retrievers focus on lexical or semantic similarity rather than logical relevance. To address this, we propose HopRAG, a novel RAG framework that augments retrieval with logical reasoning through graph-structured knowledge exploration. During indexing, HopRAG constructs a passage graph, with text chunks as vertices and logical connections established via LLM-generated pseudo-queries as edges. During retrieval, it employs a retrieve-reason-prune mechanism: starting with lexically or semantically similar passages, the system explores multi-hop neighbors guided by pseudo-queries and LLM reasoning to identify truly relevant ones. Extensive experiments demonstrate HopRAG's superiority, achieving 76.78\% higher answer accuracy and 65.07\% improved retrieval F1 score compared to conventional methods. The repository is available at https://github.com/LIU-Hao-2002/HopRAG.

[Arxiv](https://arxiv.org/abs/2502.12442)