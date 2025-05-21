# # 视频压缩指挥官：为视频大语言模型打造的即插即用推理加速器

发布时间：2025年05月20日

`LLM应用` `视频处理`

> Video Compression Commander: Plug-and-Play Inference Acceleration for Video Large Language Models

# 摘要

> 视频大型语言模型（VideoLLM）在视频理解领域表现出色，但因丰富的视觉标记带来的二次复杂度而面临效率难题。通过对VideoLLM的标记压缩方法进行系统性分析，我们发现了两个关键问题：（i）忽视了跨帧的独特视觉信号，导致信息丢失；（ii）受到实现约束，导致与现代架构或高效操作不兼容。为了解决这些挑战，我们提炼了三条VideoLLM标记压缩的设计原则，并提出了一种即插即用的推理加速框架——“视频压缩指挥官”（VidCom2）。通过量化每帧的独特性，VidCom2能够自适应地调整跨帧压缩强度，有效保留关键信息，同时减少视频序列中的冗余。在各种VideoLLMs和基准测试中的广泛实验表明，我们的VidCom2在性能和效率上都表现出色。在LLaVA-OV上，VidCom2只需25%的视觉标记即可达到原性能的99.6%，同时将LLM生成延迟减少了70.8%。值得注意的是，我们的帧压缩调整策略与其他标记压缩方法兼容，可进一步提升其性能。我们的代码可在https://github.com/xuyang-liu16/VidCom2获取。

> Video large language models (VideoLLM) excel at video understanding, but face efficiency challenges due to the quadratic complexity of abundant visual tokens. Our systematic analysis of token compression methods for VideoLLMs reveals two critical issues: (i) overlooking distinctive visual signals across frames, leading to information loss; (ii) suffering from implementation constraints, causing incompatibility with modern architectures or efficient operators. To address these challenges, we distill three design principles for VideoLLM token compression and propose a plug-and-play inference acceleration framework "Video Compression Commander" (VidCom2). By quantifying each frame's uniqueness, VidCom2 adaptively adjusts compression intensity across frames, effectively preserving essential information while reducing redundancy in video sequences. Extensive experiments across various VideoLLMs and benchmarks demonstrate the superior performance and efficiency of our VidCom2. With only 25% visual tokens, VidCom2 achieves 99.6% of the original performance on LLaVA-OV while reducing 70.8% of the LLM generation latency. Notably, our Frame Compression Adjustment strategy is compatible with other token compression methods to further improve their performance. Our code is available at https://github.com/xuyang-liu16/VidCom2.

[Arxiv](https://arxiv.org/abs/2505.14454)