# # 将大型语言模型与法律体系相结合？可处罚仇恨言论的识别

发布时间：2025年06月03日

`LLM应用` `法律技术`

> Conditioning Large Language Models on Legal Systems? Detecting Punishable Hate Speech

# 摘要

> 评估法律问题需要考虑特定的法律体系及其抽象层次，从宪法到成文法再到判例法。然而，模型在多大程度上能够内化这些法律体系仍是一个未知数。本文提出并研究了在法律体系的不同抽象层次上对LLMs进行条件设置的不同方法。我们探讨了在法律体系的多个抽象层次上对LLMs进行条件设置的方法，以识别可能受处罚的仇恨言论。具体而言，我们专注于根据德国刑法典规定，对特定社交媒体帖子是否构成煽动仇恨的刑事犯罪进行分类的任务。研究结果表明，无论模型是以何种抽象层次进行条件设置，在仇恨言论的法律评估方面，模型与法律专家之间仍然存在显著的性能差距。我们的分析发现，基于抽象法律知识进行条件设置的模型缺乏对任务的深入理解，常常自相矛盾并产生幻觉回答，而使用具体法律知识的模型在识别相关目标群体方面表现尚可，但在对目标行为进行分类时则显得力不从心。

> The assessment of legal problems requires the consideration of a specific legal system and its levels of abstraction, from constitutional law to statutory law to case law. The extent to which Large Language Models (LLMs) internalize such legal systems is unknown. In this paper, we propose and investigate different approaches to condition LLMs at different levels of abstraction in legal systems. This paper examines different approaches to conditioning LLMs at multiple levels of abstraction in legal systems to detect potentially punishable hate speech. We focus on the task of classifying whether a specific social media posts falls under the criminal offense of incitement to hatred as prescribed by the German Criminal Code. The results show that there is still a significant performance gap between models and legal experts in the legal assessment of hate speech, regardless of the level of abstraction with which the models were conditioned. Our analysis revealed, that models conditioned on abstract legal knowledge lacked deep task understanding, often contradicting themselves and hallucinating answers, while models using concrete legal knowledge performed reasonably well in identifying relevant target groups, but struggled with classifying target conducts.

[Arxiv](https://arxiv.org/abs/2506.03009)