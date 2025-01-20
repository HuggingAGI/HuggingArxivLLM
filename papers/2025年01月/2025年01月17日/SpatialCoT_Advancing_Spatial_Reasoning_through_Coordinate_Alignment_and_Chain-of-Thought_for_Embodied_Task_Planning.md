# SpatialCoT: 利用坐标对齐与思维链提升空间推理能力，助力具身任务规划

发布时间：2025年01月17日

`Agent

理由：这篇论文主要讨论的是如何通过增强视觉语言模型（VLMs）的空间推理能力来提升具身AI在复杂任务中的表现。具体来说，论文提出了一种名为SpatialCoT的新方法，该方法通过空间坐标双向对齐和思维链空间接地来增强VLMs的空间推理能力。这些内容涉及到AI代理（Agent）在复杂环境中的任务执行和推理能力，因此将其分类为Agent。` `具身AI` `空间推理`

> SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning

# 摘要

> 空间推理是具身AI研究中的核心挑战。尽管通过补充空间数据和微调来提升空间推理能力的尝试屡见不鲜，但在处理复杂具身任务时，这些方法往往效果有限，主要因为它们过度依赖语言输出。虽然一些研究引入了基于点的动作空间来缓解这一问题，但在复杂环境中处理更精细任务时仍显不足。这一缺陷源于它们未能充分利用视觉语言模型（VLMs）固有的思维与推理能力。为此，我们提出了一种名为SpatialCoT的新方法，旨在增强VLMs的空间推理能力。该方法分为两个阶段：空间坐标双向对齐，将视觉语言输入与空间坐标精准匹配；以及思维链空间接地，利用语言模型的推理能力进行高级空间推理。我们在模拟和现实环境中对SpatialCoT进行了导航和操作任务的测试。实验结果显示，该方法在这两项任务中均显著优于现有最佳方案。

> Spatial reasoning is an essential problem in embodied AI research. Efforts to enhance spatial reasoning abilities through supplementary spatial data and fine-tuning have proven limited and ineffective when addressing complex embodied tasks, largely due to their dependence on language-based outputs. While some approaches have introduced a point-based action space to mitigate this issue, they fall short in managing more intricate tasks within complex environments. This deficiency arises from their failure to fully exploit the inherent thinking and reasoning capabilities that are fundamental strengths of Vision-Language Models (VLMs). To address these limitations, we propose a novel approach named SpatialCoT, specifically designed to bolster the spatial reasoning capabilities of VLMs. Our approach comprises two stages: spatial coordinate bi-directional alignment, which aligns vision-language inputs with spatial coordinates, and chain-of-thought spatial grounding, which harnesses the reasoning capabilities of language models for advanced spatial reasoning. We evaluate SpatialCoT on challenging navigation and manipulation tasks, both in simulation and real-world settings. Experimental results demonstrate that our method significantly outperforms previous state-of-the-art approaches in both tasks.

[Arxiv](https://arxiv.org/abs/2501.10074)