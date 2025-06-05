# 人工智能辅助语言学习中生成文本难度的控制

发布时间：2025年06月04日

`LLM应用` `语言学习`

> Controlling Difficulty of Generated Text for AI-Assisted Language Learning

# 摘要

> 与大型语言模型（LLMs）进行对话练习为传统面对面语言学习提供了一个有前途的替代方案。然而，大多数LLMs生成的文本复杂度接近母语者水平，这使得它们不适合初级学习者（CEFR：A1-A2）。本文探讨了可控生成技术——特别是无需微调模型的模块化方法——是否能调整LLMs的输出，以更好地支持绝对初级的学习者。我们通过自动指标和针对日语大学学习者进行的用户研究来评估这些方法。研究发现，尽管单独使用提示无法有效控制输出难度，但使用未来判别器（Yang和Klein，2021）显著提高了输出的可理解性（从40.4%提升到84.3%）。我们还引入了一种新的基于token的评估指标Token Miss Rate（TMR），它量化了每条 utterance 中不可理解的token比例，并与人工判断高度相关。为了支持未来在AI辅助语言学习领域的研究，我们公开发布了我们的代码、模型、标注工具和数据集。

> Practicing conversations with large language models (LLMs) presents a promising alternative to traditional in-person language learning. However, most LLMs generate text at a near-native level of complexity, making them ill-suited for beginner learners (CEFR: A1-A2). In this paper, we investigate whether controllable generation techniques -- specifically modular methods that do not require model fine-tuning -- can adapt LLM outputs to better support absolute beginners. We evaluate these methods through both automatic metrics and a user study with university-level learners of Japanese. Our findings show that while prompting alone fails to control output difficulty, the use of future discriminators (Yang and Klein, 2021) significantly improves output comprehensibility (from 40.4\% to 84.3\%). We further introduce a novel token-level evaluation metric, Token Miss Rate (TMR), that quantifies the proportion of incomprehensible tokens per utterance and correlates strongly with human judgments. To support future research in AI-assisted language learning, we release our code, models, annotation tools, and dataset.

[Arxiv](https://arxiv.org/abs/2506.04072)