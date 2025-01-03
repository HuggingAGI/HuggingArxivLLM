# LongVU: 长视频-语言理解的时空自适应压缩技术

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了如何通过一种名为LongVU的时空自适应压缩机制来处理长视频内容，以克服LLM上下文大小的限制。该研究聚焦于多模态大型语言模型（MLLMs）在视频内容理解和分析中的应用，特别是如何通过压缩策略在保持视频细节的同时减少视频标记数量。因此，这篇论文属于LLM应用类别，因为它涉及如何将LLM技术应用于具体的实际问题（视频理解）并提出了相应的解决方案。` `视频分析` `人工智能`

> LongVU: Spatiotemporal Adaptive Compression for Long Video-Language Understanding

# 摘要

> # 多模态大型语言模型（MLLMs）在视频内容理解和分析方面取得了显著进展。然而，处理长视频仍面临LLM上下文大小的限制。为此，我们提出了LongVU，一种时空自适应压缩机制，能在保留长视频视觉细节的同时减少视频标记数量。我们通过跨模态查询和帧间依赖关系，自适应地减少视频中的时间和空间冗余。具体而言，利用DINOv2特征去除高相似度的冗余帧，并通过文本引导的跨模态查询选择性减少帧特征。此外，基于帧的时间依赖性进行空间标记减少。这一自适应压缩策略在给定上下文长度内高效处理大量帧，几乎无视觉信息损失。LongVU在多个视频理解基准测试中表现优异，尤其在长达一小时的视频理解任务（如VideoMME和MLVU）中表现突出。即使在轻量级LLM上，LongVU也能保持最先进的视频理解性能，并有效缩小模型尺寸。

> Multimodal Large Language Models (MLLMs) have shown promising progress in understanding and analyzing video content. However, processing long videos remains a significant challenge constrained by LLM's context size. To address this limitation, we propose LongVU, a spatiotemporal adaptive compression mechanism thats reduces the number of video tokens while preserving visual details of long videos. Our idea is based on leveraging cross-modal query and inter-frame dependencies to adaptively reduce temporal and spatial redundancy in videos. Specifically, we leverage DINOv2 features to remove redundant frames that exhibit high similarity. Then we utilize text-guided cross-modal query for selective frame feature reduction. Further, we perform spatial token reduction across frames based on their temporal dependencies. Our adaptive compression strategy effectively processes a large number of frames with little visual information loss within given context length. Our LongVU consistently surpass existing methods across a variety of video understanding benchmarks, especially on hour-long video understanding tasks such as VideoMME and MLVU. Given a light-weight LLM, our LongVU also scales effectively into a smaller size with state-of-the-art video understanding performance.

[Arxiv](https://arxiv.org/abs/2410.17434)