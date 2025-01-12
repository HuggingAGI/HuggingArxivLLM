# LLaVA-Mini: 单视觉标记驱动的高效图像与视频多模态大模型

发布时间：2025年01月07日

`LLM应用

**理由**：这篇论文主要讨论了如何通过优化视觉标记的处理来提高大型多模态模型（LMMs）的效率，特别是LLaVA-Mini模型的实现和性能。虽然涉及到了模型的结构和优化方法，但其核心目标是提升LLM在实际应用中的效率和性能，因此归类为“LLM应用”。` `计算机视觉` `多模态模型`

> LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token

# 摘要

> 实时大型多模态模型（LMMs）如GPT-4o的出现，激发了人们对高效LMMs的浓厚兴趣。LMM框架通常将视觉输入编码为视觉标记（连续表示），并将其与文本指令整合到大型语言模型（LLMs）的上下文中。然而，大规模参数和大量上下文标记（主要是视觉标记）带来了巨大的计算开销。以往的研究大多聚焦于用较小的模型替换LLM骨干，却忽视了标记数量的关键问题。本文提出的LLaVA-Mini，是一种视觉标记极简的高效LMM。为了在保留视觉信息的同时实现视觉标记的高压缩比，我们首先分析了LMMs如何理解视觉标记，发现大多数视觉标记仅在LLM骨干的早期层中起关键作用，主要将视觉信息融合到文本标记中。基于这一发现，LLaVA-Mini引入了模态预融合，提前将视觉信息融合到文本标记中，从而将输入到LLM骨干的视觉标记压缩为仅一个标记。LLaVA-Mini是一个统一的大型多模态模型，能够高效地支持图像、高分辨率图像和视频的理解。在11个基于图像和7个基于视频的基准测试中，实验表明LLaVA-Mini仅使用1个视觉标记而非576个，就超越了LLaVA-v1.5。效率分析显示，LLaVA-Mini可以将FLOPs减少77%，在40毫秒内提供低延迟响应，并在24GB内存的GPU硬件上处理超过10,000帧的视频。

> The advent of real-time large multimodal models (LMMs) like GPT-4o has sparked considerable interest in efficient LMMs. LMM frameworks typically encode visual inputs into vision tokens (continuous representations) and integrate them and textual instructions into the context of large language models (LLMs), where large-scale parameters and numerous context tokens (predominantly vision tokens) result in substantial computational overhead. Previous efforts towards efficient LMMs always focus on replacing the LLM backbone with smaller models, while neglecting the crucial issue of token quantity. In this paper, we introduce LLaVA-Mini, an efficient LMM with minimal vision tokens. To achieve a high compression ratio of vision tokens while preserving visual information, we first analyze how LMMs understand vision tokens and find that most vision tokens only play a crucial role in the early layers of LLM backbone, where they mainly fuse visual information into text tokens. Building on this finding, LLaVA-Mini introduces modality pre-fusion to fuse visual information into text tokens in advance, thereby facilitating the extreme compression of vision tokens fed to LLM backbone into one token. LLaVA-Mini is a unified large multimodal model that can support the understanding of images, high-resolution images, and videos in an efficient manner. Experiments across 11 image-based and 7 video-based benchmarks demonstrate that LLaVA-Mini outperforms LLaVA-v1.5 with just 1 vision token instead of 576. Efficiency analyses reveal that LLaVA-Mini can reduce FLOPs by 77%, deliver low-latency responses within 40 milliseconds, and process over 10,000 frames of video on the GPU hardware with 24GB of memory.

[Arxiv](https://arxiv.org/abs/2501.03895)