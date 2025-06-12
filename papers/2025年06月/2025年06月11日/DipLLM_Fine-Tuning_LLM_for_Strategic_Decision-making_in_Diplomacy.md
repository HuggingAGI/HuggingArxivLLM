# DipLLM：为外交战略决策优化的大型语言模型微调

发布时间：2025年06月11日

`LLM应用` `战略决策`

> DipLLM: Fine-Tuning LLM for Strategic Decision-making in Diplomacy

# 摘要

> 《Diplomacy》是一款复杂的多人策略游戏，既需要合作又需要竞争，这对AI系统来说是一大挑战。传统方法通过寻找均衡点生成大量训练数据，但这种方式需要巨大的计算资源。大型语言模型（LLMs）提供了一种更高效的方式，它利用预训练知识，只需少量微调就能表现出色。然而，《Diplomacy》中复杂的策略互动和指数级增长的动作组合仍然给LLMs的应用带来了困难。为了解决这一问题，我们提出了DipLLM——一种基于LLM的微调智能体，专注于学习《Diplomacy》的均衡策略。DipLLM采用自回归分解框架，将复杂的多单元动作分配简化为一系列单元级别的决策过程。通过将均衡策略作为学习目标，我们仅使用了当前最优Cicero模型1.5%的数据量就完成了微调，并取得了更好的性能表现。这证明了微调后的LLMs在解决复杂多人游戏中的战略决策问题方面具有巨大潜力。

> Diplomacy is a complex multiplayer game that requires both cooperation and competition, posing significant challenges for AI systems. Traditional methods rely on equilibrium search to generate extensive game data for training, which demands substantial computational resources. Large Language Models (LLMs) offer a promising alternative, leveraging pre-trained knowledge to achieve strong performance with relatively small-scale fine-tuning. However, applying LLMs to Diplomacy remains challenging due to the exponential growth of possible action combinations and the intricate strategic interactions among players. To address this challenge, we propose DipLLM, a fine-tuned LLM-based agent that learns equilibrium policies for Diplomacy. DipLLM employs an autoregressive factorization framework to simplify the complex task of multi-unit action assignment into a sequence of unit-level decisions. By defining an equilibrium policy within this framework as the learning objective, we fine-tune the model using only 1.5% of the data required by the state-of-the-art Cicero model, surpassing its performance. Our results demonstrate the potential of fine-tuned LLMs for tackling complex strategic decision-making in multiplayer games.

[Arxiv](https://arxiv.org/abs/2506.09655)