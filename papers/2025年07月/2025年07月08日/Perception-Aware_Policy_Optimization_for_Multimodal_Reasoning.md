# 感知增强策略优化用于多模态推理

发布时间：2025年07月08日

`LLM应用` `计算机视觉` `多模态推理`

> Perception-Aware Policy Optimization for Multimodal Reasoning

# 摘要

> 可验证奖励的强化学习（RLVR）是赋予大型语言模型（LLMs）强大多步推理能力的高效策略。然而，其设计与优化仍局限于纯文本领域，在多模态推理任务中表现欠佳。我们发现，当前多模态推理中的主要误差源在于对视觉输入的感知。为解决这一瓶颈，我们提出感知增强策略优化（PAPO），这是对GRPO的简单而有效的扩展，鼓励模型在学习推理的同时学习感知，完全基于内部监督信号。值得注意的是，PAPO无需额外的数据整理、外部奖励模型或专有模型。具体而言，我们在GRPO目标中引入隐式感知损失（以KL散度项形式呈现），尽管其简单，却在多模态基准测试中带来显著提升（4.4%）。在视觉依赖度高的任务中，提升尤为明显，接近8.0%。我们还观察到感知错误大幅减少（30.5%），表明PAPO提升了感知能力。我们对PAPO进行了全面分析，识别出独特的损失挖掘问题，并通过双重熵损失进行严格分析与缓解。总体而言，我们的工作将感知增强监督更深度地融入RLVR学习目标，并为鼓励视觉推理的新RL框架奠定了基础。项目页面：https://mikewangwzhl.github.io/PAPO。


> Reinforcement Learning with Verifiable Rewards (RLVR) has proven to be a highly effective strategy for endowing Large Language Models (LLMs) with robust multi-step reasoning abilities. However, its design and optimizations remain tailored to purely textual domains, resulting in suboptimal performance when applied to multimodal reasoning tasks. In particular, we observe that a major source of error in current multimodal reasoning lies in the perception of visual inputs. To address this bottleneck, we propose Perception-Aware Policy Optimization (PAPO), a simple yet effective extension of GRPO that encourages the model to learn to perceive while learning to reason, entirely from internal supervision signals. Notably, PAPO does not rely on additional data curation, external reward models, or proprietary models. Specifically, we introduce the Implicit Perception Loss in the form of a KL divergence term to the GRPO objective, which, despite its simplicity, yields significant overall improvements (4.4%) on diverse multimodal benchmarks. The improvements are more pronounced, approaching 8.0%, on tasks with high vision dependency. We also observe a substantial reduction (30.5%) in perception errors, indicating improved perceptual capabilities with PAPO. We conduct comprehensive analysis of PAPO and identify a unique loss hacking issue, which we rigorously analyze and mitigate through a Double Entropy Loss. Overall, our work introduces a deeper integration of perception-aware supervision into RLVR learning objectives and lays the groundwork for a new RL framework that encourages visually grounded reasoning. Project page: https://mikewangwzhl.github.io/PAPO.

[Arxiv](https://arxiv.org/abs/2507.06448)