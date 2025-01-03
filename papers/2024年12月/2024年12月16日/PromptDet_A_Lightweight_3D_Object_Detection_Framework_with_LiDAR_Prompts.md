# PromptDet: 基于 LiDAR 提示的轻量级 3D 物体检测框架

发布时间：2024年12月16日

`其他

理由：这篇论文主要讨论的是多摄像头3D目标检测技术，特别是如何通过多模态融合和知识蒸馏方法来解决深度估计不准确的问题。虽然论文中提到了“提示学习”和“轻量级多模态融合方法”，但这些内容主要与计算机视觉和3D目标检测相关，而不是直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等领域。因此，这篇论文更适合归类为“其他”。` `自动驾驶` `计算机视觉`

> PromptDet: A Lightweight 3D Object Detection Framework with LiDAR Prompts

# 摘要

> # 多摄像头3D目标检测
多摄像头3D目标检测利用多个摄像头在3D空间中检测和定位物体，因其成本效益优势备受关注。然而，相机在测距上的天然缺陷导致深度估计不准确，这一问题一直困扰着现有方法。近期，为解决这一难题，研究者提出了多模态融合和知识蒸馏方法，但这些方法训练耗时且内存开销大。为此，我们受2D基础模型中提示学习的启发，提出了轻量高效的3D目标检测框架PromptDet。该框架包含两个核心模块：基于摄像头的通用检测模块（如BEVDet和BEVDepth）和LiDAR辅助提示器。LiDAR辅助提示器利用LiDAR点作为补充信号，仅需少量额外可训练参数。得益于类似提示的设计，PromptDet不仅可作为轻量级多模态融合方法，还可在推理阶段作为纯摄像头3D目标检测方案。在nuScenes数据集上的大量实验表明，PromptDet作为多模态检测器，在仅增加不到2%参数的情况下，相比纯摄像头基线，mAP和NDS分别提升了最多22.8%和21.1%。即使不使用LiDAR点，PromptDet仍能提升最多2.4%的mAP和4.0%的NDS，且几乎不影响摄像头检测的推理速度。

> Multi-camera 3D object detection aims to detect and localize objects in 3D space using multiple cameras, which has attracted more attention due to its cost-effectiveness trade-off. However, these methods often struggle with the lack of accurate depth estimation caused by the natural weakness of the camera in ranging. Recently, multi-modal fusion and knowledge distillation methods for 3D object detection have been proposed to solve this problem, which are time-consuming during the training phase and not friendly to memory cost. In light of this, we propose PromptDet, a lightweight yet effective 3D object detection framework motivated by the success of prompt learning in 2D foundation model. Our proposed framework, PromptDet, comprises two integral components: a general camera-based detection module, exemplified by models like BEVDet and BEVDepth, and a LiDAR-assisted prompter. The LiDAR-assisted prompter leverages the LiDAR points as a complementary signal, enriched with a minimal set of additional trainable parameters. Notably, our framework is flexible due to our prompt-like design, which can not only be used as a lightweight multi-modal fusion method but also as a camera-only method for 3D object detection during the inference phase. Extensive experiments on nuScenes validate the effectiveness of the proposed PromptDet. As a multi-modal detector, PromptDet improves the mAP and NDS by at most 22.8\% and 21.1\% with fewer than 2\% extra parameters compared with the camera-only baseline. Without LiDAR points, PromptDet still achieves an improvement of at most 2.4\% mAP and 4.0\% NDS with almost no impact on camera detection inference time.

[Arxiv](https://arxiv.org/abs/2412.12460)