# # **实时音频驱动的FaceTime风格视频：基于自回归扩散模型的实现**

发布时间：2025年06月03日

`LLM应用` `计算机视觉` `图形学`

> TalkingMachines: Real-Time Audio-Driven FaceTime-Style Video via Autoregressive Diffusion Models

# 摘要

> 本文中，我们介绍了 TalkingMachines——一个高效框架，能够将预训练的视频生成模型转化为实时的、音频驱动的角色动画器。TalkingMachines 通过将音频大型语言模型 (LLM) 与我们的视频生成基础模型相结合，实现了自然的对话体验。我们的主要贡献包括：(1) 我们将一个预训练的 SOTA 图像到视频的 DiT 适配为一个 180 亿参数的音频驱动角色生成模型；(2) 我们通过从双向教师模型到稀疏因果自回归学生模型的不对称知识蒸馏，实现了无错误积累的无限视频流；(3) 我们设计了一个高吞吐量、低延迟的推理管道，其中包含多项关键工程优化，例如：(a) 将 DiT 和 VAE 解码器分布在不同设备上；(b) 使用 CUDA 流实现设备间通信与计算的高效重叠；(c) 消除冗余计算以最大化帧生成吞吐量。请在此处查看演示视频 - https://aaxwaz.github.io/TalkingMachines/

> In this paper, we present TalkingMachines -- an efficient framework that transforms pretrained video generation models into real-time, audio-driven character animators. TalkingMachines enables natural conversational experiences by integrating an audio large language model (LLM) with our video generation foundation model. Our primary contributions include: (1) We adapt a pretrained SOTA image-to-video DiT into an audio-driven avatar generation model of 18 billion parameters; (2) We enable infinite video streaming without error accumulation through asymmetric knowledge distillation from a bidirectional teacher model into a sparse causal, autoregressive student model; (3) We design a high-throughput, low-latency inference pipeline incorporating several key engineering optimizations such as: (a) disaggregation of the DiT and VAE decoder across separate devices, (b) efficient overlap of inter-device communication and computation using CUDA streams, (c) elimination of redundant recomputations to maximize frame-generation throughput. Please see demo videos here - https://aaxwaz.github.io/TalkingMachines/

[Arxiv](https://arxiv.org/abs/2506.03099)