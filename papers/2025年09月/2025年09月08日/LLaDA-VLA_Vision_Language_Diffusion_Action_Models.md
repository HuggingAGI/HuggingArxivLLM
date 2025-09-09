# LLaDA-VLA：视觉语言扩散动作模型

发布时间：2025年09月08日

`LLM应用` `工业与制造`

> LLaDA-VLA: Vision Language Diffusion Action Models

# 摘要

> 自回归视觉语言模型（VLMs）的迅猛发展，激发了人们对机器人操作领域中视觉语言动作模型（VLA）的浓厚兴趣。近年来，掩码扩散模型作为一种有别于自回归模型的范式，在文本生成与多模态应用中崭露头角，表现出极具竞争力的性能，由此催生了一系列基于扩散的VLMs（d-VLMs）。然而，将这类模型应用于机器人策略学习的研究尚未充分展开。在本研究中，我们提出了LLaDA-VLA——首个基于预训练d-VLMs构建的视觉-语言-扩散-动作模型，专门用于机器人操作任务。为将d-VLMs有效适配到机器人领域，我们创新性地设计了两项关键技术：（1）局部化特殊标记分类策略，通过特殊动作标记分类替代全词汇分类，大幅降低了适配难度；（2）分层动作结构解码策略，兼顾动作内部及动作间的依赖关系，实现动作序列的分层解码。大量实验结果显示，LLaDA-VLA在模拟机器人和真实世界机器人上的性能均显著超越了当前最先进的VLAs。

> The rapid progress of auto-regressive vision-language models (VLMs) has inspired growing interest in vision-language-action models (VLA) for robotic manipulation. Recently, masked diffusion models, a paradigm distinct from autoregressive models, have begun to demonstrate competitive performance in text generation and multimodal applications, leading to the development of a series of diffusion-based VLMs (d-VLMs). However, leveraging such models for robot policy learning remains largely unexplored. In this work, we present LLaDA-VLA, the first Vision-Language-Diffusion-Action model built upon pretrained d-VLMs for robotic manipulation. To effectively adapt d-VLMs to robotic domain, we introduce two key designs: (1) a localized special-token classification strategy that replaces full-vocabulary classification with special action token classification, reducing adaptation difficulty; (2) a hierarchical action-structured decoding strategy that decodes action sequences hierarchically considering the dependencies within and across actions. Extensive experiments demonstrate that LLaDA-VLA significantly outperforms state-of-the-art VLAs on both simulation and real-world robots.

[Arxiv](https://arxiv.org/abs/2509.06932)