# DreamNav：基于轨迹的想象框架——零样本视觉-语言导航新方案

发布时间：2025年09月14日

`Agent` `工业与制造`

> DreamNav: A Trajectory-Based Imaginative Framework for Zero-Shot Vision-and-Language Navigation

# 摘要

> 连续环境中的视觉-语言导航（VLN-CE）作为具身机器人的核心能力，能够将语言指令与现实世界的感知和控制相连接。近年来，大规模预训练基础模型被用作感知、推理和动作的共享先验，实现了无需特定任务训练的零样本VLN。然而，现有的零样本VLN方法依赖高昂的感知成本和被动的场景理解，导致控制被简化为点级选择，进而面临部署成本高、动作语义错位及规划短视等问题。为解决这些挑战，我们提出DreamNav，重点关注以下三个方面：（1）为降低感知成本，第一视角校正器通过对齐视角来稳定第一人称感知；（2）摒弃点级动作，轨迹预测器采用全局轨迹级规划，以更好地匹配指令语义；（3）为实现前瞻式长时程规划，我们设计想象预测器，赋予智能体主动思考能力。在VLN-CE及真实世界测试中，DreamNav刷新了零样本VLN的最先进水平（SOTA），在SR和SPL指标上，相较于具备额外信息的最强第一人称基线，分别提升了7.49%和18.15%。据我们所知，这是首个仅依赖第一人称输入就实现轨迹级规划与主动想象统一的零样本VLN方法。

> Vision-and-Language Navigation in Continuous Environments (VLN-CE), which links language instructions to perception and control in the real world, is a core capability of embodied robots. Recently, large-scale pretrained foundation models have been leveraged as shared priors for perception, reasoning, and action, enabling zero-shot VLN without task-specific training. However, existing zero-shot VLN methods depend on costly perception and passive scene understanding, collapsing control to point-level choices. As a result, they are expensive to deploy, misaligned in action semantics, and short-sighted in planning. To address these issues, we present DreamNav that focuses on the following three aspects: (1) for reducing sensory cost, our EgoView Corrector aligns viewpoints and stabilizes egocentric perception; (2) instead of point-level actions, our Trajectory Predictor favors global trajectory-level planning to better align with instruction semantics; and (3) to enable anticipatory and long-horizon planning, we propose an Imagination Predictor to endow the agent with proactive thinking capability. On VLN-CE and real-world tests, DreamNav sets a new zero-shot state-of-the-art (SOTA), outperforming the strongest egocentric baseline with extra information by up to 7.49\% and 18.15\% in terms of SR and SPL metrics. To our knowledge, this is the first zero-shot VLN method to unify trajectory-level planning and active imagination while using only egocentric inputs.

[Arxiv](https://arxiv.org/abs/2509.11197)