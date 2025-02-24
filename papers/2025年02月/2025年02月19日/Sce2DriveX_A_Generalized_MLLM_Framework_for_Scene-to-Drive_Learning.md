# Sce2DriveX：面向场景到驾驶学习的通用化MLLM框架。

发布时间：2025年02月19日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在自动驾驶中的应用，提出了一个框架并构建了相关数据集，属于LLM的实际应用领域。` `自动驾驶` `智能驾驶`

> Sce2DriveX: A Generalized MLLM Framework for Scene-to-Drive Learning

# 摘要

> 端到端自动驾驶作为具身智能的关键组成部分，直接将原始传感器输入转化为低级车辆控制。虽然多模态大型语言模型（MLLMs）在高级交通场景语义理解方面取得显著进展，但如何有效将其转化为低级控制指令并实现跨场景泛化仍是难题。为此，我们提出Sce2DriveX——一个模仿人类驾驶链式推理的MLLM框架。通过融合局部场景视频与全局BEV地图的多模态学习，Sce2DriveX深入理解长程时空关系与道路拓扑结构，显著提升了3D动态场景中的感知与推理能力，实现跨场景驾驶泛化。在此基础上，Sce2DriveX重构了人类驾驶中的隐式认知链，涵盖场景理解、元动作推理、行为分析、运动规划与控制，进一步缩小自动驾驶与人类思维的差距。为提升模型性能，我们打造了首个大规模面向3D空间理解与长轴任务推理的视觉问答（VQA）驾驶指令数据集。实验结果表明，Sce2DriveX在场景理解到端到端驾驶的全流程中均达到目前最优水平，并在CARLA Bench2Drive基准测试中展现出强大的跨场景泛化能力。

> End-to-end autonomous driving, which directly maps raw sensor inputs to low-level vehicle controls, is an important part of Embodied AI. Despite successes in applying Multimodal Large Language Models (MLLMs) for high-level traffic scene semantic understanding, it remains challenging to effectively translate these conceptual semantics understandings into low-level motion control commands and achieve generalization and consensus in cross-scene driving. We introduce Sce2DriveX, a human-like driving chain-of-thought (CoT) reasoning MLLM framework. Sce2DriveX utilizes multimodal joint learning from local scene videos and global BEV maps to deeply understand long-range spatiotemporal relationships and road topology, enhancing its comprehensive perception and reasoning capabilities in 3D dynamic/static scenes and achieving driving generalization across scenes. Building on this, it reconstructs the implicit cognitive chain inherent in human driving, covering scene understanding, meta-action reasoning, behavior interpretation analysis, motion planning and control, thereby further bridging the gap between autonomous driving and human thought processes. To elevate model performance, we have developed the first extensive Visual Question Answering (VQA) driving instruction dataset tailored for 3D spatial understanding and long-axis task reasoning. Extensive experiments demonstrate that Sce2DriveX achieves state-of-the-art performance from scene understanding to end-to-end driving, as well as robust generalization on the CARLA Bench2Drive benchmark.

[Arxiv](https://arxiv.org/abs/2502.14917)