# Video-XL-2：迈向超长视频理解的键值稀疏化探索

发布时间：2025年06月23日

`LLM应用` `视频理解` `计算机视觉`

> Video-XL-2: Towards Very Long-Video Understanding Through Task-Aware KV Sparsification

# 摘要

> # 摘要
多模态大语言模型 (MLLMs) 在视频理解领域取得了显著进展，但长视频输入处理仍面临高内存和计算成本的挑战，使得当前模型难以兼顾高性能与高效率。为解决这一难题，我们提出了 Video-XL-2，这是一种基于任务感知 KV 稀疏化的新型 MLLM，专为长视频理解提供卓越的成本效益。

该框架采用两大核心步骤：基于块的预填充与双层键值解码。基于块的预填充将视觉令牌序列划分为块，在每个块内应用完全注意力，跨块则采用稀疏注意力，大幅降低了计算与内存开销。解码过程中，双层键值解码根据每个块与任务的相关性，选择性地重新加载密集或稀疏的键值，进一步提升内存效率并增强模型捕捉细粒度信息的能力。

Video-XL-2 在各类长视频理解基准测试中表现卓越，超越现有开源轻量级模型。其效率同样出色，可在单个 NVIDIA A100 (80GB) GPU 上处理超过 10,000 帧，并在短短几秒内完成数千帧的处理。

> Multi-modal large language models (MLLMs) models have made significant progress in video understanding over the past few years. However, processing long video inputs remains a major challenge due to high memory and computational costs. This makes it difficult for current models to achieve both strong performance and high efficiency in long video understanding. To address this challenge, we propose Video-XL-2, a novel MLLM that delivers superior cost-effectiveness for long-video understanding based on task-aware KV sparsification. The proposed framework operates with two key steps: chunk-based pre-filling and bi-level key-value decoding. Chunk-based pre-filling divides the visual token sequence into chunks, applying full attention within each chunk and sparse attention across chunks. This significantly reduces computational and memory overhead. During decoding, bi-level key-value decoding selectively reloads either dense or sparse key-values for each chunk based on its relevance to the task. This approach further improves memory efficiency and enhances the model's ability to capture fine-grained information. Video-XL-2 achieves state-of-the-art performance on various long video understanding benchmarks, outperforming existing open-source lightweight models. It also demonstrates exceptional efficiency, capable of processing over 10,000 frames on a single NVIDIA A100 (80GB) GPU and thousands of frames in just a few seconds.

[Arxiv](https://arxiv.org/abs/2506.19225)