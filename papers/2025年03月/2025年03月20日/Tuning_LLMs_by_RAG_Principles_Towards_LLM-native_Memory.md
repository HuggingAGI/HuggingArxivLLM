# # 基于 RAG 原理微调 LLM，迈向 LLM 本原记忆

发布时间：2025年03月20日

`LLM应用` `个人助理`

> Tuning LLMs by RAG Principles: Towards LLM-native Memory

# 摘要

> 内存作为大语言模型（LLMs）训练之外的重要补充信息，在诸多实际应用中发挥着关键作用，例如个人助理。目前，将内存整合到生成过程中的两大主流解决方案分别是长上下文 LLM 和检索增强生成（RAG）。本文首先在三个更新/全新数据集上系统性地对比了这两种解决方案，发现：(1) 长上下文解决方案尽管成本更高，但更易于把握全局，能够更好地回答需要整体考虑内存的问题；(2) 当查询涉及具体信息时，RAG 方案更具竞争力，尤其是在关键词能够显式匹配的情况下。因此，我们提出了一种新型方法 RAG-Tuned-LLM，该方法基于 RAG 原则生成数据，对一个相对较小的（例如 7B）LLM 进行微调，使其能够结合两种解决方案的优势。在三个数据集上的广泛实验表明，RAG-Tuned-LLM 在各种查询类型中均能超越长上下文 LLM 和 RAG 方法。

> Memory, additional information beyond the training of large language models (LLMs), is crucial to various real-world applications, such as personal assistant. The two mainstream solutions to incorporate memory into the generation process are long-context LLMs and retrieval-augmented generation (RAG). In this paper, we first systematically compare these two types of solutions on three renovated/new datasets and show that (1) long-context solutions, although more expensive, shall be easier to capture the big picture and better answer queries which require considering the memory as a whole; and (2) when the queries concern specific information, RAG solutions shall be more competitive especially when the keywords can be explicitly matched. Therefore, we propose a novel method RAG-Tuned-LLM which fine-tunes a relative small (e.g., 7B) LLM using the data generated following the RAG principles, so it can combine the advantages of both solutions. Extensive experiments on three datasets demonstrate that RAG-Tuned-LLM can beat long-context LLMs and RAG methods across a wide range of query types.

[Arxiv](https://arxiv.org/abs/2503.16071)