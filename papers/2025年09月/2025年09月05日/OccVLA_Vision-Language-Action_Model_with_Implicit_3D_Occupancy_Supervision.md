# OccVLA：基于隐式三维占据监督的视觉-语言-动作模型

发布时间：2025年09月05日

`LLM应用` `交通运输`

> OccVLA: Vision-Language-Action Model with Implicit 3D Occupancy Supervision

# 摘要

> 多模态大型语言模型（MLLMs）虽已展现出强大的视觉语言推理能力，却仍缺乏稳健的3D空间理解——这对自动驾驶而言至关重要。其局限源于两大核心挑战：（1）难以在不依赖昂贵人工标注的前提下，构建既易于获取又有效的3D表示；（2）由于缺乏大规模3D视觉语言预训练，视觉语言模型（VLMs）会丢失细粒度空间细节。为应对这些挑战，我们提出了OccVLA——一种将3D占用表示融入统一多模态推理过程的新型框架。与依赖显式3D输入的传统方法不同，OccVLA将密集3D占用同时作为预测输出和监督信号，让模型能直接从2D视觉输入中学习细粒度空间结构。占用预测被视作隐式推理过程，推理时可直接跳过且不影响性能，因此不会增加额外计算开销。OccVLA在nuScenes基准的轨迹规划任务上刷新了最先进水平，并在3D视觉问答任务中展现出卓越性能，为自动驾驶提供了一套可扩展、可解释且纯视觉的解决方案。

> Multimodal large language models (MLLMs) have shown strong vision-language reasoning abilities but still lack robust 3D spatial understanding, which is critical for autonomous driving. This limitation stems from two key challenges: (1) the difficulty of constructing accessible yet effective 3D representations without expensive manual annotations, and (2) the loss of fine-grained spatial details in VLMs due to the absence of large-scale 3D vision-language pretraining. To address these challenges, we propose OccVLA, a novel framework that integrates 3D occupancy representations into a unified multimodal reasoning process. Unlike prior approaches that rely on explicit 3D inputs, OccVLA treats dense 3D occupancy as both a predictive output and a supervisory signal, enabling the model to learn fine-grained spatial structures directly from 2D visual inputs. The occupancy predictions are regarded as implicit reasoning processes and can be skipped during inference without performance degradation, thereby adding no extra computational overhead. OccVLA achieves state-of-the-art results on the nuScenes benchmark for trajectory planning and demonstrates superior performance on 3D visual question-answering tasks, offering a scalable, interpretable, and fully vision-based solution for autonomous driving.

[Arxiv](https://arxiv.org/abs/2509.05578)