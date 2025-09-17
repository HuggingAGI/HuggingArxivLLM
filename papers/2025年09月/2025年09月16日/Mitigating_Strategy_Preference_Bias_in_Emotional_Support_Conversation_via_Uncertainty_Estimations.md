# 借助不确定性估计缓解情感支持对话中的策略偏好偏差

发布时间：2025年09月16日

`强化学习` `医疗健康`

> Mitigating Strategy Preference Bias in Emotional Support Conversation via Uncertainty Estimations

# 摘要

> 情感支持对话（ESC）旨在通过共情对话缓解痛苦，但大型语言模型（LLMs）在提供有效情感支持对话时仍面临持续挑战——策略规划准确性不足，且对特定策略存在明显的偏好偏差。尽管使用微调策略规划器的现有方法已展现出减少这类偏差的潜力，但LLMs偏好偏差的深层原因尚未得到充分探究。为解决这些问题，我们首先通过识别LLMs在策略规划中的知识边界，揭示了偏差的根本成因；随后提出一种基于双奖励函数的强化学习方法以减轻偏差，该方法根据知识边界，通过各区域的准确性和基于熵的置信度优化策略规划。在EScov和ExTES数据集上，使用多个LLM骨干模型的实验结果表明，我们的方法性能优于基线模型，验证了所提方法的有效性。

> Emotional support conversation (ESC) aims to alleviate distress through empathetic dialogue, yet large language models (LLMs) face persistent challenges in delivering effective ESC due to low accuracy in strategy planning. Moreover, there is a considerable preference bias towards specific strategies. Prior methods using fine-tuned strategy planners have shown potential in reducing such bias, while the underlying causes of the preference bias in LLMs have not well been studied. To address these issues, we first reveal the fundamental causes of the bias by identifying the knowledge boundaries of LLMs in strategy planning. Then, we propose an approach to mitigate the bias by reinforcement learning with a dual reward function, which optimizes strategy planning via both accuracy and entropy-based confidence for each region according to the knowledge boundaries. Experiments on the ESCov and ExTES datasets with multiple LLM backbones show that our approach outperforms the baselines, confirming the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.12661)