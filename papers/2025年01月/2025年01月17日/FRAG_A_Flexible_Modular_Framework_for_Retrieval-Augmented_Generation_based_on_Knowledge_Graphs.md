# FRAG: 基于知识图谱的灵活模块化检索增强生成框架

发布时间：2025年01月17日

`RAG

理由：这篇论文主要讨论了如何通过结合知识图谱（KG）和检索增强生成（RAG）来增强大型语言模型（LLMs）的推理能力，并提出了一个新颖的框架FRAG。该框架旨在解决现有KG-RAG方法在灵活性和检索质量之间的平衡问题。因此，这篇论文的核心内容属于RAG（Retrieval-Augmented Generation）领域。` `知识图谱`

> FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs

# 摘要

> 为了缓解大型语言模型（LLMs）中的幻觉和知识不足问题，基于知识图谱（KG）的检索增强生成（RAG）通过利用KG作为外部资源来增强LLMs的推理能力，展现出巨大潜力。然而，现有KG-RAG方法在灵活性和检索质量之间难以平衡。模块化方法通过避免在检索中使用KG微调模型来优先考虑灵活性，但导致检索策略固定且质量欠佳。相反，耦合方法将KG信息嵌入模型以提高检索质量，却牺牲了灵活性。本文提出了一种新颖的灵活模块化KG-RAG框架，称为FRAG，它结合了两种方法的优势。FRAG仅基于查询估计推理路径的跳数范围，并将其分类为简单或复杂。针对查询的复杂性，应用定制管道以确保高效准确的推理路径检索，从而促进最终推理过程。通过使用查询文本而非KG推断推理路径的结构信息，并采用适应性强的检索策略，FRAG在保持灵活性的同时提升了检索质量。此外，FRAG无需额外LLMs微调或调用，显著提高了效率并节省了资源。大量实验表明，FRAG以高效率和低资源消耗实现了最先进的性能。

> To mitigate the hallucination and knowledge deficiency in large language models (LLMs), Knowledge Graph (KG)-based Retrieval-Augmented Generation (RAG) has shown promising potential by utilizing KGs as external resource to enhance LLMs reasoning.However, existing KG-RAG approaches struggle with a trade-off between flexibility and retrieval quality.Modular methods prioritize flexibility by avoiding the use of KG-fine-tuned models during retrieval, leading to fixed retrieval strategies and suboptimal retrieval quality.Conversely, coupled methods embed KG information within models to improve retrieval quality, but at the expense of flexibility.In this paper, we propose a novel flexible modular KG-RAG framework, termed FRAG, which synergizes the advantages of both approaches.FRAG estimates the hop range of reasoning paths based solely on the query and classify it as either simple or complex.To match the complexity of the query, tailored pipelines are applied to ensure efficient and accurate reasoning path retrieval, thus fostering the final reasoning process.By using the query text instead of the KG to infer the structural information of reasoning paths and employing adaptable retrieval strategies, FRAG improves retrieval quality while maintaining flexibility.Moreover, FRAG does not require extra LLMs fine-tuning or calls, significantly boosting efficiency and conserving resources.Extensive experiments show that FRAG achieves state-of-the-art performance with high efficiency and low resource consumption.

[Arxiv](https://arxiv.org/abs/2501.09957)