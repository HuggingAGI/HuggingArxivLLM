# RePO: 基于ReLU的偏好优化

发布时间：2025年03月10日

`LLM理论

摘要讨论了优化大型语言模型与人类偏好对齐的方法，提出了一种新的偏好优化算法RePO，属于LLM的理论和优化方法层面。因此，归类为LLM理论。` `人工智能`

> RePO: ReLU-based Preference Optimization

# 摘要

> 将大型语言模型 (LLMs) 与人类偏好对齐对于实际部署至关重要，然而现有方法如RLHF面临计算和稳定性挑战。虽然DPO通过单一超参数$β$建立了一个离线范式，但后续方法如SimPO通过引入双参数($β$, $γ$)重新增加了复杂性。我们提出了一种基于ReLU的偏好优化算法（RePO），通过两大创新消除了$β$：(1) 保留SimPO的无参考边界，但通过梯度分析去除了$β$；(2) 采用基于ReLU的最大边界损失，自然过滤掉平凡对。理论上，RePO被定义为SimPO的极限情况($β	o \infty$)，其中逻辑加权坍塌为二元阈值，形成0-1损失的凸包。在AlpacaEval 2和Arena-Hard上的实证结果表明，RePO在多个基础模型上优于DPO和SimPO，仅需调整一个超参数。

> Aligning large language models (LLMs) with human preferences is critical for real-world deployment, yet existing methods like RLHF face computational and stability challenges. While DPO establishes an offline paradigm with single hyperparameter $β$, subsequent methods like SimPO reintroduce complexity through dual parameters ($β$, $γ$). We propose {ReLU-based Preference Optimization (RePO)}, a streamlined algorithm that eliminates $β$ via two advances: (1) retaining SimPO's reference-free margins but removing $β$ through gradient analysis, and (2) adopting a ReLU-based max-margin loss that naturally filters trivial pairs. Theoretically, RePO is characterized as SimPO's limiting case ($β\to \infty$), where the logistic weighting collapses to binary thresholding, forming a convex envelope of the 0-1 loss. Empirical results on AlpacaEval 2 and Arena-Hard show that RePO outperforms DPO and SimPO across multiple base models, requiring only one hyperparameter to tune.

[Arxiv](https://arxiv.org/abs/2503.07426)