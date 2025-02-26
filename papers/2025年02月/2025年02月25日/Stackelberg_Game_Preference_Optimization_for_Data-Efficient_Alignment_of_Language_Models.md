# 基于 Stackelberg 博弈的偏好优化实现语言模型的数据高效对齐

发布时间：2025年02月25日

`LLM理论` `人工智能` `博弈论`

> Stackelberg Game Preference Optimization for Data-Efficient Alignment of Language Models

# 摘要

> 将语言模型与人类偏好对齐对于实际应用至关重要，但现有方法往往需要大量高质量的人类标注。为了实现更高效的数据利用，我们提出了Stackelberg博弈偏好优化（SGPO），这是一个通过两玩家Stackelberg博弈建模对齐的框架。该框架中，策略（领导者）在【数学公式】-Wasserstein球内针对最坏情况的偏好分布（跟随者）进行优化，从而确保了对（自）标注噪声和分布偏移的鲁棒性。与直接偏好优化（DPO）不同，SGPO保证了【数学公式】有界遗憾，而DPO在分布不匹配时会遭受线性遗憾增长。我们通过Stackelberg自我标注偏好优化（SSAPO）算法实现了SGPO，该算法通过迭代自我标注偏好并对抗性地重新加权合成标注偏好。仅使用来自UltraFeedback数据集的2K种子偏好（即数据集人类标签的1/30），我们的方法在三轮SSAPO后，使用Mistral-7B实现了35.82%的GPT-4胜率，使用Llama3-8B-Instruct实现了40.12%的胜率。

> Aligning language models with human preferences is critical for real-world deployment, but existing methods often require large amounts of high-quality human annotations. Aiming at a data-efficient alignment method, we propose Stackelberg Game Preference Optimization (SGPO), a framework that models alignment as a two-player Stackelberg game, where a policy (leader) optimizes against a worst-case preference distribution (follower) within an $ε$-Wasserstein ball, ensuring robustness to (self-)annotation noise and distribution shifts. SGPO guarantees $O(ε)$-bounded regret, unlike Direct Preference Optimization (DPO), which suffers from linear regret growth in the distribution mismatch. We instantiate SGPO with the Stackelberg Self-Annotated Preference Optimization (SSAPO) algorithm, which iteratively self-annotates preferences and adversarially reweights synthetic annotated preferences. Using only 2K seed preferences, from the UltraFeedback dataset, i.e., 1/30 of human labels in the dataset, our method achieves 35.82% GPT-4 win-rate with Mistral-7B and 40.12% with Llama3-8B-Instruct within three rounds of SSAPO.

[Arxiv](https://arxiv.org/abs/2502.18099)