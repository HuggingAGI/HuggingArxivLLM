# 从人类反馈的强化学习中探索数据扩展趋势与影响

发布时间：2025年03月28日

`LLM应用` `人工智能`

> Exploring Data Scaling Trends and Effects in Reinforcement Learning from Human Feedback

# 摘要

> 强化学习从人类反馈中学习 (RLHF) 在使大型语言模型与人类偏好保持一致方面至关重要。然而，尽管近期研究集中于算法改进，但对提示数据构建的重要性却鲜有关注。本文旨在填补这一空白，探讨 RLHF 性能扩展中的数据驱动瓶颈，特别是奖励欺骗和响应多样性的降低。

我们提出了一种结合推理任务验证器 (RTV) 和生成奖励模型 (GenRM) 的混合奖励系统，以有效缓解奖励欺骗问题。同时，我们提出了一种新型提示选择方法 Pre-PPO，以保持响应多样性并提升学习效果。此外，我们发现，在 RLHF 训练初期优先处理数学和编码任务能显著提升性能。

通过跨两个模型规模的实验，我们验证了所提方法的有效性和可扩展性。实验结果显示，RTV 对奖励欺骗的抵抗力最强，其次是结合真实标签的 GenRM，最后是结合 SFT Best-of-N 响应的 GenRM。我们的策略能够快速捕捉任务特定的细微差别，从而实现整体 RLHF 性能的显著提升。这项工作不仅突显了谨慎构建数据的重要性，还提供了实用方法来克服 RLHF 中的性能障碍。

> Reinforcement Learning from Human Feedback (RLHF) is crucial for aligning large language models with human preferences. While recent research has focused on algorithmic improvements, the importance of prompt-data construction has been overlooked. This paper addresses this gap by exploring data-driven bottlenecks in RLHF performance scaling, particularly reward hacking and decreasing response diversity. We introduce a hybrid reward system combining reasoning task verifiers (RTV) and a generative reward model (GenRM) to mitigate reward hacking. We also propose a novel prompt-selection method, Pre-PPO, to maintain response diversity and enhance learning effectiveness. Additionally, we find that prioritizing mathematical and coding tasks early in RLHF training significantly improves performance. Experiments across two model sizes validate our methods' effectiveness and scalability. Results show that RTV is most resistant to reward hacking, followed by GenRM with ground truth, and then GenRM with SFT Best-of-N responses. Our strategies enable rapid capture of subtle task-specific distinctions, leading to substantial improvements in overall RLHF performance. This work highlights the importance of careful data construction and provides practical methods to overcome performance barriers in RLHF.

[Arxiv](https://arxiv.org/abs/2503.22230)