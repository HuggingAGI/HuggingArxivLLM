# 从英语主导到双语高效：为低资源语言定制分词器的大型语言模型

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论的是如何开发支持多种语言的双语基础大型语言模型（LLMs），并针对特定语言进行了实验和评估。这属于LLM在实际应用中的改进和优化，因此分类为LLM应用。` `多语言支持`

> From English-Centric to Effective Bilingual: LLMs with Custom Tokenizers for Underrepresented Languages

# 摘要

> 本文提出了一种模型无关的高效方法，用于开发支持英语和任意目标语言的双语基础大型语言模型（LLMs）。该方法涵盖词汇扩展、新嵌入初始化、模型训练与评估。我们针对乌克兰语、阿拉伯语和格鲁吉亚语这三种非拉丁字母语言进行了实验。结果表明，该方法在降低计算成本的同时提升了语言性能，有效缓解了对少数语言的不公平惩罚，减少了代码切换和语法错误等问题。此外，我们引入了新的语言质量评估指标，发现词汇量对生成文本质量有显著影响。

> In this paper, we propose a model-agnostic cost-effective approach to developing bilingual base large language models (LLMs) to support English and any target language. The method includes vocabulary expansion, initialization of new embeddings, model training and evaluation. We performed our experiments with three languages, each using a non-Latin script - Ukrainian, Arabic, and Georgian.
  Our approach demonstrates improved language performance while reducing computational costs. It mitigates the disproportionate penalization of underrepresented languages, promoting fairness and minimizing adverse phenomena such as code-switching and broken grammar. Additionally, we introduce new metrics to evaluate language quality, revealing that vocabulary size significantly impacts the quality of generated text.

[Arxiv](https://arxiv.org/abs/2410.18836)