# 高效微调大型语言模型用于知识导向对话生成

发布时间：2025年04月10日

`LLM应用

理由：这篇论文提出了一种名为KEDiT的知识导向对话生成微调方法，专注于如何将外部知识整合到大型语言模型中以提升对话生成的效果。虽然它涉及到模型的微调和优化，但其核心是应用层面的研究，旨在解决模型在特定任务中的性能问题。因此，它属于LLM应用类别。` `知识图谱`

> Efficient Tuning of Large Language Models for Knowledge-Grounded Dialogue Generation

# 摘要

> 大型语言模型（LLMs）在文本理解和生成方面表现出色，但难以利用训练数据之外的最新或领域知识。为此，我们提出了KEDiT，一种高效的知识导向对话生成微调方法。KEDiT分为两大阶段：首先，通过信息瓶颈压缩知识，保留关键信息且计算开销小；其次，轻量级适配器将压缩知识融入模型，仅更新不到2%的参数。在Wizard of Wikipedia和新构建的PubMed-Dialog数据集上，KEDiT生成的回复在相关性与信息量上均优于现有方法，且在自动、模型和人工评估中表现优异。该方法将预训练模型的优势与知识动态适应性相结合，为医学等领域提供了可扩展的解决方案。

> Large language models (LLMs) demonstrate remarkable text comprehension and generation capabilities but often lack the ability to utilize up-to-date or domain-specific knowledge not included in their training data. To address this gap, we introduce KEDiT, an efficient method for fine-tuning LLMs for knowledge-grounded dialogue generation. KEDiT operates in two main phases: first, it employs an information bottleneck to compress retrieved knowledge into learnable parameters, retaining essential information while minimizing computational overhead. Second, a lightweight knowledge-aware adapter integrates these compressed knowledge vectors into the LLM during fine-tuning, updating less than 2\% of the model parameters. The experimental results on the Wizard of Wikipedia and a newly constructed PubMed-Dialog dataset demonstrate that KEDiT excels in generating contextually relevant and informative responses, outperforming competitive baselines in automatic, LLM-based, and human evaluations. This approach effectively combines the strengths of pretrained LLMs with the adaptability needed for incorporating dynamic knowledge, presenting a scalable solution for fields such as medicine.

[Arxiv](https://arxiv.org/abs/2504.07754)