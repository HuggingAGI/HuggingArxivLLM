# 奖励不确定性：强化学习视角下的模型信心校准探索

发布时间：2025年03月04日

`LLM理论` `人工智能伦理` `可信AI`

> Rewarding Doubt: A Reinforcement Learning Approach to Confidence Calibration of Large Language Models

# 摘要

> 要确保大型语言模型（LLMs）的安全与可信使用，离不开对其答案信心的准确表达。我们提出了一种全新的强化学习（RL）方法，用于提升LLMs的信心校准能力。通过微调，我们让模型在回答事实性问题时能够提供经过校准的信心估计。我们将这一问题建模为一个下注游戏，模型在每次给出答案时都会预测一个信心分数，同时设计了一个奖励函数来同时惩罚过高和过低的信心。我们证明，在这种奖励设计下，最优策略将导致完美校准的信心估计。实验结果表明，这种方法不仅显著提升了信心校准效果，还在不重新训练的情况下实现了对新任务的良好推广能力。这表明，我们的方法培养了一种普遍的信心意识，为训练固有校准的LLMs提供了可能。

> A safe and trustworthy use of Large Language Models (LLMs) requires an accurate expression of confidence in their answers. We introduce a novel Reinforcement Learning (RL) approach for LLM calibration that fine-tunes LLMs to elicit calibrated confidence estimations in their answers to factual questions. We model the problem as a betting game where the model predicts a confidence score together with every answer, and design a reward function that penalizes both over and under-confidence. We prove that under our reward design an optimal policy would result in a perfectly calibrated confidence estimation. Our experiments demonstrate significantly improved confidence calibration and generalization to new tasks without re-training, indicating that our approach teaches a general confidence awareness. This approach enables the training of inherently calibrated LLMs.

[Arxiv](https://arxiv.org/abs/2503.02623)