# 基于检索增强生成的大型语言模型在因果关系挖掘中的应用

发布时间：2025年05月29日

`RAG` `信息检索` `因果关系检测`

> Retrieval Augmented Generation based Large Language Models for Causality Mining

# 摘要

> 因果关系检测与挖掘在信息检索领域具有重要意义，广泛应用于信息抽取和知识图谱构建。现有文献中提出了多种解决方案，涵盖无监督和监督方法。然而，无监督方法不仅表现欠佳，还需大量人工干预选择因果规则，导致跨领域泛化能力有限。监督方法则受限于缺乏大规模训练数据集。近期研究发现，结合有效提示工程的大型语言模型（LLMs）能有效缓解这一难题。然而，现有文献中尚未有系统性工作探讨基于LLM提示的因果关系检测与挖掘。本文提出基于检索增强生成（RAG）的动态提示方案，以提升LLM在因果关系检测与抽取任务中的性能。通过在三个数据集和五个LLMs上的实验，验证了基于RAG的动态提示方案相较于静态提示方案的显著优势。

> Causality detection and mining are important tasks in information retrieval due to their enormous use in information extraction, and knowledge graph construction. To solve these tasks, in existing literature there exist several solutions -- both unsupervised and supervised. However, the unsupervised methods suffer from poor performance and they often require significant human intervention for causal rule selection, leading to poor generalization across different domains. On the other hand, supervised methods suffer from the lack of large training datasets. Recently, large language models (LLMs) with effective prompt engineering are found to be effective to overcome the issue of unavailability of large training dataset. Yet, in existing literature, there does not exist comprehensive works on causality detection and mining using LLM prompting. In this paper, we present several retrieval-augmented generation (RAG) based dynamic prompting schemes to enhance LLM performance in causality detection and extraction tasks. Extensive experiments over three datasets and five LLMs validate the superiority of our proposed RAG-based dynamic prompting over other static prompting schemes.

[Arxiv](https://arxiv.org/abs/2505.23944)