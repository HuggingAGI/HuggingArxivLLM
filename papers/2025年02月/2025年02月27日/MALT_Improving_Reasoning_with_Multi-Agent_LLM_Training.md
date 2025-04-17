# MALT：利用多智能体LLM训练优化推理能力

发布时间：2025年02月27日

`LLM理论` `人工智能`

> MALT: Improving Reasoning with Multi-Agent LLM Training

# 摘要

> 大型语言模型（LLMs）通常只能生成单一的思维链答案，这限制了它们在复杂任务中探索不同推理路径或自我修正错误输出的能力。本文中，我们提出了MALT（多智能体LLM训练），这是一种新颖的后训练策略。通过异质智能体的顺序流水线，MALT将推理过程分解为生成、验证和优化三个步骤。在数据生成阶段，每个智能体被反复采样以形成一个多智能体搜索树，最终输出与真实数据进行对比评分。随后，我们应用价值迭代将奖励信号回传至每个条件化模型，无需人工或教师模型监督，自动产生多智能体后训练数据。我们的无策略方法允许每个智能体通过学习正确与错误轨迹实现专业化，最终提升端到端推理链。在MATH、GSM8K和CSQA数据集上，MALT相较于同一基线LLM分别实现了15.66%、7.42%和9.40%的相对提升，标志着向多智能体协作训练的重要迈进。

> Large Language Models (LLMs) often produce answers with a single chain-of-thought, which restricts their ability to explore reasoning paths or self-correct flawed outputs in complex tasks. In this paper, we introduce MALT (Multi-Agent LLM Training), a novel post-training strategy that divides the reasoning process into generation, verification, and refinement steps using a sequential pipeline of heterogeneous agents. During data generation, each agent is repeatedly sampled to form a multi-agent search tree, where final outputs are graded against ground-truth data. We then apply value iteration to propagate reward signals back to each role-conditioned model, automatically producing multi-agent post-training data without human or teacher-model supervision. Our off-policy approach allows each agent to specialize by learning from correct and incorrect trajectories, ultimately improving the end-to-end reasoning chain. On MATH, GSM8K, and CSQA, MALT surpasses the same baseline LLM with a relative improvement of 15.66%, 7.42%, and 9.40% respectively, making it an important advance towards multi-agent cooperative training.

[Arxiv](https://arxiv.org/abs/2412.01928)