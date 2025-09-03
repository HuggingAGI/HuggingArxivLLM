# 变化感知视觉令牌丢弃：加速大型视觉语言模型

发布时间：2025年09月01日

`LLM应用` `基础理论`

> Variation-aware Vision Token Dropping for Faster Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在多模态理解任务中已展现卓越能力。但随着对高分辨率图像和长视频理解需求的增长，token数量激增，导致推理效率下降。token压缩通过减少需处理的token数量，成为提升计算效率的直接方案。经深入分析，我们发现现有LLM内部token压缩方法存在两大关键局限：位置偏差及与高效算子不兼容，这制约了它们在LVLM加速中的实际应用。本文首次从token变化视角切入，揭示LLM内部视觉token变化具有任务无关特性，并提出变化感知视觉token丢弃方法（即V²Drop）。该方法在LVLM推理时逐步移除变化最小的视觉token，有效提升计算效率。多模型与基准测试的大量实验表明，V²Drop在图像和视频理解任务中分别能保留原始模型94.0%和98.6%的性能，同时将LLM生成延迟降低31.5%和74.2%；与高效算子结合后，还可进一步减少GPU峰值内存占用。

> Large vision-language models (LVLMs) have demonstrated remarkable capabilities in multimodal understanding tasks. However, the increasing demand for high-resolution image and long-video understanding results in substantial token counts, leading to reduced inference efficiency. Token compression offers a direct solution by reducing the number of tokens to be processed, thereby improving computational efficiency. Through extensive analysis, we identify two critical limitations in existing inner-LLM token compression methods: positional bias and incompatibility with efficient operators, which hinder their practical deployment for LVLM acceleration. This paper presents the first approach from a token variation perspective, revealing that visual token variations within LLMs exhibit task-agnostic properties. We propose Variation-aware Vision Token Dropping (\textit{i.e.}, \textbf{V$^2$Drop}), which progressively removes visual tokens with minimal variation during LVLM inference, thereby enhancing computational efficiency. Extensive experiments across multiple models and benchmarks demonstrate that our V$^2$Drop is able to maintain \textbf{94.0\%} and \textbf{98.6\%} of the original model performance for image and video understanding tasks respectively, while reducing LLM generation latency by \textbf{31.5\%} and \textbf{74.2\%}. When combined with efficient operators, V$^2$Drop further reduces GPU peak memory usage.

[Arxiv](https://arxiv.org/abs/2509.01552)