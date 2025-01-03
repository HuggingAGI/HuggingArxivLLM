# 快速且稳健的视觉运动黎曼流匹配策略

发布时间：2024年12月14日

`其他

理由：这篇论文主要讨论的是基于扩散的视觉运动策略在机器人任务中的应用，特别是提出了黎曼流匹配策略（RFMP）和稳定RFMP（SRFMP）。虽然涉及到机器人和视觉数据处理，但主要内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题。因此，将其分类为“其他”更为合适。` `机器人` `运动控制`

> Fast and Robust Visuomotor Riemannian Flow Matching Policy

# 摘要

> 基于扩散的视觉运动策略在结合视觉数据与高维、多模态动作分布方面表现出色，能够高效学习复杂的机器人任务。然而，扩散模型常因昂贵的去噪过程或复杂的顺序训练而推理缓慢。本文提出黎曼流匹配策略（RFMP），继承了流匹配（FM）易于训练和快速推理的优点，并自然融入了现实机器人应用中的几何约束，因为机器人状态位于黎曼流形上。为进一步增强鲁棒性，我们提出了稳定RFMP（SRFMP），利用LaSalle不变性原理，使FM动态对目标黎曼分布具有稳定性。在八个模拟和现实任务中的评估表明，RFMP在欧几里得和黎曼空间上高效学习并合成了复杂的感知运动策略，优于扩散策略，同时与一致性策略保持竞争力。

> Diffusion-based visuomotor policies excel at learning complex robotic tasks by effectively combining visual data with high-dimensional, multi-modal action distributions. However, diffusion models often suffer from slow inference due to costly denoising processes or require complex sequential training arising from recent distilling approaches. This paper introduces Riemannian Flow Matching Policy (RFMP), a model that inherits the easy training and fast inference capabilities of flow matching (FM). Moreover, RFMP inherently incorporates geometric constraints commonly found in realistic robotic applications, as the robot state resides on a Riemannian manifold. To enhance the robustness of RFMP, we propose Stable RFMP (SRFMP), which leverages LaSalle's invariance principle to equip the dynamics of FM with stability to the support of a target Riemannian distribution. Rigorous evaluation on eight simulated and real-world tasks show that RFMP successfully learns and synthesizes complex sensorimotor policies on Euclidean and Riemannian spaces with efficient training and inference phases, outperforming Diffusion Policies while remaining competitive with Consistency Policies.

[Arxiv](https://arxiv.org/abs/2412.10855)