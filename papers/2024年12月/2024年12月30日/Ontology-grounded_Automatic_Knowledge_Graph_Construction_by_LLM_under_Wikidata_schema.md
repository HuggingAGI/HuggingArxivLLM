# 在 Wikidata 模式下基于本体由 LLM 构建的自动知识图谱

发布时间：2024年12月30日

`LLM应用` `知识图谱` `知识库`

> Ontology-grounded Automatic Knowledge Graph Construction by LLM under Wikidata schema

# 摘要

> 我们提出一种基于本体的知识图谱（KG）构建方法，借助大型语言模型（LLMs）在知识库上进行。通过在知识库生成能力问题（CQ）以发现知识范畴，从 CQ 中提取关系，并尝试用 Wikidata 中的对应关系替换等效关系来构建本体。为保证所得 KG 的一致性和可解释性，我们依据提取的关系，以构建的本体为基础生成 KG。在基准数据集上的评估显示，在知识图谱构建任务中表现出色。我们的工作为可扩展的 KG 构建流程指明了一个颇具前景的方向，只需极少人工干预，就能生成高质量且人类可理解的 KG，这些 KG 与 Wikidata 语义可交互操作，有利于潜在的知识库拓展。

> We propose an ontology-grounded approach to Knowledge Graph (KG) construction using Large Language Models (LLMs) on a knowledge base. An ontology is authored by generating Competency Questions (CQ) on knowledge base to discover knowledge scope, extracting relations from CQs, and attempt to replace equivalent relations by their counterpart in Wikidata. To ensure consistency and interpretability in the resulting KG, we ground generation of KG with the authored ontology based on extracted relations. Evaluation on benchmark datasets demonstrates competitive performance in knowledge graph construction task. Our work presents a promising direction for scalable KG construction pipeline with minimal human intervention, that yields high quality and human-interpretable KGs, which are interoperable with Wikidata semantics for potential knowledge base expansion.

[Arxiv](https://arxiv.org/abs/2412.20942)