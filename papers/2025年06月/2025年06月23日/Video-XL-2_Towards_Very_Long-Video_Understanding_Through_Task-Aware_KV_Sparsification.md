# Video-XL-2：通过任务感知的KV稀疏化，迈向超长视频理解的新境界

发布时间：2025年06月23日

`LLM应用` `视频理解` `视频分析`

> Video-XL-2: Towards Very Long-Video Understanding Through Task-Aware KV Sparsification

# 摘要

> 多模态大型语言模型 (MLLMs) 在视频理解领域取得了显著进展，但长视频输入处理仍面临巨大挑战，主要归因于高昂的内存和计算成本，使得现有模型难以在长视频理解中同时实现强劲性能和高效运行。为应对这一挑战，我们提出 Video-XL-2，一种基于任务感知 KV 稀疏化的新型 MLLM，为长视频理解提供卓越的成本效益。该框架主要通过两个关键步骤运行：基于块的预填充和两级键值解码。基于块的预填充将视觉令牌序列划分为块，对每个块内部应用完整注意力，跨块则采用稀疏注意力，大幅降低了计算和内存开销。在解码阶段，两级键值解码根据每个块与任务的相关性，选择性地重新加载密集或稀疏的键值，进一步提升了内存效率，并增强了模型捕捉细粒度信息的能力。Video-XL-2 在多个长视频理解基准测试中实现了最先进的性能，超越现有开源轻量级模型。它还展现了卓越的效率，能够在单个 NVIDIA A100 (80GB) GPU 上处理超过 10,000 帧，并在短短几秒内完成数千帧的处理。

> Multi-modal large language models (MLLMs) models have made significant progress in video understanding over the past few years. However, processing long video inputs remains a major challenge due to high memory and computational costs. This makes it difficult for current models to achieve both strong performance and high efficiency in long video understanding. To address this challenge, we propose Video-XL-2, a novel MLLM that delivers superior cost-effectiveness for long-video understanding based on task-aware KV sparsification. The proposed framework operates with two key steps: chunk-based pre-filling and bi-level key-value decoding. Chunk-based pre-filling divides the visual token sequence into chunks, applying full attention within each chunk and sparse attention across chunks. This significantly reduces computational and memory overhead. During decoding, bi-level key-value decoding selectively reloads either dense or sparse key-values for each chunk based on its relevance to the task. This approach further improves memory efficiency and enhances the model's ability to capture fine-grained information. Video-XL-2 achieves state-of-the-art performance on various long video understanding benchmarks, outperforming existing open-source lightweight models. It also demonstrates exceptional efficiency, capable of processing over 10,000 frames on a single NVIDIA A100 (80GB) GPU and thousands of frames in just a few seconds.

[Arxiv](https://arxiv.org/abs/2506.19225)