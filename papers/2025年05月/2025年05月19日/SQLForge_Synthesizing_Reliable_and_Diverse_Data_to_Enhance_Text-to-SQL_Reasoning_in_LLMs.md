# SQLForge：利用合成可靠且多样化数据提升LLMs的文本到SQL推理能力

发布时间：2025年05月19日

`LLM应用` `数据库`

> SQLForge: Synthesizing Reliable and Diverse Data to Enhance Text-to-SQL Reasoning in LLMs

# 摘要

> 大型语言模型（LLMs）在文本到SQL推理任务中展现了巨大的潜力，但现有开源模型与闭源模型之间仍存在显著的性能差距。本文中，我们介绍了SQLForge，这是一种通过生成可靠且多样化数据来提升LLMs文本到SQL推理能力的新方法。我们通过SQL语法约束和SQL到问题的逆向翻译来提高数据可靠性，确保数据在结构和语义层面的逻辑性。此外，我们提出了一种SQL模板丰富化和迭代式数据领域探索机制，以提升数据多样性。基于增强的数据，我们对不同架构和参数规模的开源模型进行了微调，最终形成了SQLForge-LM系列模型。SQLForge-LM在广泛认可的Spider和BIRD基准测试中，开源模型中达到了最先进水平。具体来说，SQLForge-LM在Spider Dev上达到了85.7%的准确率，在BIRD Dev上达到了59.8%的准确率，显著缩小了与闭源方法的性能差距。

> Large Language models (LLMs) have demonstrated significant potential in text-to-SQL reasoning tasks, yet a substantial performance gap persists between existing open-source models and their closed-source counterparts. In this paper, we introduce SQLForge, a novel approach for synthesizing reliable and diverse data to enhance text-to-SQL reasoning in LLMs. We improve data reliability through SQL syntax constraints and SQL-to-question reverse translation, ensuring data logic at both structural and semantic levels. We also propose an SQL template enrichment and iterative data domain exploration mechanism to boost data diversity. Building on the augmented data, we fine-tune a variety of open-source models with different architectures and parameter sizes, resulting in a family of models termed SQLForge-LM. SQLForge-LM achieves the state-of-the-art performance on the widely recognized Spider and BIRD benchmarks among the open-source models. Specifically, SQLForge-LM achieves EX accuracy of 85.7% on Spider Dev and 59.8% on BIRD Dev, significantly narrowing the performance gap with closed-source methods.

[Arxiv](https://arxiv.org/abs/2505.13725)