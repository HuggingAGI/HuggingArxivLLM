# 细粒度视频-文本检索：新基准与方法

发布时间：2024年12月31日

`LLM应用

理由：这篇论文主要讨论了视频-语言检索任务中的细粒度信息感知能力，并提出了一个新的基准FIBER。虽然论文中提到了多模态大型语言模型（MLLMs）的应用，但其核心内容集中在如何利用这些模型来提升视频-语言检索的性能，特别是通过文本嵌入方法来解锁MLLMs的细粒度理解能力。因此，这篇论文更符合“LLM应用”这一分类，因为它主要关注的是如何将大型语言模型应用于具体的任务（视频-语言检索）中，而不是探讨LLM的理论或构建新的Agent系统。` `视频检索` `多模态学习`

> Fine-grained Video-Text Retrieval: A New Benchmark and Method

# 摘要

> 细粒度空间和时间信息的感知能力对视频-语言检索至关重要。然而，现有视频检索基准（如MSRVTT和MSVD）因缺乏详细注释，难以有效评估视频-语言模型（VLMs）的细粒度检索能力。为此，我们推出了FIBER——一个包含1,000个FineAction数据集视频的细粒度文本到视频检索基准。FIBER独特之处在于为每个视频提供了详细的人工注释，涵盖空间和时间维度，从而能够独立评估VLMs在视频检索任务中的空间和时间偏差。此外，我们采用文本嵌入方法，解锁了多模态大型语言模型（MLLMs）的细粒度视频-语言理解能力。实验结果显示，我们的视频大型语言编码器（VLLE）在传统基准上的表现与CLIP模型相当，且在细粒度表示能力上更胜一筹，空间-时间偏差更低。项目页面：https://fiber-bench.github.io。

> The ability of perceiving fine-grained spatial and temporal information is crucial for video-language retrieval. However, the existing video retrieval benchmarks, such as MSRVTT and MSVD, fail to efficiently evaluate the fine-grained retrieval ability of video-language models (VLMs) due to a lack of detailed annotations. To address this problem, we present FIBER, a FIne-grained BEnchmark for text to video Retrieval, containing 1,000 videos sourced from the FineAction dataset. Uniquely, our FIBER benchmark provides detailed human-annotated spatial annotations and temporal annotations for each video, making it possible to independently evaluate the spatial and temporal bias of VLMs on video retrieval task. Besides, we employ a text embedding method to unlock the capability of fine-grained video-language understanding of Multimodal Large Language Models (MLLMs). Surprisingly, the experiment results show that our Video Large Language Encoder (VLLE) performs comparably to CLIP-based models on traditional benchmarks and has a stronger capability of fine-grained representation with lower spatial-temporal bias. Project page: https://fiber-bench.github.io.

[Arxiv](https://arxiv.org/abs/2501.00513)