# 高效大型多模态模型服务之路

发布时间：2025年02月02日

`LLM应用

理由：这篇论文主要讨论了大型多模态模型（LMMs）在生产环境中的部署和优化问题，涉及系统分析和资源管理。虽然提到了模型的架构和推理过程，但核心内容集中在如何在实际应用中高效部署和优化这些模型，因此属于LLM应用的范畴。` `人工智能` `系统架构`

> Towards Efficient Large Multimodal Model Serving

# 摘要

> # 摘要
生成式AI的突破性进展催生了能够同时处理文本、图像、视频和音频等多种模态输入的大型多模态模型（LMMs）。尽管这些模型能力强大，但其复杂的架构和异构的资源需求使得在生产环境中高效部署成为一大挑战。
  我们对两种主流LMM架构——仅解码器和交叉注意力——在六个代表性开源模型上进行了首次全面系统分析。通过研究其多阶段推理管道和资源利用模式，我们揭示了这些模式对系统设计的独特影响。此外，我们还深入分析了生产环境中的LMM推理轨迹，发现了独特的工作负载特征，如可变的重尾请求分布、多样的模态组合和突发流量模式。
  我们的核心发现表明，不同LMM推理阶段的性能特征和资源需求差异显著，而跨模态的并发请求会引发显著的性能干扰。为此，我们提出了一种解耦的服务架构，支持每个阶段的独立资源分配和自适应扩展。我们还提出了阶段共置等优化策略，以在满足延迟要求的同时最大化吞吐量和资源利用率。

> Recent advances in generative AI have led to large multi-modal models (LMMs) capable of simultaneously processing inputs of various modalities such as text, images, video, and audio. While these models demonstrate impressive capabilities, efficiently serving them in production environments poses significant challenges due to their complex architectures and heterogeneous resource requirements.
  We present the first comprehensive systems analysis of two prominent LMM architectures, decoder-only and cross-attention, on six representative open-source models. We investigate their multi-stage inference pipelines and resource utilization patterns that lead to unique systems design implications. We also present an in-depth analysis of production LMM inference traces, uncovering unique workload characteristics, including variable, heavy-tailed request distributions, diverse modal combinations, and bursty traffic patterns.
  Our key findings reveal that different LMM inference stages exhibit highly heterogeneous performance characteristics and resource demands, while concurrent requests across modalities lead to significant performance interference. To address these challenges, we propose a decoupled serving architecture that enables independent resource allocation and adaptive scaling for each stage. We further propose optimizations such as stage colocation to maximize throughput and resource utilization while meeting the latency objectives.

[Arxiv](https://arxiv.org/abs/2502.00937)