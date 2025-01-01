# VELoRA：一种实现高效基于 RGB-事件识别的低秩适配方法

发布时间：2024年12月28日

`其他` `计算机视觉` `模式识别`

> VELoRA: A Low-Rank Adaptation Approach for Efficient RGB-Event based Recognition

# 摘要

> 利用 RGB 和事件相机进行模式识别，通过部署采用微调策略的深度神经网络，性能能够显著提升。受大型模型成功应用的启发，引入这类大型模型也可进一步提升多模态任务的性能。然而，对这些模型进行全面微调会效率低下，所以诸如 LoRA 和 Adapter 等轻量级微调方法已被提出，以在效率和性能间达成更好的平衡。据我们了解，目前尚无基于预训练基础模型对 RGB-Event 识别进行参数高效微调（PEFT）的工作。为解决此问题，本文提出一种新颖的 PEFT 策略，让预训练的基础视觉模型适应基于 RGB-Event 的分类。具体而言，给定 RGB 帧和事件流，我们基于具有模态特定 LoRA 调整策略的视觉基础模型 ViT 提取 RGB 和事件特征。同时，还考虑了双模态的帧差，通过帧差骨干网络捕捉运动线索。将这些特征连接后，输入到高级 Transformer 层，通过模态共享的 LoRA 调整实现高效的多模态特征学习。最后，把这些特征连接并输入到分类头，实现高效微调。源代码和预训练模型将在 url{https://github.com/Event-AHU/VELoRA} 发布。

> Pattern recognition leveraging both RGB and Event cameras can significantly enhance performance by deploying deep neural networks that utilize a fine-tuning strategy. Inspired by the successful application of large models, the introduction of such large models can also be considered to further enhance the performance of multi-modal tasks. However, fully fine-tuning these models leads to inefficiency and lightweight fine-tuning methods such as LoRA and Adapter have been proposed to achieve a better balance between efficiency and performance. To our knowledge, there is currently no work that has conducted parameter-efficient fine-tuning (PEFT) for RGB-Event recognition based on pre-trained foundation models. To address this issue, this paper proposes a novel PEFT strategy to adapt the pre-trained foundation vision models for the RGB-Event-based classification. Specifically, given the RGB frames and event streams, we extract the RGB and event features based on the vision foundation model ViT with a modality-specific LoRA tuning strategy. The frame difference of the dual modalities is also considered to capture the motion cues via the frame difference backbone network. These features are concatenated and fed into high-level Transformer layers for efficient multi-modal feature learning via modality-shared LoRA tuning. Finally, we concatenate these features and feed them into a classification head to achieve efficient fine-tuning. The source code and pre-trained models will be released on url{https://github.com/Event-AHU/VELoRA}.

[Arxiv](https://arxiv.org/abs/2412.20064)