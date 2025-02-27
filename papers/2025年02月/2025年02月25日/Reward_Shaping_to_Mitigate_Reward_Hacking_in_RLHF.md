# # 奖励塑造：缓解强化学习中人类反馈奖励机制的操控问题

发布时间：2025年02月25日

`LLM应用

理由：这篇论文探讨了如何通过强化学习（RLHF）将大型语言模型与人类价值观对齐，特别是通过奖励塑造来缓解奖励欺骗问题。它提出了一个新的方法PAR，并进行了实验验证，展示了其在实际应用中的效果。因此，它属于LLM应用类别。` `人工智能` `人工智能伦理`

> Reward Shaping to Mitigate Reward Hacking in RLHF

# 摘要

> 从人类反馈中学习的强化学习（RLHF）对于将大型语言模型（LLMs）与人类价值观对齐至关重要。然而，RLHF容易受到奖励欺骗的影响，即代理利用奖励函数中的缺陷，而非学习预期行为，从而降低对齐效果。尽管奖励塑造有助于稳定RLHF并部分缓解奖励欺骗，但对塑造技术及其潜在原理的系统性研究仍然不足。为填补这一空白，我们对流行的奖励塑造方法进行了全面研究。我们的分析揭示了三个关键设计原则：（1）RL奖励的理想状态是有界的，（2）RL从初始快速增长随后逐步收敛中受益，（3）RL奖励最好被设计为以中心化奖励为函数。基于这些见解，我们提出了Preference As Reward（PAR），一种新颖的方法，它利用奖励模型本身中嵌入的潜在偏好作为强化学习的信号。我们在两个基础模型Gemma2-2B和Llama3-8B上，使用Ultrafeedback-Binarized和HH-RLHF两个数据集对PAR进行了评估。实验结果表明，PAR在其他奖励塑造方法中表现更优。在AlpacaEval 2.0基准测试中，PAR的胜率至少比其他方法高出5个百分点。此外，PAR展现出显著的数据效率，仅需一个参考奖励即可达到最佳性能，并且即使经过两个完整的训练周期后，仍能保持对奖励欺骗的鲁棒性。代码可在https://github.com/PorUna-byte/PAR获取。

> Reinforcement Learning from Human Feedback (RLHF) is essential for aligning large language models (LLMs) with human values. However, RLHF is susceptible to reward hacking, where the agent exploits flaws in the reward function rather than learning the intended behavior, thus degrading alignment. While reward shaping helps stabilize RLHF and partially mitigate reward hacking, a systematic investigation into shaping techniques and their underlying principles remains lacking. To bridge this gap, we present a comprehensive study of the prevalent reward shaping methods. Our analysis suggests three key design principles: (1) RL reward is ideally bounded, (2) RL benefits from rapid initial growth followed by gradual convergence, and (3) RL reward is best formulated as a function of centered reward. Guided by these insights, we propose Preference As Reward (PAR), a novel approach that leverages the latent preferences embedded within the reward model itself as the signal for reinforcement learning. We evaluated PAR on two base models, Gemma2-2B and Llama3-8B, using two datasets, Ultrafeedback-Binarized and HH-RLHF. Experimental results demonstrate PAR's superior performance over other reward shaping methods. On the AlpacaEval 2.0 benchmark, PAR achieves a win rate at least 5 percentage points higher than competing approaches. Furthermore, PAR exhibits remarkable data efficiency, requiring only a single reference reward for optimal performance, and maintains robustness against reward hacking even after two full epochs of training. Code is available at https://github.com/PorUna-byte/PAR.

[Arxiv](https://arxiv.org/abs/2502.18770)