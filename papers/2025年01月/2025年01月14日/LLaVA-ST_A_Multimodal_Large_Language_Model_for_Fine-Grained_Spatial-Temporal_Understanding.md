# LLaVA-ST: 多模态大语言模型，专精于细粒度时空理解

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在处理时间和空间定位方面的挑战，并提出了LLaVA-ST模型来解决这些问题。论文还介绍了用于训练和评估的数据集和基准。这些内容主要涉及如何应用大型语言模型来解决具体的多模态理解问题，因此应归类为“LLM应用”。` `计算机视觉` `视频分析`

> LLaVA-ST: A Multimodal Large Language Model for Fine-Grained Spatial-Temporal Understanding

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）的最新进展令人瞩目，但现有方法难以同时有效处理时间和空间定位。这一挑战源于两大问题：一是时空定位引入了大量坐标组合，增加了语言与视觉坐标对齐的复杂性；二是视频特征压缩中难以编码细粒度的时间和空间信息。为此，我们提出了LLaVA-ST，一个专为细粒度时空多模态理解设计的MLLM。LLaVA-ST引入了语言对齐的位置嵌入，将文本坐标标记嵌入视觉空间，简化了细粒度时空对应关系的对齐。我们还设计了时空打包器，将时间和空间分辨率特征压缩解耦为两个独立的点对区域注意力处理流。此外，我们构建了包含430万训练样本的ST-Align数据集，用于细粒度时空多模态理解。通过ST-Align，我们提出了一个渐进式训练管道，逐步从粗到细对齐视觉和文本特征。我们还推出了ST-Align基准，用于评估时空交错细粒度理解任务，包括时空视频定位（STVG）、事件定位与字幕（ELC）以及空间视频定位（SVG）。LLaVA-ST在11个需要细粒度时间、空间或时空交错多模态理解的基准上表现卓越。代码、数据和基准将在https://github.com/appletea233/LLaVA-ST发布。

> Recent advancements in multimodal large language models (MLLMs) have shown promising results, yet existing approaches struggle to effectively handle both temporal and spatial localization simultaneously. This challenge stems from two key issues: first, incorporating spatial-temporal localization introduces a vast number of coordinate combinations, complicating the alignment of linguistic and visual coordinate representations; second, encoding fine-grained temporal and spatial information during video feature compression is inherently difficult. To address these issues, we propose LLaVA-ST, a MLLM for fine-grained spatial-temporal multimodal understanding. In LLaVA-ST, we propose Language-Aligned Positional Embedding, which embeds the textual coordinate special token into the visual space, simplifying the alignment of fine-grained spatial-temporal correspondences. Additionally, we design the Spatial-Temporal Packer, which decouples the feature compression of temporal and spatial resolutions into two distinct point-to-region attention processing streams. Furthermore, we propose ST-Align dataset with 4.3M training samples for fine-grained spatial-temporal multimodal understanding. With ST-align, we present a progressive training pipeline that aligns the visual and textual feature through sequential coarse-to-fine stages.Additionally, we introduce an ST-Align benchmark to evaluate spatial-temporal interleaved fine-grained understanding tasks, which include Spatial-Temporal Video Grounding (STVG) , Event Localization and Captioning (ELC) and Spatial Video Grounding (SVG). LLaVA-ST achieves outstanding performance on 11 benchmarks requiring fine-grained temporal, spatial, or spatial-temporal interleaving multimodal understanding. Our code, data and benchmark will be released at Our code, data and benchmark will be released at https://github.com/appletea233/LLaVA-ST .

[Arxiv](https://arxiv.org/abs/2501.08282)