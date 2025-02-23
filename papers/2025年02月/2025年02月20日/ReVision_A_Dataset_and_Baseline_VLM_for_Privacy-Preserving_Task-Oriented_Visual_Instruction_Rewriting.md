# ReVision：面向隐私保护的任务导向视觉指令重写基准数据集与视觉语言模型

发布时间：2025年02月20日

`LLM应用

理由：这篇论文探讨了视觉语言模型（VLMs）在多模态交互中的应用，特别是通过视觉指令改写来提升隐私保护。它展示了如何将VLMs应用于实际场景，以解决隐私和实时性问题，属于LLM的实际应用范畴。` `智能设备` `人工智能`

> ReVision: A Dataset and Baseline VLM for Privacy-Preserving Task-Oriented Visual Instruction Rewriting

# 摘要

> 随着增强现实 (AR)、虚拟现实 (VR) 和配备强大摄像头的现代智能手机成为人机交互的主要界面，高效且注重隐私的多模态交互变得至关重要。现有的强大视觉语言模型 (VLMs) 虽然支持多模态交互，但它们通常依赖基于云的处理，这带来了两个主要问题：(1) 将敏感视觉数据传输到服务器会引发隐私担忧，以及 (2) 它们在实时、设备端的实用性有限。本文提出了一种名为“视觉指令改写”的创新方法，通过将多模态指令转换为纯文本命令，实现了轻量级设备端指令改写器 VLM（25亿参数）与现有对话 AI 系统的无缝整合，从而提升视觉数据隐私。为此，我们构建了一个涵盖14个领域、包含超过3.9万个实例的数据集，并开发了一个紧凑型 VLM，该模型基于图像描述数据集进行预训练，并针对指令改写进行了微调。通过 BLEU、METEOR 和 ROUGE 等自然语言生成指标以及语义解析分析的实验结果表明，即使使用模型的量化版本（<500MB 存储占用），也能实现有效的指令改写，从而支持以隐私为中心的多模态 AI 应用。

> Efficient and privacy-preserving multimodal interaction is essential as AR, VR, and modern smartphones with powerful cameras become primary interfaces for human-computer communication. Existing powerful large vision-language models (VLMs) enabling multimodal interaction often rely on cloud-based processing, raising significant concerns about (1) visual privacy by transmitting sensitive vision data to servers, and (2) their limited real-time, on-device usability. This paper explores Visual Instruction Rewriting, a novel approach that transforms multimodal instructions into text-only commands, allowing seamless integration of lightweight on-device instruction rewriter VLMs (250M parameters) with existing conversational AI systems, enhancing vision data privacy. To achieve this, we present a dataset of over 39,000 examples across 14 domains and develop a compact VLM, pretrained on image captioning datasets and fine-tuned for instruction rewriting. Experimental results, evaluated through NLG metrics such as BLEU, METEOR, and ROUGE, along with semantic parsing analysis, demonstrate that even a quantized version of the model (<500MB storage footprint) can achieve effective instruction rewriting, thus enabling privacy-focused, multimodal AI applications.

[Arxiv](https://arxiv.org/abs/2502.14780)