# # 生物医学问答：基于本地知识图谱的多级摘要实现

发布时间：2025年04月01日

`RAG` `问答系统` `生物医学`

> Biomedical Question Answering via Multi-Level Summarization on a Local Knowledge Graph

# 摘要

> 问答系统（QA）领域中，检索增强生成（RAG）技术带来了革命性的性能提升，但如何有效捕捉多文档间关系，尤其是对生物医学任务而言，仍是待解难题。本研究提出了一种创新方法，通过命题声明构建本地知识图谱，再经分层总结提取摘要，实现对小型语言模型的上下文化处理，从而执行问答任务。在多个生物医学问答基准测试中，我们的方法表现优于RAG基线。针对特定指标的分步评估也证实了方法的有效性。

> In Question Answering (QA), Retrieval Augmented Generation (RAG) has revolutionized performance in various domains. However, how to effectively capture multi-document relationships, particularly critical for biomedical tasks, remains an open question. In this work, we propose a novel method that utilizes propositional claims to construct a local knowledge graph from retrieved documents. Summaries are then derived via layerwise summarization from the knowledge graph to contextualize a small language model to perform QA. We achieved comparable or superior performance with our method over RAG baselines on several biomedical QA benchmarks. We also evaluated each individual step of our methodology over a targeted set of metrics, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2504.01309)