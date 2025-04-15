# 从笑点到预测：衡量大型语言模型识别单口喜剧幽默性的全新标准

发布时间：2025年04月11日

`LLM应用` `幽默检测`

> From Punchlines to Predictions: A Metric to Assess LLM Performance in Identifying Humor in Stand-Up Comedy

# 摘要

> 喜剧不仅是时代的一面镜子，更是人际交往中不可或缺的调味剂。随着大型语言模型（LLMs）的普及，幽默与人工智能的交叉领域已不再是笑谈。本研究聚焦于模型从单口喜剧剧本中精准识别幽默台词的能力。单口喜剧独特的叙事风格使其成为提升AI幽默理解能力的理想数据集。我们提出了一种新型幽默检测指标，旨在评估不同提示下LLMs提取幽默台词的能力。该指标采用模块化设计，提供模糊字符串匹配、句嵌入和子空间相似度三种评分方法，对模型性能进行全面评估。对比实验显示，无论采用何种提示工程，领先模型ChatGPT、Claude和DeepSeek在幽默检测中的得分均不超过51%。这一表现甚至超越了人类评估者41%的得分。然而，人类评估者与LLMs在判断上的差异，凸显了幽默的主观性以及从现场表演剧本中提取幽默台词的复杂性。代码可在https://github.com/swaggirl9000/humor获取。


> Comedy serves as a profound reflection of the times we live in and is a staple element of human interactions. In light of the widespread adoption of Large Language Models (LLMs), the intersection of humor and AI has become no laughing matter. Advancements in the naturalness of human-computer interaction correlates with improvements in AI systems' abilities to understand humor. In this study, we assess the ability of models in accurately identifying humorous quotes from a stand-up comedy transcript. Stand-up comedy's unique comedic narratives make it an ideal dataset to improve the overall naturalness of comedic understanding. We propose a novel humor detection metric designed to evaluate LLMs amongst various prompts on their capability to extract humorous punchlines. The metric has a modular structure that offers three different scoring methods - fuzzy string matching, sentence embedding, and subspace similarity - to provide an overarching assessment of a model's performance. The model's results are compared against those of human evaluators on the same task. Our metric reveals that regardless of prompt engineering, leading models, ChatGPT, Claude, and DeepSeek, achieve scores of at most 51% in humor detection. Notably, this performance surpasses that of humans who achieve a score of 41%. The analysis of human evaluators and LLMs reveals variability in agreement, highlighting the subjectivity inherent in humor and the complexities involved in extracting humorous quotes from live performance transcripts. Code available at https://github.com/swaggirl9000/humor.

[Arxiv](https://arxiv.org/abs/2504.09049)