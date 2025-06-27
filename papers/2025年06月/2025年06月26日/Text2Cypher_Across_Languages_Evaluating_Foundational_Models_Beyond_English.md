# Text2Cypher跨语言研究：评估基础模型在多语言环境中的表现

发布时间：2025年06月26日

`LLM应用` `数据库` `多语言处理`

> Text2Cypher Across Languages: Evaluating Foundational Models Beyond English

# 摘要

> 大型语言模型的最新进展推动了自然语言界面的发展，使其能够将用户问题转化为数据库查询，如Text2SQL、Text2SPARQL和Text2Cypher。这些界面虽然提升了数据库的可访问性，但目前研究主要集中在英语上，对其他语言的评估仍显不足。本文研究了基础大型语言模型在Text2Cypher任务上的多语言性能表现。我们创建并发布了一个多语言测试集，将英语问题翻译为西班牙语和土耳其语，同时保留原始Cypher查询，以实现公平的跨语言比较。通过标准化提示和指标，我们评估了多个基础模型。结果显示了一致的性能模式：英语最好，西班牙语次之，土耳其语最差。这一现象主要归因于训练数据可用性和语言特征的差异。此外，我们还研究了将任务提示翻译成西班牙语和土耳其语的影响。结果表明，评估指标几乎没有变化，提示翻译的影响较小。我们的发现凸显了在多语言查询生成领域开展更具包容性的评估与开发的重要性。未来的研究方向包括模式本地化和跨多种语言的微调工作。

> Recent advances in large language models have enabled natural language interfaces that translate user questions into database queries, such as Text2SQL, Text2SPARQL, and Text2Cypher. While these interfaces enhance database accessibility, most research today focuses solely on English, with limited evaluation in other languages. This paper investigates the performance of foundational LLMs on the Text2Cypher task across multiple languages. We create and release a multilingual test set by translating English questions into Spanish and Turkish while preserving the original Cypher queries, enabling fair cross-lingual comparison. We evaluate multiple foundational models using standardized prompts and metrics. Our results show a consistent performance pattern: highest on English, then Spanish, and lowest on Turkish. We attribute this to differences in training data availability and linguistic characteristics. Additionally, we explore the impact of translating task prompts into Spanish and Turkish. Results show little to no change in evaluation metrics, suggesting prompt translation has minor impact. Our findings highlight the need for more inclusive evaluation and development in multilingual query generation. Future work includes schema localization and fine-tuning across diverse languages.

[Arxiv](https://arxiv.org/abs/2506.21445)