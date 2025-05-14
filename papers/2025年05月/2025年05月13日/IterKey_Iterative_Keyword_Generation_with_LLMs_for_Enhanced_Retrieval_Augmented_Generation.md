# IterKey：基于 LLMs 的迭代关键词生成，助力提升检索增强生成效果。

发布时间：2025年05月13日

`RAG` `问答系统` `信息检索`

> IterKey: Iterative Keyword Generation with LLMs for Enhanced Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部文档，为大型语言模型（LLMs）的上下文知识提供了有力补充。然而，现实世界的应用不仅追求准确性，还要求可解释性。密集检索方法虽能提供高准确性，却难以解释；稀疏检索方法虽透明，但受限于关键词匹配，常无法完全捕捉查询意图。为解决这一矛盾，我们提出了IterKey——一个基于LLM的迭代关键词生成框架，通过稀疏检索优化RAG。IterKey包含三个核心阶段：基于LLM生成检索关键词、根据检索文档生成答案、以及对答案进行验证。若验证未通过，系统将迭代优化关键词并重新执行流程。实验结果显示，在四个问答任务中，IterKey较基于BM25的RAG和简单基线方法，准确率提升了5%至20%。其性能可与基于密集检索的RAG以及先前的迭代查询优化方法相媲美。总结而言，IterKey是一种创新的基于BM25的方法，借助LLMs实现RAG的迭代优化，成功在准确性和可解释性之间找到了完美平衡。

> Retrieval-Augmented Generation (RAG) has emerged as a way to complement the in-context knowledge of Large Language Models (LLMs) by integrating external documents. However, real-world applications demand not only accuracy but also interpretability. While dense retrieval methods provide high accuracy, they lack interpretability; conversely, sparse retrieval methods offer transparency but often fail to capture the full intent of queries due to their reliance on keyword matching. To address these issues, we introduce IterKey, an LLM-driven iterative keyword generation framework that enhances RAG via sparse retrieval. IterKey consists of three LLM-driven stages: generating keywords for retrieval, generating answers based on retrieved documents, and validating the answers. If validation fails, the process iteratively repeats with refined keywords. Across four QA tasks, experimental results show that IterKey achieves 5% to 20% accuracy improvements over BM25-based RAG and simple baselines. Its performance is comparable to dense retrieval-based RAG and prior iterative query refinement methods using dense models. In summary, IterKey is a novel BM25-based approach leveraging LLMs to iteratively refine RAG, effectively balancing accuracy with interpretability.

[Arxiv](https://arxiv.org/abs/2505.08450)