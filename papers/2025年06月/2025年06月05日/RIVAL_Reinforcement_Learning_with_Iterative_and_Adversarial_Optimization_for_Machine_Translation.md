# RIVAL：通过迭代与对抗优化的强化学习实现机器翻译

发布时间：2025年06月05日

`LLM应用` `翻译技术`

> RIVAL: Reinforcement Learning with Iterative and Adversarial Optimization for Machine Translation

# 摘要

> 大型语言模型（LLMs）在多语言能力方面表现出色，结合人类反馈强化学习（RLHF）的翻译任务也展现出巨大潜力。然而，这一范式在处理口语化字幕翻译时表现不尽如人意。本研究深入探究这一现象，发现由于分布偏移，离线奖励模型（RM）逐渐与在线LLM产生分歧，最终导致不良的训练结果。为此，我们提出RIVAL框架，通过将RM与LLM之间的对抗训练过程建模为极小极大博弈，迭代更新两个模型。其中，RM被训练以区分优质与劣质翻译（定性偏好奖励），而LLM则被训练以提升其翻译质量以缩小这一差距。为稳定训练并提升泛化能力，我们还将定量偏好奖励（如BLEU）纳入RM，实现了与人工评估相契合的无参考质量建模。通过大量实验，我们证明了所提出的对抗训练框架显著优于现有翻译基线。

> Large language models (LLMs) possess strong multilingual capabilities, and combining Reinforcement Learning from Human Feedback (RLHF) with translation tasks has shown great potential. However, we observe that this paradigm performs unexpectedly poorly when applied to colloquial subtitle translation tasks. In this work, we investigate this issue and find that the offline reward model (RM) gradually diverges from the online LLM due to distributional shift, ultimately leading to undesirable training outcomes. To address this, we propose RIVAL, an adversarial training framework that formulates the process as a min-max game between the RM and the LLM. RIVAL iteratively updates the both models, with the RM trained to distinguish strong from weak translations (qualitative preference reward), and the LLM trained to enhance its translation for closing this gap. To stabilize training and improve generalizability, we also incorporate quantitative preference reward (e.g., BLEU) into the RM, enabling reference-free quality modeling aligned with human evaluation. Through extensive experiments, we demonstrate that the proposed adversarial training framework significantly improves upon translation baselines.

[Arxiv](https://arxiv.org/abs/2506.05070)