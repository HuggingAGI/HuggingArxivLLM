# 基于多阶段质量混合的人类反馈的多智能体强化学习

发布时间：2025年03月03日

`Agent` `人工智能` `人机交互`

> : Multi-agent Reinforcement Learning from Multi-phase Human Feedback of Mixed Quality

# 摘要

> 在多智能体强化学习（MARL）中设计有效的奖励函数是一个重大挑战，常常导致在复杂且需要协调的环境中出现次优或不一致的行为。我们提出了一种名为多智能体多阶段混合质量人类反馈强化学习（$	ext{M}^3	ext{HF}$）的新框架，该框架将多阶段混合质量的人类反馈整合到 MARL 的训练过程中。通过让不同专业水平的人类提供迭代指导，$	ext{M}^3	ext{HF}$ 能够结合专家与非专家的反馈，持续优化智能体的策略。在训练过程中，我们通过暂停智能体学习来获取人类评估，利用大型语言模型解析反馈并进行合理分配，结合预定义模板和自适应权重（采用权重衰减和基于性能的调整）来更新奖励函数。这种方法不仅能够整合不同质量层次的人类见解，还显著提升了多智能体协作的可解释性和鲁棒性。在具有挑战性的环境中，实证结果表明 $	ext{M}^3	ext{HF}$ 显著优于现有最先进的方法，成功解决了 MARL 中奖励设计的复杂性，并为人类在训练过程中的广泛参与提供了可能性。

> Designing effective reward functions in multi-agent reinforcement learning (MARL) is a significant challenge, often leading to suboptimal or misaligned behaviors in complex, coordinated environments. We introduce Multi-agent Reinforcement Learning from Multi-phase Human Feedback of Mixed Quality ($\text{M}^3\text{HF}$), a novel framework that integrates multi-phase human feedback of mixed quality into the MARL training process. By involving humans with diverse expertise levels to provide iterative guidance, $\text{M}^3\text{HF}$ leverages both expert and non-expert feedback to continuously refine agents' policies. During training, we strategically pause agent learning for human evaluation, parse feedback using large language models to assign it appropriately and update reward functions through predefined templates and adaptive weight by using weight decay and performance-based adjustments. Our approach enables the integration of nuanced human insights across various levels of quality, enhancing the interpretability and robustness of multi-agent cooperation. Empirical results in challenging environments demonstrate that $\text{M}^3\text{HF}$ significantly outperforms state-of-the-art methods, effectively addressing the complexities of reward design in MARL and enabling broader human participation in the training process.

[Arxiv](https://arxiv.org/abs/2503.02077)