# CoF：针对多模态大型语言模型的从粗到细粒度的图像理解

发布时间：2024年12月22日

`LLM应用` `多模态` `视觉理解`

> CoF: Coarse to Fine-Grained Image Understanding for Multi-modal Large Language Models

# 摘要

> 大型语言模型（LLM）的卓越表现促使研究人员研发了多模态 LLM（MLLM），其在各类多模态任务中展现出巨大潜力。然而，当下的 MLLM 常常难以有效应对细粒度的多模态难题。我们认为，这一局限与模型的视觉基础能力紧密相连。视觉编码器有限的空间感知和感知敏锐度，常常致使图像中的无关背景信息形成干扰，导致模型忽略细微却关键的细节。故而，达成细粒度的区域视觉理解颇为困难。在本文中，我们把多模态理解划分为两个阶段，即从粗到细（CoF）。在第一阶段，我们引导 MLLM 定位答案的大致区域。在第二阶段，我们借助视觉提示工程进一步强化模型对图像内相关区域的关注，调整相关区域的注意力权重。这进而提升了视觉基础能力和下游任务的整体表现。我们的实验表明，这种方法大幅提升了基线模型的性能，展现出显著的泛化能力和有效性。我们的 CoF 方法可在 https://github.com/Gavin001201/CoF 在线获取。

> The impressive performance of Large Language Model (LLM) has prompted researchers to develop Multi-modal LLM (MLLM), which has shown great potential for various multi-modal tasks. However, current MLLM often struggles to effectively address fine-grained multi-modal challenges. We argue that this limitation is closely linked to the models' visual grounding capabilities. The restricted spatial awareness and perceptual acuity of visual encoders frequently lead to interference from irrelevant background information in images, causing the models to overlook subtle but crucial details. As a result, achieving fine-grained regional visual comprehension becomes difficult. In this paper, we break down multi-modal understanding into two stages, from Coarse to Fine (CoF). In the first stage, we prompt the MLLM to locate the approximate area of the answer. In the second stage, we further enhance the model's focus on relevant areas within the image through visual prompt engineering, adjusting attention weights of pertinent regions. This, in turn, improves both visual grounding and overall performance in downstream tasks. Our experiments show that this approach significantly boosts the performance of baseline models, demonstrating notable generalization and effectiveness. Our CoF approach is available online at https://github.com/Gavin001201/CoF.

[Arxiv](https://arxiv.org/abs/2412.16869)