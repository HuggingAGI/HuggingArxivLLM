# GRAF：用于法律问题回答、由事实增强的图检索

发布时间：2024年12月05日

`LLM应用` `NLP`

> GRAF: Graph Retrieval Augmented by Facts for Legal Question Answering

# 摘要

> 预训练语言模型（PLMs）近些年来表现出众，为自然语言处理（NLP）的研究和行业开创了新范式。法律领域因其文本特性，受到了自然语言处理（NLP）社区的一定关注。该领域的部分任务以问答（QA）任务的形式存在。此项工作对低资源语言的法律领域多项选择题问答（MCQA）进行了探索。此工作的贡献是多方面的。我们首先推出了 JuRO，这是首个公开可用的罗马尼亚法律 MCQA 数据集，涵盖三个不同的考试，总计 10836 个问题。伴随这个数据集，我们引入了 CROL，这是一个有组织的法律语料库，共有 93 个不同文档以及来自 763 个时间段的修改，我们在工作中借助它用于信息检索（IR）技术。此外，我们率先提出了 Law-RoG，这是罗马尼亚语的知识图谱（KG），且此 KG 源自上述语料库。最后，我们提出了一种用于 MCQA 的新方法——事实增强的图检索（GRAF），其取得了与普遍认可的 SOTA 方法相媲美的结果，甚至在多数情况下超越了它们。

> Pre-trained Language Models (PLMs) have shown remarkable performances in recent years, setting a new paradigm for NLP research and industry. The legal domain has received some attention from the NLP community partly due to its textual nature. Some tasks from this domain are represented by question-answering (QA) tasks. This work explores the legal domain Multiple-Choice QA (MCQA) for a low-resource language. The contribution of this work is multi-fold. We first introduce JuRO, the first openly available Romanian legal MCQA dataset, comprising three different examinations and a number of 10,836 total questions. Along with this dataset, we introduce CROL, an organized corpus of laws that has a total of 93 distinct documents with their modifications from 763 time spans, that we leveraged in this work for Information Retrieval (IR) techniques. Moreover, we are the first to propose Law-RoG, a Knowledge Graph (KG) for the Romanian language, and this KG is derived from the aforementioned corpus. Lastly, we propose a novel approach for MCQA, Graph Retrieval Augmented by Facts (GRAF), which achieves competitive results with generally accepted SOTA methods and even exceeds them in most settings.

[Arxiv](https://arxiv.org/abs/2412.04119)