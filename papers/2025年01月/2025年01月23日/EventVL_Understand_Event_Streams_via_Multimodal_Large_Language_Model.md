# EventVL: 利用多模态大语言模型解析事件流

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了一个生成式多模态大语言模型（MLLM）框架EventVL，用于处理事件流中的语义和上下文信息。虽然涉及多模态和视觉任务，但其核心是围绕大语言模型的应用展开的，特别是在事件字幕和场景描述生成任务中的应用。因此，将其归类为LLM应用是合适的。` `自动驾驶` `计算机视觉`

> EventVL: Understand Event Streams via Multimodal Large Language Model

# 摘要

> 基于事件的视觉语言模型（VLM）在实际视觉任务中取得了显著进展。然而，现有研究大多依赖CLIP处理传统感知任务，导致模型难以从事件流中充分提取语义和上下文信息。为此，我们提出了EventVL，首个面向显式语义理解的生成式多模态大语言模型（MLLM）框架。我们首先构建了一个包含近140万对高质量数据的事件-图像/视频-文本数据集，覆盖驾驶场景、人体运动等多种场景，为跨模态语义学习奠定基础。随后，我们设计了事件时空表示方法，通过多样化聚合和分割事件流，全面挖掘信息。为进一步优化语义空间，我们引入了动态语义对齐机制，有效填补事件语义的稀疏性。实验表明，EventVL在事件字幕和场景描述生成任务中大幅超越现有MLLM基线。我们期待这项研究能推动事件视觉领域的发展。

> The event-based Vision-Language Model (VLM) recently has made good progress for practical vision tasks. However, most of these works just utilize CLIP for focusing on traditional perception tasks, which obstruct model understanding explicitly the sufficient semantics and context from event streams. To address the deficiency, we propose EventVL, the first generative event-based MLLM (Multimodal Large Language Model) framework for explicit semantic understanding. Specifically, to bridge the data gap for connecting different modalities semantics, we first annotate a large event-image/video-text dataset, containing almost 1.4 million high-quality pairs of data, which enables effective learning across various scenes, e.g., drive scene or human motion. After that, we design Event Spatiotemporal Representation to fully explore the comprehensive information by diversely aggregating and segmenting the event stream. To further promote a compact semantic space, Dynamic Semantic Alignment is introduced to improve and complete sparse semantic spaces of events. Extensive experiments show that our EventVL can significantly surpass existing MLLM baselines in event captioning and scene description generation tasks. We hope our research could contribute to the development of the event vision community.

[Arxiv](https://arxiv.org/abs/2501.13707)