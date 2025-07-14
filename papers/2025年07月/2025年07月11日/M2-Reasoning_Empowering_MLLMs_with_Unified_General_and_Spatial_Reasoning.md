# M2-Reasoning: 为多模态大语言模型注入统一的通用与空间推理能力

发布时间：2025年07月11日

`LLM理论

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）的改进和训练方法，特别是通过数据管道和动态多任务训练策略来提升推理能力。这属于模型理论和训练方法的范畴。` `机器人` `自动驾驶`

> M2-Reasoning: Empowering MLLMs with Unified General and Spatial Reasoning

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在可验证奖励的强化学习（RLVR）推动下取得了显著进展，推理能力得到了显著提升。然而，这些模型在动态空间交互方面仍存在关键挑战，这对实际应用至关重要。为解决这一问题，我们推出M2-Reasoning-7B，一款在通用推理和空间推理方面均表现卓越的模型。我们的方法融合了两大创新：(1) 一条全新的数据管道，生成了29.42万高质量数据样本（16.8万用于冷启动微调，12.62万用于RLVR），这些样本具有逻辑连贯的推理轨迹，并经过全面评估；(2) 一种动态多任务训练策略，采用逐步优化方法来缓解数据冲突，并为特定任务提供奖励，以传递定制化的激励信号。通过结合精选数据和先进训练策略，M2-Reasoning-7B在8个基准测试中树立了新的标杆，展现了其在通用推理和空间推理领域的卓越性能。

> Recent advancements in Multimodal Large Language Models (MLLMs), particularly through Reinforcement Learning with Verifiable Rewards (RLVR), have significantly enhanced their reasoning abilities. However, a critical gap persists: these models struggle with dynamic spatial interactions, a capability essential for real-world applications. To bridge this gap, we introduce M2-Reasoning-7B, a model designed to excel in both general and spatial reasoning. Our approach integrates two key innovations: (1) a novel data pipeline that generates 294.2K high-quality data samples (168K for cold-start fine-tuning and 126.2K for RLVR), which feature logically coherent reasoning trajectories and have undergone comprehensive assessment; and (2) a dynamic multi-task training strategy with step-wise optimization to mitigate conflicts between data, and task-specific rewards for delivering tailored incentive signals. This combination of curated data and advanced training allows M2-Reasoning-7B to set a new state-of-the-art (SOTA) across 8 benchmarks, showcasing superior performance in both general and spatial reasoning domains.

[Arxiv](https://arxiv.org/abs/2507.08306)