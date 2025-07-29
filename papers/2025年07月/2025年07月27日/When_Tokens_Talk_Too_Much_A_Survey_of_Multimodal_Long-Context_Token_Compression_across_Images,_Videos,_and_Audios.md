# # **标记说得太多时：涵盖图像、视频和音频的多模态长上下文标记压缩综述**

发布时间：2025年07月27日

`其他` `多模态` `标记压缩`

> When Tokens Talk Too Much: A Survey of Multimodal Long-Context Token Compression across Images, Videos, and Audios

# 摘要

> 多模态大语言模型（MLLMs）在处理复杂上下文方面取得了显著进展，例如高分辨率图像、延长视频和长音频输入。然而，这种能力也带来了计算挑战，主要源于自注意力机制的二次复杂度。为解决这一问题，标记压缩作为一种高效方法应运而生。本文首次系统性综述了多模态长上下文标记压缩领域，并根据数据特性将其分为三类：视觉、动态和声学压缩。此外，我们还从机制角度将其细分为基于变换、相似性、注意力和查询的方法。本综述旨在整合当前研究，识别关键挑战，并启发未来研究。我们还维护了一个公共存储库，持续跟踪该领域的最新进展。

> Multimodal large language models (MLLMs) have made remarkable strides, largely driven by their ability to process increasingly long and complex contexts, such as high-resolution images, extended video sequences, and lengthy audio input. While this ability significantly enhances MLLM capabilities, it introduces substantial computational challenges, primarily due to the quadratic complexity of self-attention mechanisms with numerous input tokens. To mitigate these bottlenecks, token compression has emerged as an auspicious and critical approach, efficiently reducing the number of tokens during both training and inference. In this paper, we present the first systematic survey and synthesis of the burgeoning field of multimodal long context token compression. Recognizing that effective compression strategies are deeply tied to the unique characteristics and redundancies of each modality, we categorize existing approaches by their primary data focus, enabling researchers to quickly access and learn methods tailored to their specific area of interest: (1) image-centric compression, which addresses spatial redundancy in visual data; (2) video-centric compression, which tackles spatio-temporal redundancy in dynamic sequences; and (3) audio-centric compression, which handles temporal and spectral redundancy in acoustic signals. Beyond this modality-driven categorization, we further dissect methods based on their underlying mechanisms, including transformation-based, similarity-based, attention-based, and query-based approaches. By providing a comprehensive and structured overview, this survey aims to consolidate current progress, identify key challenges, and inspire future research directions in this rapidly evolving domain. We also maintain a public repository to continuously track and update the latest advances in this promising area.

[Arxiv](https://arxiv.org/abs/2507.20198)