# 多模态大型语言模型的模态不一致持续学习

发布时间：2024年12月17日

`LLM应用` `多模态` `持续学习`

> Modality-Inconsistent Continual Learning of Multimodal Large Language Models

# 摘要

> 在本文中，我们引入了模态不一致持续学习（MICL），这是针对多模态大型语言模型（MLLMs）的全新持续学习场景，涵盖了具有不一致模态（如图像、音频或视频）以及不同任务类型（如字幕生成或问答）的任务。和现有的仅视觉或模态递增设置不同，MICL 融合了模态与任务类型的转变，二者都会引发灾难性遗忘。为应对这些挑战，我们提出了 MoInCL，其运用伪目标生成模块来缓解先前所见模态中因任务类型转变导致的遗忘。同时，它还融入了基于指令的知识蒸馏，以便在引入新模态时，保留模型处理先前所学模态的能力。我们通过总共六个任务对 MICL 进行基准测试，并开展实验来验证所提出的 MoInCL 的有效性。实验结果彰显了 MoInCL 的优越性，相比具有代表性的和最先进的持续学习基线，有了显著的提升。

> In this paper, we introduce Modality-Inconsistent Continual Learning (MICL), a new continual learning scenario for Multimodal Large Language Models (MLLMs) that involves tasks with inconsistent modalities (image, audio, or video) and varying task types (captioning or question-answering). Unlike existing vision-only or modality-incremental settings, MICL combines modality and task type shifts, both of which drive catastrophic forgetting. To address these challenges, we propose MoInCL, which employs a Pseudo Targets Generation Module to mitigate forgetting caused by task type shifts in previously seen modalities. It also incorporates Instruction-based Knowledge Distillation to preserve the model's ability to handle previously learned modalities when new ones are introduced. We benchmark MICL using a total of six tasks and conduct experiments to validate the effectiveness of our proposed MoInCL. The experimental results highlight the superiority of MoInCL, showing significant improvements over representative and state-of-the-art continual learning baselines.

[Arxiv](https://arxiv.org/abs/2412.13050)