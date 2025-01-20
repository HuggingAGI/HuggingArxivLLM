# FRAG: 基于知识图谱的灵活模块化检索增强生成框架
发布时间：2025年01月17日

`RAG`
> FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs
>
> 为了缓解大型语言模型（LLMs）中的幻觉和知识不足问题，基于知识图谱（KG）的检索增强生成（RAG）通过利用KG作为外部资源来增强LLMs的推理能力，展现出巨大潜力。然而，现有KG-RAG方法在灵活性和检索质量之间难以平衡。模块化方法通过避免在检索中使用KG微调模型来优先考虑灵活性，但导致检索策略固定且质量欠佳。相反，耦合方法将KG信息嵌入模型以提高检索质量，却牺牲了灵活性。本文提出了一种新颖的灵活模块化KG-RAG框架，称为FRAG，它结合了两种方法的优势。FRAG仅基于查询估计推理路径的跳数范围，并将其分类为简单或复杂。针对查询的复杂性，应用定制管道以确保高效准确的推理路径检索，从而促进最终推理过程。通过使用查询文本而非KG推断推理路径的结构信息，并采用适应性强的检索策略，FRAG在保持灵活性的同时提升了检索质量。此外，FRAG无需额外LLMs微调或调用，显著提高了效率并节省了资源。大量实验表明，FRAG以高效率和低资源消耗实现了最先进的性能。
>
> https://arxiv.org/abs/2501.09957

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2501.09957](https://arxiv.org/abs/2501.09957)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)