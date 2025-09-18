# AdaThinkDrive：基于强化学习的自动驾驶自适应思维

发布时间：2025年09月17日

`Agent` `交通运输`

> AdaThinkDrive: Adaptive Thinking via Reinforcement Learning for Autonomous Driving

# 摘要

> 尽管思维链（CoT）等推理技术已在视觉语言动作（VLA）模型中广泛应用，并在端到端自动驾驶领域展现出良好潜力，但近期研究在整合CoT时却常在简单场景中“画蛇添足”——不仅未提升决策质量，反而增加了不必要的计算负担。为此，我们提出了AdaThinkDrive——一种受“快慢思维”启发、具备双模式推理机制的新型VLA框架。

该框架首先在大规模自动驾驶（AD）场景上预训练，通过问答（QA）与轨迹数据集学习世界知识和驾驶常识。在监督微调（SFT）阶段，我们构建了双模式数据集——“快速回答（无CoT）”与“慢速思考（有CoT）”，让模型学会辨别何时需要启动推理。此外，我们还设计了自适应思考奖励策略，并结合组相对策略优化（GRPO），通过对比不同推理模式的轨迹质量，激励模型“按需”使用CoT。

在Navsim基准测试中，AdaThinkDrive的PDMS指标达到90.3，较最佳纯视觉基线提升1.7分。消融实验进一步显示，该模型在PDMS指标上比“从不推理”和“始终推理”基线分别提升2.0和1.4分；同时，与“始终推理”基线相比，推理时间缩短14%，充分证明了自适应推理在精准性与效率间的平衡能力。

> While reasoning technology like Chain of Thought (CoT) has been widely adopted in Vision Language Action (VLA) models, it demonstrates promising capabilities in end to end autonomous driving. However, recent efforts to integrate CoT reasoning often fall short in simple scenarios, introducing unnecessary computational overhead without improving decision quality. To address this, we propose AdaThinkDrive, a novel VLA framework with a dual mode reasoning mechanism inspired by fast and slow thinking. First, our framework is pretrained on large scale autonomous driving (AD) scenarios using both question answering (QA) and trajectory datasets to acquire world knowledge and driving commonsense. During supervised fine tuning (SFT), we introduce a two mode dataset, fast answering (w/o CoT) and slow thinking (with CoT), enabling the model to distinguish between scenarios that require reasoning. Furthermore, an Adaptive Think Reward strategy is proposed in conjunction with the Group Relative Policy Optimization (GRPO), which rewards the model for selectively applying CoT by comparing trajectory quality across different reasoning modes. Extensive experiments on the Navsim benchmark show that AdaThinkDrive achieves a PDMS of 90.3, surpassing the best vision only baseline by 1.7 points. Moreover, ablations show that AdaThinkDrive surpasses both the never Think and always Think baselines, improving PDMS by 2.0 and 1.4, respectively. It also reduces inference time by 14% compared to the always Think baseline, demonstrating its ability to balance accuracy and efficiency through adaptive reasoning.

[Arxiv](https://arxiv.org/abs/2509.13769)