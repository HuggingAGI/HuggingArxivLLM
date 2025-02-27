# MEBench：面向跨文档多实体问答任务的大型语言模型评测基准

发布时间：2025年02月26日

`LLM应用` `问答系统` `信息检索`

> MEBench: Benchmarking Large Language Models for Cross-Document Multi-Entity Question Answering

# 摘要

> 多实体问答（MEQA）对大型语言模型（LLM）和检索增强生成（RAG）系统提出了重大挑战，这些系统常常难以整合来自不同文档的分散信息。现有方法在单文档理解方面表现出色，但在跨文档聚合，特别是处理实体密集型问题（如“ACM 会士在各类研究领域中的分布情况如何？”）时常常力不从心，这类问题需要整合来自异构来源（如维基百科页面）的以实体为中心的见解。为了解决这一差距，我们引入了 MEBench，这是一个全新的多文档、多实体基准测试，旨在系统评估 LLM 在检索、整合和推理零散信息方面的能力。我们的基准包含 4,780 个问题，系统地分为三大主要类别，进一步细分为八种不同类型，确保了对现实世界多实体推理场景的广泛覆盖。我们在最先进的 LLM（如 GPT-4、Llama-3）和 RAG 管道上的实验揭示了关键限制：即使是最先进的模型在 MEBench 上也只能达到 59% 的准确率。我们的基准强调了在 MEQA 任务中信息提取的完整性和事实准确性的重要性，采用实体属性 F1（EA-F1）指标对实体级别正确性和归属有效性进行粒度评估。MEBench 不仅突显了当前 LLM 框架中的系统性弱点，还为开发稳健且具备实体感知能力的问答架构奠定了基础。

> Multi-entity question answering (MEQA) represents significant challenges for large language models (LLM) and retrieval-augmented generation (RAG) systems, which frequently struggle to consolidate scattered information across diverse documents. While existing methods excel at single-document comprehension, they often struggle with cross-document aggregation, particularly when resolving entity-dense questions like "What is the distribution of ACM Fellows among various fields of study?", which require integrating entity-centric insights from heterogeneous sources (e.g., Wikipedia pages). To address this gap, we introduce MEBench, a novel multi-document, multi-entity benchmark designed to systematically evaluate LLMs' capacity to retrieve, consolidate, and reason over fragmented information. Our benchmark comprises 4,780 questions which are systematically categorized into three primary categories, further divided into eight distinct types, ensuring broad coverage of real-world multi-entity reasoning scenarios. Our experiments on state-of-the-art LLMs (e.g., GPT-4, Llama-3) and RAG pipelines reveal critical limitations: even advanced models achieve only 59% accuracy on MEBench. Our benchmark emphasizes the importance of completeness and factual precision of information extraction in MEQA tasks, using Entity-Attributed F1 (EA-F1) metric for granular evaluation of entity-level correctness and attribution validity. MEBench not only highlights systemic weaknesses in current LLM frameworks but also provides a foundation for advancing robust, entity-aware QA architectures.

[Arxiv](https://arxiv.org/abs/2502.18993)