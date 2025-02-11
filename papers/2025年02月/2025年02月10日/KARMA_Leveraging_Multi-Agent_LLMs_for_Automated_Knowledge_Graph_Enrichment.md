# KARMA：借助多智能体大型语言模型实现知识图谱自动化丰富

发布时间：2025年02月10日

`LLM应用

摘要中提到的KARMA框架利用多智能体大型语言模型（LLMs）来处理非结构化文本，实现知识图谱的自动化扩展。这表明论文主要关注于将LLMs应用于实际问题，如知识抽取和图谱构建，属于LLM的应用领域。因此，分类为LLM应用。` `知识图谱`

> KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment

# 摘要

> # 摘要
知识图谱 (KGs) 对现代 AI 系统的运行至关重要，但面对科学文献的爆炸式增长，传统的手动整理方式已力不从心。本文提出了一种名为 KARMA 的创新框架，通过多智能体大型语言模型 (LLMs) 对非结构化文本进行深度分析，从而实现知识图谱的自动化扩展。我们的方法采用了九个协作智能体，涵盖实体发现、关系抽取、模式对齐和冲突解决等多个关键环节。这些智能体通过迭代解析文档、验证提取的知识，并将其无缝整合到现有图结构中，同时严格遵循特定领域的模式规范。在来自三个不同领域的 1,200 篇 PubMed 文献上的实验结果令人振奋：KARMA 成功识别出多达 38,230 个新实体，通过多层评估实现了 83.1% 的 LLM 验证正确率，并将冲突边减少了 18.6%。这充分证明了 KARMA 在知识图谱丰富方面的强大效能。

> Maintaining comprehensive and up-to-date knowledge graphs (KGs) is critical for modern AI systems, but manual curation struggles to scale with the rapid growth of scientific literature. This paper presents KARMA, a novel framework employing multi-agent large language models (LLMs) to automate KG enrichment through structured analysis of unstructured text. Our approach employs nine collaborative agents, spanning entity discovery, relation extraction, schema alignment, and conflict resolution that iteratively parse documents, verify extracted knowledge, and integrate it into existing graph structures while adhering to domain-specific schema. Experiments on 1,200 PubMed articles from three different domains demonstrate the effectiveness of KARMA in knowledge graph enrichment, with the identification of up to 38,230 new entities while achieving 83.1\% LLM-verified correctness and reducing conflict edges by 18.6\% through multi-layer assessments.

[Arxiv](https://arxiv.org/abs/2502.06472)