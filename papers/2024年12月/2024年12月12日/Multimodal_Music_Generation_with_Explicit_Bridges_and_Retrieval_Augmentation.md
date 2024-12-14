# 具有显式桥梁和检索增强的多模态音乐生成

发布时间：2024年12月12日

`LLM应用` `多媒体`

> Multimodal Music Generation with Explicit Bridges and Retrieval Augmentation

# 摘要

> 多模态音乐生成旨在通过多种输入模态（如文本、视频和图像）来创作音乐。现有的方法采用通用嵌入空间来实现多模态融合。然而，尽管在其他模态中成效显著，但应用于多模态音乐生成时，却面临着数据稀缺、跨模态对齐不佳以及可控性有限等挑战。本文借助文本与音乐的显性桥梁来解决这些问题，以达成多模态对齐。我们推出了一种名为视觉音乐桥（VMB）的新方法。具体而言，多模态音乐描述模型能将视觉输入转化为详尽的文本描述，从而提供文本桥梁；双轨音乐检索模块结合了广泛和有针对性的检索策略，提供音乐桥梁并实现用户控制。最后，我们设计了一个显式条件音乐生成框架，基于这两座桥梁来生成音乐。我们针对视频转音乐、图像转音乐、文本转音乐、可控音乐生成任务以及可控性开展了实验。结果显示，与以往方法相比，VMB 显著提升了音乐质量、模态和定制对齐效果。VMB 为在各类多媒体领域应用的可解释且富有表现力的多模态音乐生成树立了新标杆。演示和代码可在 https://github.com/wbs2788/VMB 获取。

> Multimodal music generation aims to produce music from diverse input modalities, including text, videos, and images. Existing methods use a common embedding space for multimodal fusion. Despite their effectiveness in other modalities, their application in multimodal music generation faces challenges of data scarcity, weak cross-modal alignment, and limited controllability. This paper addresses these issues by using explicit bridges of text and music for multimodal alignment. We introduce a novel method named Visuals Music Bridge (VMB). Specifically, a Multimodal Music Description Model converts visual inputs into detailed textual descriptions to provide the text bridge; a Dual-track Music Retrieval module that combines broad and targeted retrieval strategies to provide the music bridge and enable user control. Finally, we design an Explicitly Conditioned Music Generation framework to generate music based on the two bridges. We conduct experiments on video-to-music, image-to-music, text-to-music, and controllable music generation tasks, along with experiments on controllability. The results demonstrate that VMB significantly enhances music quality, modality, and customization alignment compared to previous methods. VMB sets a new standard for interpretable and expressive multimodal music generation with applications in various multimedia fields. Demos and code are available at https://github.com/wbs2788/VMB.

[Arxiv](https://arxiv.org/abs/2412.09428)