# 多模态大型语言模型（Multimodal LLMs）用于文本到图像生成的定制奖励模型

发布时间：2025年07月28日

`LLM应用

理由：这篇论文讨论了如何利用多模态大型语言模型（MLLMs）来评估文本到图像的生成质量，属于将LLM应用于特定任务的范畴。` `生成式AI` `计算机视觉`

> Multimodal LLMs as Customized Reward Models for Text-to-Image Generation

# 摘要

> 我们推出了LLaVA-Reward，一款高效奖励模型，专为利用预训练的多模态大型语言模型（MLLMs）从多角度自动评估文本到图像（T2I）生成而设计。现有基于MLLM的方法依赖指令遵循数据进行监督微调，且通过分析文本响应来评估生成质量，这一过程耗时且训练困难。为解决这一问题，我们提出LLaVA-Reward，它直接利用MLLMs在文本-图像对上的隐藏状态。为了提升解码器型MLLM中视觉与文本表示的双向交互，我们进一步引入跨连接交叉注意力（SkipCA）模块。通过连接早期层的视觉特征与后期层的隐藏表示，该设计显著增强了文本-图像相关性推理能力。此外，LLaVA-Reward支持多种偏好数据类型的高效微调，包括配对偏好数据和非配对数据。我们在文本-图像对齐、保真度/伪影、安全性以及整体排名四个视角上训练LLaVA-Reward。实证结果表明，LLaVA-Reward在生成与人类对齐的分数方面超越了传统方法和基于MLLM的方法，并在文本到图像生成的自动评估和推理时间扩展方面展现了卓越性能。

> We introduce LLaVA-Reward, an efficient reward model designed to automatically evaluate text-to-image (T2I) generations across multiple perspectives, leveraging pretrained multimodal large language models (MLLMs). Existing MLLM-based approaches require instruction-following data for supervised fine-tuning and evaluate generation quality on analyzing text response, which is time-consuming and difficult to train. To address this problem, we propose LLaVA-Reward, which directly utilizes the hidden states of MLLMs given text-image pairs. To enhance the bidirectional interaction between visual and textual representations in decoder-only MLLMs, we further propose adding a Skip-connection Cross Attention (SkipCA) module. This design enhances text-image correlation reasoning by connecting early-layer visual features with later-layer hidden representations.In addition, LLaVA-Reward supports different types of preference data for efficient fine-tuning, including paired preference data and unpaired data. We train LLaVA-Reward on four evaluation perspectives: text-image alignment, fidelity/artifact, safety, and overall ranking. Empirical results demonstrate that LLaVA-Reward outperforms conventional and MLLM-based methods in generating human-aligned scores for automatic evaluations and inference-time scaling in text-to-image generations.

[Arxiv](https://arxiv.org/abs/2507.21391)