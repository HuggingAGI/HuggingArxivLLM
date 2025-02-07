# 融合 LMM 规划器与 3D 技能策略，实现通用化操作

发布时间：2025年01月30日

`Agent

理由：这篇论文主要讨论的是如何将大型多模态模型（LMMs）与3D特征场结合，形成一个框架（LMM-3DP），用于机器人的高层规划和低层控制。这涉及到智能体（Agent）的设计和实现，特别是如何利用LMMs的推理能力来增强机器人的自主决策和执行能力。因此，这篇论文更适合归类为Agent。` `机器人` `3D视觉`

> Integrating LMM Planners and 3D Skill Policies for Generalizable Manipulation

# 摘要

> # 摘要
近期，大型多模态模型（LMMs）在视觉推理能力上的突破，以及3D特征场的语义增强，为机器人能力的拓展带来了新的可能。这些进展为连接LMMs的高层推理与3D特征场的低层控制策略提供了巨大潜力。本文提出LMM-3DP框架，旨在整合LMM规划器与3D技能策略。该框架从三个核心维度展开：高层规划、低层控制及两者的高效整合。在高层规划中，LMM-3DP具备动态场景理解、自我反馈的批评机制、历史策略记忆及失败重试能力。低层控制则依赖于语义感知的3D特征场，确保操作的精准性。通过将高层策略的语言嵌入与3D特征场在3D变换器中协同处理，LMM-3DP实现了高层与低层控制的无缝对接。我们在真实厨房环境中对多种技能和长期任务进行了全面测试。结果表明，相较于基于LLM的基线，LMM-3DP在低层控制成功率上提升了1.45倍，高层规划准确性提高了约1.5倍。更多演示视频及框架概述，请访问https://lmm-3dp-release.github.io。

> The recent advancements in visual reasoning capabilities of large multimodal models (LMMs) and the semantic enrichment of 3D feature fields have expanded the horizons of robotic capabilities. These developments hold significant potential for bridging the gap between high-level reasoning from LMMs and low-level control policies utilizing 3D feature fields. In this work, we introduce LMM-3DP, a framework that can integrate LMM planners and 3D skill Policies. Our approach consists of three key perspectives: high-level planning, low-level control, and effective integration. For high-level planning, LMM-3DP supports dynamic scene understanding for environment disturbances, a critic agent with self-feedback, history policy memorization, and reattempts after failures. For low-level control, LMM-3DP utilizes a semantic-aware 3D feature field for accurate manipulation. In aligning high-level and low-level control for robot actions, language embeddings representing the high-level policy are jointly attended with the 3D feature field in the 3D transformer for seamless integration. We extensively evaluate our approach across multiple skills and long-horizon tasks in a real-world kitchen environment. Our results show a significant 1.45x success rate increase in low-level control and an approximate 1.5x improvement in high-level planning accuracy compared to LLM-based baselines. Demo videos and an overview of LMM-3DP are available at https://lmm-3dp-release.github.io.

[Arxiv](https://arxiv.org/abs/2501.18733)