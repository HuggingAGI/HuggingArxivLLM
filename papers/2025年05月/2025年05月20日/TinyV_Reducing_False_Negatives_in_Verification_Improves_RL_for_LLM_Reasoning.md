# TinyV：通过减少验证中的假阴性，优化LLM推理强化学习

发布时间：2025年05月20日

`LLM应用` `模型验证`

> TinyV: Reducing False Negatives in Verification Improves RL for LLM Reasoning

# 摘要

> 强化学习（RL）已成为一种强大的工具，通过优化大型语言模型（LLMs）的策略来提升其推理能力，这一优化过程依赖于奖励信号。然而，RL的成功高度依赖于奖励的可靠性，而这些奖励是由验证器提供的。本文揭示并分析了一个普遍存在的问题——假阴性，即验证器错误地拒绝了正确的模型输出。通过对Big-Math-RL-Verified数据集的深入研究，我们发现超过38%的模型生成响应遭受了假阴性，其中验证器未能识别出正确答案。我们从实证和理论上展示了这些假阴性对RL训练造成了严重损害，剥夺了模型获取有益梯度信号的机会，并延缓了收敛速度。为了解决这一问题，我们提出了tinyV，这是一种轻量级的基于LLM的验证器，能够增强现有的基于规则的方法，动态识别潜在的假阴性，并恢复有效响应，从而生成更准确的奖励估计。在多个数学推理基准测试中，与基线相比，整合TinyV可将通过率提升高达10%，并加速收敛。我们的研究发现强调了解决验证器假阴性问题的关键重要性，并为改进基于RL的LLMs微调提供了一种实用方法。我们的代码可在https://github.com/uw-nsl/TinyV获取。

> Reinforcement Learning (RL) has become a powerful tool for enhancing the reasoning abilities of large language models (LLMs) by optimizing their policies with reward signals. Yet, RL's success relies on the reliability of rewards, which are provided by verifiers. In this paper, we expose and analyze a widespread problem--false negatives--where verifiers wrongly reject correct model outputs. Our in-depth study of the Big-Math-RL-Verified dataset reveals that over 38% of model-generated responses suffer from false negatives, where the verifier fails to recognize correct answers. We show, both empirically and theoretically, that these false negatives severely impair RL training by depriving the model of informative gradient signals and slowing convergence. To mitigate this, we propose tinyV, a lightweight LLM-based verifier that augments existing rule-based methods, which dynamically identifies potential false negatives and recovers valid responses to produce more accurate reward estimates. Across multiple math-reasoning benchmarks, integrating TinyV boosts pass rates by up to 10% and accelerates convergence relative to the baseline. Our findings highlight the critical importance of addressing verifier false negatives and offer a practical approach to improve RL-based fine-tuning of LLMs. Our code is available at https://github.com/uw-nsl/TinyV.

[Arxiv](https://arxiv.org/abs/2505.14625)