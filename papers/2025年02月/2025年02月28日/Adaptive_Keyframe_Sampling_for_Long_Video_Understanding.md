# # 自适应关键帧采样：长视频理解的新突破

发布时间：2025年02月28日

`LLM应用` `视频处理` `问答系统`

> Adaptive Keyframe Sampling for Long Video Understanding

# 摘要

> 多模态大型语言模型（MLLMs）通过将视觉输入作为额外的上下文令牌注入大型语言模型（LLMs）中，实现了开放世界视觉理解。然而，当视觉输入从单张图像变为长视频时，上述范式遇到了困难，因为视频令牌的数量远远超出了MLLMs的最大容量。因此，现有的基于视频的MLLMs大多建立在从输入数据中采样少量令牌的基础上，这可能导致关键信息丢失，从而产生错误答案。本文提出了一种简单而有效的算法，名为自适应关键帧采样（AKS）。它插入了一个即插即用模块，称为关键帧选择，旨在在固定数量的视频令牌下最大化有用信息。我们将关键帧选择建模为一个优化问题，涉及（1）关键帧与提示词的相关性，以及（2）关键帧对整个视频的覆盖范围，并提出了一种自适应算法来逼近最优解。在两个长视频理解基准上的实验验证了，通过选择信息丰富的关键帧，自适应关键帧采样能够提升视频问答的准确性（超越强基线模型）。我们的研究表明，在基于视频的MLLMs中，信息预过滤的重要性。代码可在https://github.com/ncTimTang/AKS获取。

> Multimodal large language models (MLLMs) have enabled open-world visual understanding by injecting visual input as extra tokens into large language models (LLMs) as contexts. However, when the visual input changes from a single image to a long video, the above paradigm encounters difficulty because the vast amount of video tokens has significantly exceeded the maximal capacity of MLLMs. Therefore, existing video-based MLLMs are mostly established upon sampling a small portion of tokens from input data, which can cause key information to be lost and thus produce incorrect answers. This paper presents a simple yet effective algorithm named Adaptive Keyframe Sampling (AKS). It inserts a plug-and-play module known as keyframe selection, which aims to maximize the useful information with a fixed number of video tokens. We formulate keyframe selection as an optimization involving (1) the relevance between the keyframes and the prompt, and (2) the coverage of the keyframes over the video, and present an adaptive algorithm to approximate the best solution. Experiments on two long video understanding benchmarks validate that Adaptive Keyframe Sampling improves video QA accuracy (beyond strong baselines) upon selecting informative keyframes. Our study reveals the importance of information pre-filtering in video-based MLLMs. Code is available at https://github.com/ncTimTang/AKS.

[Arxiv](https://arxiv.org/abs/2502.21271)