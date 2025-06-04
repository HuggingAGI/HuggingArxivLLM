# ImpRAG: 基于隐式查询的检索增强生成方法

发布时间：2025年06月02日

`RAG` `问答系统` `信息检索`

> ImpRAG: Retrieval-Augmented Generation with Implicit Queries

# 摘要

> 传统 RAG 系统将检索与生成割裂为独立模块，需借助显式文本查询连接二者，这种设计限制了模型的跨任务泛化能力。我们提出了一种创新的无查询 RAG 系统——隐式 RAG（ImpRAG），将检索与生成无缝整合为统一模型。ImpRAG 赋予模型隐式表达信息需求的能力，摆脱了人为指定查询的束缚。通过将预训练的解码器-only 语言模型划分为专门层组，ImpRAG 实现了检索与生成任务的同步优化。我们的两阶段推理框架采用同一模型参数与前向传递流程，有效弥合了检索器与语言模型之间的鸿沟。在 8 个知识密集型任务上的实验表明，ImpRAG 在不同格式的未见任务中，精确匹配得分提升了 3.6 至 11.5 个百分点，充分展现了其在模型自主表达信息需求与跨任务泛化方面的卓越效能。研究分析表明，平衡检索与生成参数并利用生成困惑度作为检索训练目标，是实现性能提升的关键策略。

> Retrieval-Augmented Generation (RAG) systems traditionally treat retrieval and generation as separate processes, requiring explicit textual queries to connect them. This separation can limit the ability of models to generalize across diverse tasks. In this work, we propose a query-free RAG system, named ImpRAG, which integrates retrieval and generation into a unified model. ImpRAG allows models to implicitly express their information needs, eliminating the need for human-specified queries. By dividing pretrained decoder-only language models into specialized layer groups, ImpRAG optimizes retrieval and generation tasks simultaneously. Our approach employs a two-stage inference process, using the same model parameters and forward pass for both retrieval and generation, thereby minimizing the disparity between retrievers and language models. Experiments on 8 knowledge-intensive tasks demonstrate that ImpRAG achieves 3.6-11.5 improvements in exact match scores on unseen tasks with diverse formats, highlighting its effectiveness in enabling models to articulate their own information needs and generalize across tasks. Our analysis underscores the importance of balancing retrieval and generation parameters and leveraging generation perplexities as retrieval training objectives for enhanced performance.

[Arxiv](https://arxiv.org/abs/2506.02279)