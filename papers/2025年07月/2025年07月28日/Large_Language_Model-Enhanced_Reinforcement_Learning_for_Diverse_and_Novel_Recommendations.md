# 大型语言模型增强的强化学习，助力多样化且新颖的推荐

发布时间：2025年07月28日

`LLM应用` `推荐系统`

> Large Language Model-Enhanced Reinforcement Learning for Diverse and Novel Recommendations

# 摘要

> 推荐系统中，多样性和新颖性对捕捉用户偏好和激发探索至关重要，但许多系统仍侧重于点击相关性。尽管强化学习（RL）曾被用于提升多样性，但其随机探索常偏离用户兴趣。为此，我们提出LAAC（LLM引导的对抗式Actor-Critic），一种创新方法，通过大型语言模型（LLMs）作为参考策略推荐新颖内容，同时训练轻量级策略，结合系统数据优化建议。LAAC采用Actor-Critic网络间的双层优化，让Critic有选择地青睐有潜力的新颖行动，Actor则能超越LLM推荐，持续优化策略。为缓解LLM建议的高估问题，我们引入正则化，将未探索项目的Critic值锚定在已良好估计的数据集动作附近。真实数据集实验显示，LAAC在多样性、新颖性和准确性上超越现有基线，且在不平衡数据上表现稳健，成功整合LLM知识，无需昂贵微调。

> In recommendation systems, diversity and novelty are essential for capturing varied user preferences and encouraging exploration, yet many systems prioritize click relevance. While reinforcement learning (RL) has been explored to improve diversity, it often depends on random exploration that may not align with user interests. We propose LAAC (LLM-guided Adversarial Actor Critic), a novel method that leverages large language models (LLMs) as reference policies to suggest novel items, while training a lightweight policy to refine these suggestions using system-specific data. The method formulates training as a bilevel optimization between actor and critic networks, enabling the critic to selectively favor promising novel actions and the actor to improve its policy beyond LLM recommendations. To mitigate overestimation of unreliable LLM suggestions, we apply regularization that anchors critic values for unexplored items close to well-estimated dataset actions. Experiments on real-world datasets show that LAAC outperforms existing baselines in diversity, novelty, and accuracy, while remaining robust on imbalanced data, effectively integrating LLM knowledge without expensive fine-tuning.

[Arxiv](https://arxiv.org/abs/2507.21274)