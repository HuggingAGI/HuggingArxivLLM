# Skywork UniPic 2.0：基于在线强化学习构建Kontext模型，打造统一多模态模型

发布时间：2025年09月04日

`其他` `媒体与娱乐`

> Skywork UniPic 2.0: Building Kontext Model with Online RL for Unified Multimodal Model

# 摘要

> 多模态模型的最新进展已在统一图像生成与编辑领域展现出令人瞩目的性能。然而，许多主流开源模型往往优先扩大参数规模而非优化训练策略，导致效率与性能受限。为此，我们提出UniPic2-SD3.5M-Kontext：一款基于SD3.5-Medium的20亿参数DiT模型，它不仅实现了最先进的图像生成与编辑能力，还能无缝扩展为统一多模态框架。我们的方法首先对SD3.5-Medium进行架构调整，并在高质量数据上开展大规模预训练，使其具备文本到图像的联合生成与编辑能力。为提升指令遵循度与编辑一致性，我们提出新颖的渐进式双任务强化策略（PDTR），通过分阶段训练有效强化双任务能力。实证结果表明，不同任务的强化阶段相互增益，且无负干扰。经过预训练与强化策略优化后，UniPic2-SD3.5M-Kontext的图像生成与编辑能力显著优于生成参数规模大得多的模型，包括BAGEL（70亿）和Flux-Kontext（120亿）。此外，基于MetaQuery框架，我们通过连接器将UniPic2-SD3.5M-Kontext与Qwen2.5-VL-7B相连并开展联合训练，构建出统一多模态模型UniPic2-Metaquery。该模型整合理解、生成与编辑能力，依托简洁可扩展的训练范式，在各类任务中均实现顶尖性能。这充分验证了我们所提训练范式的有效性与通用性，我们将其正式命名为Skywork UniPic 2.0。

> Recent advances in multimodal models have demonstrated impressive capabilities in unified image generation and editing. However, many prominent open-source models prioritize scaling model parameters over optimizing training strategies, limiting their efficiency and performance. In this work, we present UniPic2-SD3.5M-Kontext, a 2B-parameter DiT model based on SD3.5-Medium, which achieves state-of-the-art image generation and editing while extending seamlessly into a unified multimodal framework. Our approach begins with architectural modifications to SD3.5-Medium and large-scale pre-training on high-quality data, enabling joint text-to-image generation and editing capabilities. To enhance instruction following and editing consistency, we propose a novel Progressive Dual-Task Reinforcement strategy (PDTR), which effectively strengthens both tasks in a staged manner. We empirically validate that the reinforcement phases for different tasks are mutually beneficial and do not induce negative interference. After pre-training and reinforcement strategies, UniPic2-SD3.5M-Kontext demonstrates stronger image generation and editing capabilities than models with significantly larger generation parameters-including BAGEL (7B) and Flux-Kontext (12B). Furthermore, following the MetaQuery, we connect the UniPic2-SD3.5M-Kontext and Qwen2.5-VL-7B via a connector and perform joint training to launch a unified multimodal model UniPic2-Metaquery. UniPic2-Metaquery integrates understanding, generation, and editing, achieving top-tier performance across diverse tasks with a simple and scalable training paradigm. This consistently validates the effectiveness and generalizability of our proposed training paradigm, which we formalize as Skywork UniPic 2.0.

[Arxiv](https://arxiv.org/abs/2509.04548)