# SAFE-SQL: 基于自增强上下文学习与细粒度示例选择的文本到SQL转换方法

发布时间：2025年02月16日

`LLM应用` `数据库`

> SAFE-SQL: Self-Augmented In-Context Learning with Fine-grained Example Selection for Text-to-SQL

# 摘要

> Text-to-SQL旨在将自然语言问题转换为可执行的SQL查询。虽然之前的方法，如骨架掩码选择，通过检索相似的训练示例来引导大型语言模型（LLMs）表现出强大的性能，但在现实场景中，当缺乏这些示例时，它们往往表现不佳。为了解决这一问题，我们提出了SAFE-SQL框架，它通过生成和筛选自增广示例来提升SQL生成效果。SAFE-SQL首先提示一个LLM生成多个与测试输入相关的Text-to-SQL示例，然后通过三个相关性评估筛选这些示例，构建高质量的上下文学习示例。利用自生成的示例，SAFE-SQL不仅超越了之前的零样本和少样本Text-to-SQL框架，还实现了更高的执行准确性。特别地，我们的方法在额外困难和未见场景中表现更优，而传统方法往往在此类场景中失效。

> Text-to-SQL aims to convert natural language questions into executable SQL queries. While previous approaches, such as skeleton-masked selection, have demonstrated strong performance by retrieving similar training examples to guide large language models (LLMs), they struggle in real-world scenarios where such examples are unavailable. To overcome this limitation, we propose Self-Augmentation in-context learning with Fine-grained Example selection for Text-to-SQL (SAFE-SQL), a novel framework that improves SQL generation by generating and filtering self-augmented examples. SAFE-SQL first prompts an LLM to generate multiple Text-to-SQL examples relevant to the test input. Then SAFE-SQL filters these examples through three relevance assessments, constructing high-quality in-context learning examples. Using self-generated examples, SAFE-SQL surpasses the previous zero-shot, and few-shot Text-to-SQL frameworks, achieving higher execution accuracy. Notably, our approach provides additional performance gains in extra hard and unseen scenarios, where conventional methods often fail.

[Arxiv](https://arxiv.org/abs/2502.11438)