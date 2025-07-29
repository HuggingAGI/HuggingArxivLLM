# RAG 在实际应用中的有效性与局限性研究：探讨基于混合知识检索增强的 LLMs

发布时间：2025年07月26日

`RAG` `信息检索`

> RAG in the Wild: On the (In)effectiveness of LLMs with Mixture-of-Knowledge Retrieval Augmentation

# 摘要

> 检索增强生成（RAG）通过在推理时融合外部知识来提升大型语言模型（LLMs）的能力。尽管RAG在以维基百科等通用领域语料库为基础的基准测试中表现出色，但其在现实多样化检索场景下的有效性仍待深入探索。我们使用大规模混合知识数据集MassiveDS评估了RAG系统，发现其存在几个关键局限性：检索主要对小型模型有益，重排序器贡献有限，且没有单一检索源能持续领先。此外，当前LLMs难以有效跨异质知识源路由查询。这些发现凸显了在实际部署RAG前开发自适应检索策略的必要性。我们的代码和数据可在https://github.com/ritaranx/RAG_in_the_Wild获取。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by integrating external knowledge retrieved at inference time. While RAG demonstrates strong performance on benchmarks largely derived from general-domain corpora like Wikipedia, its effectiveness under realistic, diverse retrieval scenarios remains underexplored. We evaluated RAG systems using MassiveDS, a large-scale datastore with mixture of knowledge, and identified critical limitations: retrieval mainly benefits smaller models, rerankers add minimal value, and no single retrieval source consistently excels. Moreover, current LLMs struggle to route queries across heterogeneous knowledge sources. These findings highlight the need for adaptive retrieval strategies before deploying RAG in real-world settings. Our code and data can be found at https://github.com/ritaranx/RAG_in_the_Wild.

[Arxiv](https://arxiv.org/abs/2507.20059)