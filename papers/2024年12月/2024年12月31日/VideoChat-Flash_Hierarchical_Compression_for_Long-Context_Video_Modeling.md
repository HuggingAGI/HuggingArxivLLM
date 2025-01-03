# VideoChat-Flash: 长上下文视频建模的分层压缩技术

发布时间：2024年12月31日

`LLM应用

**理由**：这篇论文主要讨论了一种新的方法（HiCo）和系统（VideoChat-Flash）来处理多模态大语言模型（MLLMs）中的长上下文建模问题，特别是针对极长视频的处理。这属于大语言模型在实际应用中的优化和改进，因此归类为LLM应用。` `视频处理` `多模态学习`

> VideoChat-Flash: Hierarchical Compression for Long-Context Video Modeling

# 摘要

> 长上下文建模是多模态大语言模型（MLLMs）的核心能力，使其能够处理具有隐式记忆的长篇内容。然而，处理极长视频仍面临挑战，主要在于难以在长序列中保持关键特征。本文提出了一种高保真表示的层次化视觉标记压缩方法（HiCo），以及专为多模态长序列处理设计的实用系统VideoChat-Flash。HiCo通过利用长视频中的视觉信息冗余，从片段级到视频级压缩上下文，在保留关键细节的同时大幅降低计算量。VideoChat-Flash采用多阶段从短到长的学习策略，并引入了一个名为LongVid的真实长视频数据集，以及升级版的“视频中的针”（NIAH）评估框架。在大量实验中，VideoChat-Flash在7B模型规模的主流长视频和短视频基准测试中表现优异，首次在开源模型中实现了NIAH 10,000帧99.1%的准确率。

> Long-context modeling is a critical capability for multimodal large language models (MLLMs), enabling them to process long-form contents with implicit memorization. Despite its advances, handling extremely long videos remains challenging due to the difficulty in maintaining crucial features over extended sequences. This paper introduces a Hierarchical visual token Compression (HiCo) method designed for high-fidelity representation and a practical context modeling system VideoChat-Flash tailored for multimodal long-sequence processing. HiCo capitalizes on the redundancy of visual information in long videos to compress long video context from the clip-level to the video-level, reducing the compute significantly while preserving essential details. VideoChat-Flash features a multi-stage short-to-long learning scheme, a rich dataset of real-world long videos named LongVid, and an upgraded "Needle-In-A-video-Haystack" (NIAH) for evaluating context capacities. In extensive experiments, VideoChat-Flash shows the leading performance on both mainstream long and short video benchmarks at the 7B model scale. It firstly gets 99.1% accuracy over 10,000 frames in NIAH among open-source models.

[Arxiv](https://arxiv.org/abs/2501.00574)