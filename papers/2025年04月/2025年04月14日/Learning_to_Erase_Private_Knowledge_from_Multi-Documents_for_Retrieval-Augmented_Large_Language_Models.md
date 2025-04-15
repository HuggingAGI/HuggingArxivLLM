# 为检索增强的大型语言模型学习擦除多文档中的私人知识

发布时间：2025年04月14日

`RAG` `隐私保护` `知识图谱`

> Learning to Erase Private Knowledge from Multi-Documents for Retrieval-Augmented Large Language Models

# 摘要

> # 摘要
检索增强生成（RAG）是将大型语言模型应用于专有领域的一种有前景的技术。然而，检索到的文档可能包含敏感知识，这在生成结果中存在隐私泄露的风险。因此，如何有效擦除检索文档中的隐私信息，是RAG面临的关键挑战。

与传统的文本匿名化不同，RAG需要考虑以下几点：(1) 内在的多文档推理可能面临去匿名化攻击；(2) 隐私知识因场景而异，因此应允许用户自定义需要擦除的信息；(3) 保留足够的公开可用知识以支持生成任务。

本文介绍了RAG的隐私擦除任务，并提出了Eraser4RAG，这是一种隐私知识擦除器，能够有效去除用户定义的隐私知识，同时保留足够的公开知识用于生成。具体来说，我们首先构建一个全局知识图谱，以识别文档中的潜在知识，旨在防御去匿名化攻击。然后将其随机拆分为隐私子图和公开子图，并微调Flan-T5以重写检索到的文档，排除隐私三元组。最后，使用PPO算法优化重写模型，以最小化隐私三元组并最大化公开三元组的保留。

在四个问答数据集上的实验表明，Eraser4RAG的擦除性能优于GPT-4o。

> Retrieval-Augmented Generation (RAG) is a promising technique for applying LLMs to proprietary domains. However, retrieved documents may contain sensitive knowledge, posing risks of privacy leakage in generative results. Thus, effectively erasing private information from retrieved documents is a key challenge for RAG. Unlike traditional text anonymization, RAG should consider: (1) the inherent multi-document reasoning may face de-anonymization attacks; (2) private knowledge varies by scenarios, so users should be allowed to customize which information to erase; (3) preserving sufficient publicly available knowledge for generation tasks. This paper introduces the privacy erasure task for RAG and proposes Eraser4RAG, a private knowledge eraser which effectively removes user-defined private knowledge from documents while preserving sufficient public knowledge for generation. Specifically, we first construct a global knowledge graph to identify potential knowledge across documents, aiming to defend against de-anonymization attacks. Then we randomly split it into private and public sub-graphs, and fine-tune Flan-T5 to rewrite the retrieved documents excluding private triples. Finally, PPO algorithm optimizes the rewriting model to minimize private triples and maximize public triples retention. Experiments on four QA datasets demonstrate that Eraser4RAG achieves superior erase performance than GPT-4o.

[Arxiv](https://arxiv.org/abs/2504.09910)