# SAFER：基于稀疏自编码器的奖励模型安全性探究

发布时间：2025年07月01日

`LLM理论` `人工智能安全` `模型对齐`

> SAFER: Probing Safety in Reward Models with Sparse Autoencoder

# 摘要

> 人类反馈强化学习（RLHF）是使大型语言模型（LLMs）与人类价值观对齐的关键范式，但其核心奖励模型仍存在不透明性。为此，我们提出了稀疏自动编码器增强奖励模型（	extbf{SAFER}），一种通过机制分析来解释和改进奖励模型的新颖框架。借助稀疏自动编码器（SAEs），我们揭示了奖励模型激活中可被人理解的特征，从而能够深入了解与安全性相关的决策过程。将SAFER应用于安全导向的偏好数据集后，我们通过选择和拒绝响应之间的激活差异量化了单个特征的重要性。利用这些特征级别的信号，我们设计了有针对性的数据投毒和去噪策略。实验表明，SAFER可以在不牺牲通用聊天性能的情况下，通过最小的数据修改精确地降低或提升安全性对齐。我们的方法为在高风险的LLM对齐任务中解释、审核和优化奖励模型做出了贡献。我们的代码可在https://github.com/xzy-101/SAFER-code获取。	extit{本文讨论了与大型语言模型安全相关的话题，可能包含突出潜在风险或不安全结果的讨论或示例。}

> Reinforcement learning from human feedback (RLHF) is a key paradigm for aligning large language models (LLMs) with human values, yet the reward models at its core remain largely opaque. In this work, we present sparse Autoencoder For Enhanced Reward model (\textbf{SAFER}), a novel framework for interpreting and improving reward models through mechanistic analysis. Leveraging Sparse Autoencoders (SAEs), we uncover human-interpretable features in reward model activations, enabling insight into safety-relevant decision-making. We apply SAFER to safety-oriented preference datasets and quantify the salience of individual features by activation differences between chosen and rejected responses. Using these feature-level signals, we design targeted data poisoning and denoising strategies. Experiments show that SAFER can precisely degrade or enhance safety alignment with minimal data modification, without sacrificing general chat performance. Our approach contributes to interpreting, auditing and refining reward models in high-stakes LLM alignment tasks. Our codes are available at https://github.com/xzy-101/SAFER-code. \textit{This paper discusses topics related to large language model safety and may include discussions or examples that highlight potential risks or unsafe outcomes.}

[Arxiv](https://arxiv.org/abs/2507.00665)