# # 研究基于历史文本知识图谱的图检索增强生成

发布时间：2025年06月18日

`RAG` `计算人文` `历史文本分析`

> Research on Graph-Retrieval Augmented Generation Based on Historical Text Knowledge Graphs

# 摘要

> 本文针对计算人文和AIGC技术背景下通用大语言模型在历史文本分析领域的知识鸿沟，提出了Graph RAG框架。该框架结合了链式思维提示、自我指令生成和过程监督，构建了《史记》等前四史人物关系数据集，且仅需少量人工标注。该数据集支持自动化的知识抽取，降低了人工成本。在知识图谱增强生成阶段，我们引入了知识图谱与检索增强生成之间的协作机制，提升了通用模型与历史知识的对齐度。实验表明，在关系抽取任务上，专有领域模型荀子-大鹏1.5-14B（输入为简体中文，采用链式思维提示）取得了最优效果（F1=0.68）。DeepSeek模型在与GraphRAG框架结合后，于开放领域C-CLUE关系抽取数据集上，F1值提升了11%（0.08-0.19），超越了荀子-大鹏1.5-14B的F1值（0.12），有效缓解了幻觉现象，提升了可解释性。该框架为古典文本知识抽取提供了低资源解决方案，推动了历史知识服务与人文研究的发展。

> This article addresses domain knowledge gaps in general large language models for historical text analysis in the context of computational humanities and AIGC technology. We propose the Graph RAG framework, combining chain-of-thought prompting, self-instruction generation, and process supervision to create a The First Four Histories character relationship dataset with minimal manual annotation. This dataset supports automated historical knowledge extraction, reducing labor costs. In the graph-augmented generation phase, we introduce a collaborative mechanism between knowledge graphs and retrieval-augmented generation, improving the alignment of general models with historical knowledge. Experiments show that the domain-specific model Xunzi-Qwen1.5-14B, with Simplified Chinese input and chain-of-thought prompting, achieves optimal performance in relation extraction (F1 = 0.68). The DeepSeek model integrated with GraphRAG improves F1 by 11% (0.08-0.19) on the open-domain C-CLUE relation extraction dataset, surpassing the F1 value of Xunzi-Qwen1.5-14B (0.12), effectively alleviating hallucinations phenomenon, and improving interpretability. This framework offers a low-resource solution for classical text knowledge extraction, advancing historical knowledge services and humanities research.

[Arxiv](https://arxiv.org/abs/2506.15241)