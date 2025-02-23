# RAG 与 GraphRAG：系统评估与关键洞察

发布时间：2025年02月16日

`RAG` `问答系统` `知识图谱`

> RAG vs. GraphRAG: A Systematic Evaluation and Key Insights

# 摘要

> 检索增强生成（RAG）通过从外部来源检索相关信息，显著提升了大型语言模型（LLMs）在各类任务中的表现，尤其在文本数据领域。对于结构化数据，如知识图谱，GraphRAG已被广泛用于高效检索相关信息。然而，最新研究表明，将文本中的隐性知识转化为图结构，能够为特定任务带来显著优势，从而将GraphRAG的应用范围从图数据扩展至通用文本数据。尽管这些方法已成功扩展，但目前针对文本数据的GraphRAG应用大多局限于特定任务和数据集，缺乏在广泛使用的文本基准上对RAG与GraphRAG进行系统性评估和比较。本研究系统评估了RAG与GraphRAG在问答和基于查询的摘要等成熟基准任务中的表现，揭示了两者在不同任务与评估维度下的独特优势。基于这些发现，我们深入探讨了融合两者优势以提升下游任务性能的策略。此外，本文还深入剖析了现有GraphRAG方法的局限性，并为未来研究指明了方向。

> Retrieval-Augmented Generation (RAG) enhances the performance of LLMs across various tasks by retrieving relevant information from external sources, particularly on text-based data. For structured data, such as knowledge graphs, GraphRAG has been widely used to retrieve relevant information. However, recent studies have revealed that structuring implicit knowledge from text into graphs can benefit certain tasks, extending the application of GraphRAG from graph data to general text-based data. Despite their successful extensions, most applications of GraphRAG for text data have been designed for specific tasks and datasets, lacking a systematic evaluation and comparison between RAG and GraphRAG on widely used text-based benchmarks. In this paper, we systematically evaluate RAG and GraphRAG on well-established benchmark tasks, such as Question Answering and Query-based Summarization. Our results highlight the distinct strengths of RAG and GraphRAG across different tasks and evaluation perspectives. Inspired by these observations, we investigate strategies to integrate their strengths to improve downstream tasks. Additionally, we provide an in-depth discussion of the shortcomings of current GraphRAG approaches and outline directions for future research.

[Arxiv](https://arxiv.org/abs/2502.11371)