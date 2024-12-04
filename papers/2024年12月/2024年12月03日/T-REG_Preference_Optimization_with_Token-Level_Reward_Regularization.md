# T-REG：基于令牌级别奖励正则化的偏好优化

发布时间：2024年12月03日

`LLM应用` `语言模型`

> T-REG: Preference Optimization with Token-Level Reward Regularization

# 摘要

> 强化学习从人类反馈（RLHF）对于让大型语言模型（LLMs）契合人类价值观起着关键作用。传统的 RLHF 是对查询生成回应，并用奖励模型给整个回应赋予奖励。然而，这种方式因依赖单一稀疏奖励而面临难题，导致模型难以辨别序列中哪些部分对最终奖励贡献最大。近期的方法试图引入令牌级奖励来克服这一局限。但这些方法往往依赖训练好的信用分配模型或 AI 标注员，令人对奖励的质量和可靠性产生担忧。在本文中，我们提出了令牌级奖励正则化（T-REG）这一新颖的方法，它利用序列级和令牌级奖励来进行偏好优化。借助 LLMs 的自我完善能力，我们的方法通过对比提示让 LLMs 能够自行生成令牌级奖励。这些自我生成的奖励随后作为奖励正则化，引导模型更有效地在令牌间分配序列级奖励。这有利于更优的令牌级信用分配，并提升对齐性能。在包括 Alpaca Eval 2 和 Arena-Hard 在内的指令遵循基准测试中，实验表明我们的方法分别比基线方法始终高出多达 3.8％和 4.4％。我们会在 https://github.com/wzhouad/T-REG 上发布代码和模型。

> Reinforcement learning from human feedback (RLHF) has been crucial in aligning large language models (LLMs) with human values. Traditionally, RLHF involves generating responses to a query and using a reward model to assign a reward to the entire response. However, this approach faces challenges due to its reliance on a single, sparse reward, which makes it challenging for the model to identify which parts of the sequence contribute most significantly to the final reward. Recent methods have attempted to address this limitation by introducing token-level rewards. However, these methods often rely on either a trained credit assignment model or AI annotators, raising concerns about the quality and reliability of the rewards. In this paper, we propose token-level reward regularization (T-REG), a novel approach that leverages both sequence-level and token-level rewards for preference optimization. Harnessing the self-refinement capabilities of LLMs, our method uses contrastive prompting to enable LLMs to self-generate token-level rewards. These self-generated rewards then act as reward regularization, guiding the model to more effectively distribute sequence-level rewards across tokens. This facilitates better token-level credit assignment and enhances alignment performance. Experiments on the instruction following benchmarks, including Alpaca Eval 2 and Arena-Hard, show that our method consistently outperforms baseline methods by up to 3.8% and 4.4%, respectively. We will release the code and models at https://github.com/wzhouad/T-REG.

[Arxiv](https://arxiv.org/abs/2412.02685)