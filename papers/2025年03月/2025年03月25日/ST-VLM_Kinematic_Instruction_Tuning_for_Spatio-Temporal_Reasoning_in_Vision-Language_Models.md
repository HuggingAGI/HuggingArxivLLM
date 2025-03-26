# ST-VLM：视觉-语言模型中基于运动学指令的时空推理微调方法

发布时间：2025年03月25日

`LLM应用` `自动驾驶` `体育分析`

> ST-VLM: Kinematic Instruction Tuning for Spatio-Temporal Reasoning in Vision-Language Models

# 摘要

> 时空推理在理解现实世界环境方面至关重要，尤其在自动驾驶和体育分析等领域。尽管近期研究通过大规模数据显著提升了视觉语言模型（VLMs）的空间推理能力，但这些模型仍难以有效分析运动物体的运动轨迹、速度等运动学要素。为解决这一问题，我们构建了STKit和STKit-Bench——一个包含运动指令微调的时空推理数据集与基准测试。它们由带有三维标注的真实世界视频组成，详细记录了物体的运动动力学特征，包括运动距离、速度、运动方向、物体间距离比较以及相对运动方向。为了进一步扩展这类数据构建至无三维标签的视频，我们提出了一种自动管道，利用真实尺度的4D重建生成伪标签。基于我们的运动指令微调数据，我们推出了增强版的视觉语言模型——ST-VLM。在STKit-Bench基准测试中，ST-VLM表现出色。此外，我们验证了ST-VLM在不同领域和任务中的强大适应能力，其在其他时空推理基准测试（如ActivityNet、TVQA+）中超越了现有基线模型。最后，通过将学习到的时空推理能力与现有模型能力相结合，ST-VLM实现了复杂多步骤推理。项目页面：https://ikodoh.github.io/ST-VLM。

> Spatio-temporal reasoning is essential in understanding real-world environments in various fields, eg, autonomous driving and sports analytics. Recent advances have improved the spatial reasoning ability of Vision-Language Models (VLMs) by introducing large-scale data, but these models still struggle to analyze kinematic elements like traveled distance and speed of moving objects. To bridge this gap, we construct a spatio-temporal reasoning dataset and benchmark involving kinematic instruction tuning, referred to as STKit and STKit-Bench. They consist of real-world videos with 3D annotations, detailing object motion dynamics: traveled distance, speed, movement direction, inter-object distance comparisons, and relative movement direction. To further scale such data construction to videos without 3D labels, we propose an automatic pipeline to generate pseudo-labels using 4D reconstruction in real-world scale. With our kinematic instruction tuning data for spatio-temporal reasoning, we present ST-VLM, a VLM enhanced for spatio-temporal reasoning, which exhibits outstanding performance on STKit-Bench. Furthermore, we show that ST-VLM generalizes robustly across diverse domains and tasks, outperforming baselines on other spatio-temporal benchmarks (eg, ActivityNet, TVQA+). Finally, by integrating learned spatio-temporal reasoning with existing abilities, ST-VLM enables complex multi-step reasoning. Project page: https://ikodoh.github.io/ST-VLM.

[Arxiv](https://arxiv.org/abs/2503.19355)