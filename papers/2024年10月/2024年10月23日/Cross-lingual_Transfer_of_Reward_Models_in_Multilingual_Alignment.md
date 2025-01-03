# 多语言对齐中的跨语言奖励模型迁移

发布时间：2024年10月23日

`LLM应用

理由：这篇论文探讨了基于人类反馈的强化学习（RLHF）在多语言环境中的应用，特别是奖励模型（RMs）在多语言间的迁移效果。研究涉及如何利用英语为主的RMs提升多语言对齐和指令跟随能力，这属于大型语言模型（LLM）在实际应用中的优化和扩展，因此应归类为LLM应用。` `多语言学习`

> Cross-lingual Transfer of Reward Models in Multilingual Alignment

# 摘要

> # 摘要
基于人类反馈的强化学习（RLHF）显著受益于精确的奖励模型（RMs）。然而，当前奖励建模的研究多集中于英语，限制了RLHF在多语言对齐中的应用。本研究探讨了以英语为主的RMs在多语言间的迁移效果。实验显示，英语RMs在Multilingual RewardBench中平均提升3~4%，优于目标语言RMs。我们还通过表示变化分析了RMs的跨语言迁移，并通过多语言对齐展示了这种迁移如何提升多语言指令跟随能力。此外，我们对现成RMs进行了深入分析，并公开了代码、模型和数据。

> Reinforcement learning with human feedback (RLHF) is shown to largely benefit from precise reward models (RMs). However, recent studies in reward modeling schemes are skewed towards English, limiting the applicability of RLHF in multilingual alignments. In this work, we investigate the cross-lingual transfer of RMs trained in diverse languages, primarily from English. Our experimental results demonstrate the strong cross-lingual transfer of English RMs, exceeding target language RMs by 3~4% average increase in Multilingual RewardBench. Furthermore, we analyze the cross-lingual transfer of RMs through the representation shifts. Finally, we perform multilingual alignment to exemplify how cross-lingual transfer in RM propagates to enhanced multilingual instruction-following capability, along with extensive analyses on off-the-shelf RMs. We release the code, model, and data.

[Arxiv](https://arxiv.org/abs/2410.18027)