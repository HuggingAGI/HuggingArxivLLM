# MAGIC：一个多跳图基准，面向检索增强生成中的跨上下文冲突

发布时间：2025年07月29日

`RAG` `知识图谱` `信息检索`

> MAGIC: A Multi-Hop and Graph-Based Benchmark for Inter-Context Conflicts in Retrieval-Augmented Generation

# 摘要

> 知识冲突在检索增强生成（RAG）系统中普遍存在，检索到的文档可能与彼此或模型的内置知识存在不一致甚至矛盾。现有研究这一现象的基准测试存在诸多局限：仅聚焦于问答场景、过度依赖实体替换技术，且冲突类型较为单一。为突破这些限制，我们提出了一种基于知识图谱（KG）的框架，能够在两个相似但不同的上下文间制造多样且微妙的冲突，同时通过KG的显式关系结构确保结果的可解释性。在我们的基准测试MAGIC中，实验结果揭示了大型语言模型（LLMs）在处理知识冲突方面的内在机制：无论是开源模型还是专有模型，都难以有效检测冲突，尤其在需要多跳推理时，常常难以准确识别矛盾的根源。最后，我们进行了深入分析，为改进LLMs整合多样甚至相互矛盾信息的能力提供了重要参考。


> Knowledge conflict often arises in retrieval-augmented generation (RAG) systems, where retrieved documents may be inconsistent with one another or contradict the model's parametric knowledge. Existing benchmarks for investigating the phenomenon have notable limitations, including a narrow focus on the question answering setup, heavy reliance on entity substitution techniques, and a restricted range of conflict types. To address these issues, we propose a knowledge graph (KG)-based framework that generates varied and subtle conflicts between two similar yet distinct contexts, while ensuring interpretability through the explicit relational structure of KGs. Experimental results on our benchmark, MAGIC, provide intriguing insights into the inner workings of LLMs regarding knowledge conflict: both open-source and proprietary models struggle with conflict detection -- especially when multi-hop reasoning is required -- and often fail to pinpoint the exact source of contradictions. Finally, we present in-depth analyses that serve as a foundation for improving LLMs in integrating diverse, sometimes even conflicting, information.

[Arxiv](https://arxiv.org/abs/2507.21544)