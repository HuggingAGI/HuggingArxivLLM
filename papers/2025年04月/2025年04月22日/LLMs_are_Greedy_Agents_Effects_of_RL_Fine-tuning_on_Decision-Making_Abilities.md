# 大型语言模型作为贪婪型智能体：强化学习微调对决策能力的影响

发布时间：2025年04月22日

`LLM应用

摘要讨论了大型语言模型（LLMs）在agent应用中的表现和改进方法，特别是通过强化学习来优化其决策能力。这属于LLM的应用层面，因此归类为LLM应用。` `人工智能` `决策系统`

> LLMs are Greedy Agents: Effects of RL Fine-tuning on Decision-Making Abilities

# 摘要

> 大型语言模型（LLMs）的成功激发了对各种agent应用的探索。一个核心假设是，LLMs能够借助常识和链式推理（Chain-of-Thought, CoT）有效解决复杂问题。然而，LLM代理在探索能力和知行合一上仍存在不足。本研究深入分析了LLMs在决策场景中表现欠佳的原因，重点关注三种典型问题：贪婪决策、频率偏差和知行差距。我们提出通过基于自动生成的CoT理由的强化学习（RL）微调来改善这些缺陷。实验结果表明，RL微调显著提升了LLMs的决策能力，具体表现为探索能力的增强和知行差距的缩小。此外，我们还探讨了经典探索机制（如$ε$-贪婪）和LLM专属方法（如自我修正与自我一致性），为提升LLM的决策能力提供了更有效的微调方案。

> The success of Large Language Models (LLMs) has sparked interest in various agentic applications. A key hypothesis is that LLMs, leveraging common sense and Chain-of-Thought (CoT) reasoning, can effectively explore and efficiently solve complex domains. However, LLM agents have been found to suffer from sub-optimal exploration and the knowing-doing gap, the inability to effectively act on knowledge present in the model. In this work, we systematically study why LLMs perform sub-optimally in decision-making scenarios. In particular, we closely examine three prevalent failure modes: greediness, frequency bias, and the knowing-doing gap. We propose mitigation of these shortcomings by fine-tuning via Reinforcement Learning (RL) on self-generated CoT rationales. Our experiments across multi-armed bandits, contextual bandits, and Tic-tac-toe, demonstrate that RL fine-tuning enhances the decision-making abilities of LLMs by increasing exploration and narrowing the knowing-doing gap. Finally, we study both classic exploration mechanisms, such as $ε$-greedy, and LLM-specific approaches, such as self-correction and self-consistency, to enable more effective fine-tuning of LLMs for decision-making.

[Arxiv](https://arxiv.org/abs/2504.16078)