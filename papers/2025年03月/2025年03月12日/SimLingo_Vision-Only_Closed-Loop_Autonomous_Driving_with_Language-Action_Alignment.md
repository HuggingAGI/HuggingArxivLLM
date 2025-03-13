# SimLingo：基于语言-动作对齐的仅视觉闭环自动驾驶

发布时间：2025年03月12日

`LLM应用` `自动驾驶` `计算机视觉`

> SimLingo: Vision-Only Closed-Loop Autonomous Driving with Language-Action Alignment

# 摘要

> 将大型语言模型 (LLMs) 引入自动驾驶领域，旨在提升系统的泛化能力和可解释性，这一方向备受关注。然而，现有方法往往侧重于驾驶能力或视觉-语言理解，要在两者间取得平衡仍具挑战。目前，视觉-语言理解主要通过视觉问答实现，但这一方法仅在与自动驾驶的动作空间对齐时才有效。否则，模型的回答可能与其行为不符。为此，我们提出了一种全新的模型，能够同时处理闭环驾驶、视觉-语言理解以及语言-动作对齐三大任务。我们的模型 SimLingo 基于视觉语言模型 (VLM)，仅依赖摄像头，无需昂贵的 LiDAR 传感器。在广泛使用的 CARLA 模拟器上，SimLingo 在 Bench2Drive 基准测试中达到顶尖水平，并摘得 CARLA 2024 挑战赛桂冠。同时，它在多种语言相关任务中表现出色，驾驶性能依然优异。

> Integrating large language models (LLMs) into autonomous driving has attracted significant attention with the hope of improving generalization and explainability. However, existing methods often focus on either driving or vision-language understanding but achieving both high driving performance and extensive language understanding remains challenging. In addition, the dominant approach to tackle vision-language understanding is using visual question answering. However, for autonomous driving, this is only useful if it is aligned with the action space. Otherwise, the model's answers could be inconsistent with its behavior. Therefore, we propose a model that can handle three different tasks: (1) closed-loop driving, (2) vision-language understanding, and (3) language-action alignment. Our model SimLingo is based on a vision language model (VLM) and works using only camera, excluding expensive sensors like LiDAR. SimLingo obtains state-of-the-art performance on the widely used CARLA simulator on the Bench2Drive benchmark and is the winning entry at the CARLA challenge 2024. Additionally, we achieve strong results in a wide variety of language-related tasks while maintaining high driving performance.

[Arxiv](https://arxiv.org/abs/2503.09594)