# GENIUS：一个多模态通用搜索的生成式框架。

发布时间：2025年03月25日

`其他

摘要中提到的生成式检索和GENIUS框架主要专注于信息检索方法的改进，属于检索技术领域，而非直接涉及大型语言模型的应用或理论。因此，将其归类为“其他”更为合适。` `信息检索` `互联网`

> GENIUS: A Generative Framework for Universal Multimodal Search

# 摘要

> 生成式检索是一种新兴的信息检索方法，它基于查询生成目标数据的标识符（ID），为传统基于嵌入的检索方法提供了一种高效替代方案。然而，现有的模型具有特定任务性，性能上尚未达到基于嵌入的检索方法的水平。本文提出了一种通用的生成式检索框架 GENIUS，支持跨多种模态和领域的多样化任务。其核心是引入模态解耦语义量化，将多模态数据转换为离散的 ID，编码模态和语义信息。此外，我们提出了一种查询增强方法，通过在查询和目标之间进行插值，使 GENIUS 能够适应不同查询形式。在 M-BEIR 基准测试中，GENIUS 明显超越了之前的生成式方法。与基于嵌入的检索不同，GENIUS 在不同规模的数据库中始终保持高速检索，同时在多个基准测试中表现出色。通过额外的重排序，GENIUS 通常能够实现与基于嵌入的方法相当的结果，同时保持高效性。

> Generative retrieval is an emerging approach in information retrieval that generates identifiers (IDs) of target data based on a query, providing an efficient alternative to traditional embedding-based retrieval methods. However, existing models are task-specific and fall short of embedding-based retrieval in performance. This paper proposes GENIUS, a universal generative retrieval framework supporting diverse tasks across multiple modalities and domains. At its core, GENIUS introduces modality-decoupled semantic quantization, transforming multimodal data into discrete IDs encoding both modality and semantics. Moreover, to enhance generalization, we propose a query augmentation that interpolates between a query and its target, allowing GENIUS to adapt to varied query forms. Evaluated on the M-BEIR benchmark, it surpasses prior generative methods by a clear margin. Unlike embedding-based retrieval, GENIUS consistently maintains high retrieval speed across database size, with competitive performance across multiple benchmarks. With additional re-ranking, GENIUS often achieves results close to those of embedding-based methods while preserving efficiency.

[Arxiv](https://arxiv.org/abs/2503.19868)