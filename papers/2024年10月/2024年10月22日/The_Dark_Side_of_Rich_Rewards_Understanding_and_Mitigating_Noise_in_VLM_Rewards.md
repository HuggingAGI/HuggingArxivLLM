# 丰厚奖励的阴暗面：解析与缓解VLM奖励中的噪声

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了视觉-语言模型（VLMs）在生成奖励信号以训练具身代理（embodied agents）时的表现问题，并提出了一个新的奖励函数BiMI来改善代理的学习效率。研究的核心是具身代理的训练和性能优化，因此应归类为Agent。` `机器人` `人工智能`

> The Dark Side of Rich Rewards: Understanding and Mitigating Noise in VLM Rewards

# 摘要

> 尽管视觉-语言模型（VLMs）常用于生成奖励信号来训练具身代理执行指令，但研究发现，与仅依赖内在（探索驱动）奖励的代理相比，VLM奖励引导的代理表现往往不尽如人意，这与近期研究的预期相悖。我们推测，假阳性奖励——即错误奖励了不期望的轨迹——比假阴性奖励更具破坏性。分析证实了这一推测，发现常用的余弦相似度度量易产生假阳性奖励估计。为此，我们提出了BiMI（{Bi}nary {M}utual {I}nformation），一种旨在减少噪声的新型奖励函数。BiMI显著提升了在多种复杂具身导航环境中的学习效率。研究结果深入剖析了不同类型奖励噪声对代理学习的影响，并强调了在训练具身代理时解决多模态奖励信号噪声的重要性。

> While Vision-Language Models (VLMs) are increasingly used to generate reward signals for training embodied agents to follow instructions, our research reveals that agents guided by VLM rewards often underperform compared to those employing only intrinsic (exploration-driven) rewards, contradicting expectations set by recent work. We hypothesize that false positive rewards -- instances where unintended trajectories are incorrectly rewarded -- are more detrimental than false negatives. Our analysis confirms this hypothesis, revealing that the widely used cosine similarity metric is prone to false positive reward estimates. To address this, we introduce BiMI ({Bi}nary {M}utual {I}nformation), a novel reward function designed to mitigate noise. BiMI significantly enhances learning efficiency across diverse and challenging embodied navigation environments. Our findings offer a nuanced understanding of how different types of reward noise impact agent learning and highlight the importance of addressing multimodal reward signal noise when training embodied agents

[Arxiv](https://arxiv.org/abs/2409.15922)