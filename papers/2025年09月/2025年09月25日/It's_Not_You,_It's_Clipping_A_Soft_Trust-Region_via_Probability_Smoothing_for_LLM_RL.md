# 问题不在你，而在裁剪：基于概率平滑的LLM强化学习软信任域

发布时间：2025年09月25日

`其他` `（由于论文摘要翻译失败` `无法获取内容信息` `无法确定应用行业领域` `故无法生成标签。但根据题目要求需从给定列表选择` `此处可能存在信息缺失` `若必须选择` `最可能的默认领域为）基础理论`

> It's Not You, It's Clipping: A Soft Trust-Region via Probability Smoothing for LLM RL

# 摘要

> <翻译失败>

> Training large language models (LLMs) with reinforcement learning (RL) methods such as PPO and GRPO commonly relies on ratio clipping to stabilise updates. While effective at preventing instability, clipping discards information and introduces gradient discontinuities. We propose Probability Smoothing Policy Optimisation (PSPO), which smooths the current policy's probabilities toward the old (behaviour) policy before computing the importance ratio, analogous to label smoothing. Unlike clipping, PSPO preserves gradient signal, while interpolation toward the old policy creates a soft trust region that discourages large, destabilising updates, with formal guarantees.
  We instantiate PSPO within GRPO (GR-PSPO) and fine-tune Qwen2.5-0.5B and Qwen2.5-1.5B on GSM8K, evaluating on GSM8K test and the cross-dataset generalisation on SVAMP, ASDiv, and MATH-500. Relative to unclipped GRPO (single iteration; no data reuse, ratio always = 1), GR-PSPO achieves similar performance but improves the reasoning leading to clearer and more concise responses which are more logical. Compared to clipped GRPO, GR-PSPO substantially improves performance both the 0.5B and 1.5B models, with a boost of over 20% on GSM8K (39.7% vs. 17.6% for 0.5B, 59.4% vs. 37.8% for 1.5B).

[Arxiv](https://arxiv.org/abs/2509.21282)