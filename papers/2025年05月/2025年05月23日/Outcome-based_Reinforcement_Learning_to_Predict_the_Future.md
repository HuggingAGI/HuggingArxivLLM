# # 基于结果的强化学习：预测未来

发布时间：2025年05月23日

`LLM应用

理由：这篇论文主要探讨了如何通过强化学习（RLVR）来提升大型语言模型在预测任务中的性能，属于应用层面的创新。`

> Outcome-based Reinforcement Learning to Predict the Future

# 摘要

> 可验证奖励的强化学习（RLVR）在大型语言模型中显著提升了数学和编程能力，但将其扩展到复杂现实领域如预测方面仍鲜有尝试。一个关键挑战在于，基于结果的强化学习在预测任务中必须处理二元、延迟且噪声的奖励信号，这使得标准微调方法难以应对。我们发现，通过将两大领先算法——组相对策略优化（GRPO）和ReMax——适应于预测场景，可以在140亿参数模型上实现与前沿水平相当的预测精度，并在校准和假设性预测市场押注中超越现有方法。我们的改进包括：移除GRPO中每个问题的方差缩放，应用ReMax中的基线减去优势策略，通过10万条时间一致的合成问题丰富训练数据，并引入轻量级约束机制，对 nonsensical、非英语回答及缺乏推理过程的行为进行惩罚，从而实现对11万事件的稳定训练。将ReMax扩展至11万问题并集成七种预测方法，最终得到一个140亿参数模型，在保留集上（Brier = 0.193，p = 0.23）达到与前沿基准o1相当的预测精度，同时在模型校准（ECE = 0.042，p < 0.001）方面显著领先。一个简单的交易规则将这种校准优势转化为127美元的假设性收益，而o1仅实现92美元（p = 0.037）。这表明，经过优化的RLVR方法能够将小型规模的LLM转化为具有潜在经济价值的预测工具，并为未来扩展至更大规模模型提供了启示。

> Reinforcement learning with verifiable rewards (RLVR) has boosted math and coding in large language models, yet there has been little effort to extend RLVR into messier, real-world domains like forecasting. One sticking point is that outcome-based reinforcement learning for forecasting must learn from binary, delayed, and noisy rewards, a regime where standard fine-tuning is brittle. We show that outcome-only online RL on a 14B model can match frontier-scale accuracy and surpass it in calibration and hypothetical prediction market betting by adapting two leading algorithms, Group-Relative Policy Optimisation (GRPO) and ReMax, to the forecasting setting. Our adaptations remove per-question variance scaling in GRPO, apply baseline-subtracted advantages in ReMax, hydrate training with 100k temporally consistent synthetic questions, and introduce lightweight guard-rails that penalise gibberish, non-English responses and missing rationales, enabling a single stable pass over 110k events. Scaling ReMax to 110k questions and ensembling seven predictions yields a 14B model that matches frontier baseline o1 on accuracy on our holdout set (Brier = 0.193, p = 0.23) while beating it in calibration (ECE = 0.042, p < 0.001). A simple trading rule turns this calibration edge into \$127 of hypothetical profit versus \$92 for o1 (p = 0.037). This demonstrates that refined RLVR methods can convert small-scale LLMs into potentially economically valuable forecasting tools, with implications for scaling this to larger models.

[Arxiv](https://arxiv.org/abs/2505.17989)