# 基于好奇心的强化学习：从人类反馈中学习

发布时间：2025年01月20日

`LLM理论

理由：这篇论文主要讨论了基于人类反馈的强化学习（RLHF）在大型语言模型（LLMs）中的应用，并提出了一种新的好奇心驱动的RLHF（CD-RLHF）框架，以优化输出多样性和对齐质量。论文的核心内容涉及LLM的训练和优化方法，属于对LLM的理论研究和改进，因此应归类为LLM理论。`

> Curiosity-Driven Reinforcement Learning from Human Feedback

# 摘要

> # 摘要
基于人类反馈的强化学习（RLHF）在使大型语言模型（LLMs）与人类偏好对齐方面表现出色，但常常牺牲了输出的多样性。多样性与对齐质量之间的权衡仍是一个重大挑战。受强化学习中好奇心驱动探索的启发，我们提出了好奇心驱动的RLHF（CD-RLHF），该框架通过引入新颖状态的内在奖励和传统稀疏外在奖励，优化了输出多样性和对齐质量。我们通过一系列任务（如文本摘要和指令遵循）的实验验证了CD-RLHF的有效性。该方法在多个多样性指标上显著提升了多样性，同时保持了与标准RLHF相当的人类偏好对齐。代码已开源：https://github.com/ernie-research/CD-RLHF。

> Reinforcement learning from human feedback (RLHF) has proven effective in aligning large language models (LLMs) with human preferences, but often at the cost of reduced output diversity. This trade-off between diversity and alignment quality remains a significant challenge. Drawing inspiration from curiosity-driven exploration in reinforcement learning, we introduce curiosity-driven RLHF (CD-RLHF), a framework that incorporates intrinsic rewards for novel states, alongside traditional sparse extrinsic rewards, to optimize both output diversity and alignment quality. We demonstrate the effectiveness of CD-RLHF through extensive experiments on a range of tasks, including text summarization and instruction following. Our approach achieves significant gains in diversity on multiple diversity-oriented metrics while maintaining alignment with human preferences comparable to standard RLHF. We make our code publicly available at https://github.com/ernie-research/CD-RLHF.

[Arxiv](https://arxiv.org/abs/2501.11463)