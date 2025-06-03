# Dyna-Think：融合推理、行动与世界模型模拟的智能体

发布时间：2025年05月30日

`Agent` `人工智能`

> Dyna-Think: Synergizing Reasoning, Acting, and World Model Simulation in AI Agents

# 摘要

> 大型语言模型（LLMs）在推理领域取得了显著进展，例如DeepSeek-R1在数学和编码等领域表现出色，展现了验证、目标分解和自我反思等复杂认知行为。然而，针对长期任务的AI代理，哪些行为有效以及哪些行为缺失仍不明确。本研究提出了Dyna-Think框架，将规划与内部世界模型、推理和行动相结合，以提升AI代理的性能。为实现Dyna-Think，我们提出了Dyna-Think模仿学习（DIT）和Dyna-Think动态训练（DDT）。DIT通过重构R1的思考过程，专注于与提议动作相关的内部世界模型模拟，并利用重构数据训练策略以初始化Dyna-Think。DDT采用两阶段训练：首先通过状态预测或批判生成等目标提升代理的世界建模能力，然后通过策略训练优化代理动作。我们在OSWorld上的评估表明，Dyna-Think显著提升了代理的领域内和领域外性能，与R1相比达到相似的最佳性能，同时平均生成的标记数减少了一半。我们的研究表明，1）利用批判生成进行世界模型训练有效提升了策略性能；2）AI代理的优异表现与其强大的世界建模能力密切相关。我们相信，将世界模型模拟整合到AI代理中以增强其推理、规划和行动能力，是一个极具潜力的研究方向。

> Recent progress in reasoning with large language models (LLMs), such as DeepSeek-R1, demonstrates impressive capabilities in domains like mathematics and coding, by exhibiting complex cognitive behaviors such as verification, goal decomposition, and self-reflection. However, it is unclear what behavior is effective and what behavior is missing for long-horizon AI agents tasks. In this work, we propose Dyna-Think, a thinking framework that integrates planning with an internal world model with reasoning and acting to enhance AI agent performance. To enable Dyna-Think, we propose Dyna-Think Imitation Learning (DIT) and Dyna-Think Dyna Training (DDT). To initialize a policy with Dyna-Think, DIT reconstructs the thinking process of R1 to focus on performing world model simulation relevant to the proposed (and planned) action, and trains the policy using this reconstructed data. To enhance Dyna-Think, DDT uses a two-stage training process to first improve the agent's world modeling ability via objectives such as state prediction or critique generation, and then improve the agent's action via policy training. We evaluate our methods on OSWorld, and demonstrate that Dyna-Think improves the agent's in-domain and out-of-domain performance, achieving similar best-of-n performance compared to R1 while generating 2x less tokens on average. Our extensive empirical studies reveal that 1) using critique generation for world model training is effective to improve policy performance; and 2) AI agents with better performance correlate with better world modeling abilities. We believe our results suggest a promising research direction to integrate world model simulation into AI agents to enhance their reasoning, planning, and acting capabilities.

[Arxiv](https://arxiv.org/abs/2506.00320)