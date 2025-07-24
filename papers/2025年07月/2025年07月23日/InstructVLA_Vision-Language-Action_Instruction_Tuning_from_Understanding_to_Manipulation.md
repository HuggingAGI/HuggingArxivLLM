# 指导VLA：从理解到操作的视觉-语言-动作指令微调

发布时间：2025年07月23日

`Agent` `机器人学` `人工智能`

> InstructVLA: Vision-Language-Action Instruction Tuning from Understanding to Manipulation

# 摘要

> 要在现实世界中有效运作，机器人需要将多模态推理与精准动作生成相结合。然而，现有的视觉-语言-动作（VLA）模型往往顾此失彼，能力局限于特定任务数据，并且容易遗忘预训练的视觉-语言能力。为了解决这一问题，我们提出了InstructVLA——一个端到端的VLA模型，它不仅保留了大型视觉-语言模型（VLM）的灵活推理能力，还实现了领先的操控性能。

InstructVLA引入了一种全新的训练范式——视觉-语言-动作指令微调（VLA-IT）。通过多模态训练和专家混合适应，它同时优化了标准VLM语料库和一个精心整理的65万样本VLA-IT数据集上的文本推理和动作生成。在同类任务中，InstructVLA的表现比SpatialVLA提升了30.5%。

为了评估其泛化能力，我们推出了SimplerEnv-Instruct——一个包含80项任务的基准测试，要求闭环控制和对高级指令的理解。在这些任务中，InstructVLA的表现比微调后的OpenVLA高出92%，比由GPT-4辅助的动作专家高出29%。此外，InstructVLA在多模态任务中超越了基线VLM，并通过推理时间扩展，利用文本推理在模拟和现实环境中提升操控性能。这些结果展示了InstructVLA在实现直观且可控的人机交互与高效策略学习方面的巨大潜力。

> To operate effectively in the real world, robots must integrate multimodal reasoning with precise action generation. However, existing vision-language-action (VLA) models often sacrifice one for the other, narrow their abilities to task-specific manipulation data, and suffer catastrophic forgetting of pre-trained vision-language capabilities. To bridge this gap, we introduce InstructVLA, an end-to-end VLA model that preserves the flexible reasoning of large vision-language models (VLMs) while delivering leading manipulation performance. InstructVLA introduces a novel training paradigm, Vision-Language-Action Instruction Tuning (VLA-IT), which employs multimodal training with mixture-of-experts adaptation to jointly optimize textual reasoning and action generation on both standard VLM corpora and a curated 650K-sample VLA-IT dataset. On in-domain SimplerEnv tasks, InstructVLA achieves 30.5% improvement over SpatialVLA. To evaluate generalization, we introduce SimplerEnv-Instruct, an 80-task benchmark requiring closed-loop control and high-level instruction understanding, where it outperforms a fine-tuned OpenVLA by 92% and an action expert aided by GPT-4o by 29%. Additionally, InstructVLA surpasses baseline VLMs on multimodal tasks and exhibits inference-time scaling by leveraging textual reasoning to boost manipulation performance in both simulated and real-world settings. These results demonstrate InstructVLA's potential for bridging intuitive and steerable human-robot interaction with efficient policy learning.

[Arxiv](https://arxiv.org/abs/2507.17520)