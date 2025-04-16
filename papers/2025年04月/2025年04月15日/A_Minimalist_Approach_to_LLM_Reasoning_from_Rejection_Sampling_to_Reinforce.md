# # 极简主义视角下的LLM推理：从拒绝采样到强化学习

发布时间：2025年04月15日

`LLM理论` `人工智能` `机器学习`

> A Minimalist Approach to LLM Reasoning: from Rejection Sampling to Reinforce

# 摘要

> 强化学习（RL）已成为微调大型语言模型（LLM）处理复杂推理任务的主要方法。在近期的方法中，GRPO因成功训练DeepSeek-R1等模型而引人注目，但其有效性的根源仍不明确。本研究从类似强化学习的算法视角重新审视GRPO，并对其核心组件进行深入分析。令人惊讶的是，我们发现，RAFT这一简单拒绝采样基线，仅基于正向奖励样本训练，却能与GRPO和PPO相媲美。通过消融实验，我们发现GRPO的主要优势在于筛选出完全错误的提示，而非其奖励归一化机制。受此启发，我们提出Reinforce-Rej，这一基于政策梯度的极简扩展方法，能够同时筛选完全错误和完全正确的样本。Reinforce-Rej在KL效率和稳定性方面表现更优，为更复杂的RL算法提供了一种轻量而有效的替代方案。我们主张将RAFT作为稳健且可解释的基线，并建议未来研究应专注于更系统地整合负样本的设计，而非盲目依赖。我们的发现为基于奖励的LLM后训练研究提供了重要指导。

> Reinforcement learning (RL) has become a prevailing approach for fine-tuning large language models (LLMs) on complex reasoning tasks. Among recent methods, GRPO stands out for its empirical success in training models such as DeepSeek-R1, yet the sources of its effectiveness remain poorly understood. In this work, we revisit GRPO from a reinforce-like algorithm perspective and analyze its core components. Surprisingly, we find that a simple rejection sampling baseline, RAFT, which trains only on positively rewarded samples, yields competitive performance than GRPO and PPO. Our ablation studies reveal that GRPO's main advantage arises from discarding prompts with entirely incorrect responses, rather than from its reward normalization. Motivated by this insight, we propose Reinforce-Rej, a minimal extension of policy gradient that filters both entirely incorrect and entirely correct samples. Reinforce-Rej improves KL efficiency and stability, serving as a lightweight yet effective alternative to more complex RL algorithms. We advocate RAFT as a robust and interpretable baseline, and suggest that future advances should focus on more principled designs for incorporating negative samples, rather than relying on them indiscriminately. Our findings provide guidance for future work in reward-based LLM post-training.

[Arxiv](https://arxiv.org/abs/2504.11343)