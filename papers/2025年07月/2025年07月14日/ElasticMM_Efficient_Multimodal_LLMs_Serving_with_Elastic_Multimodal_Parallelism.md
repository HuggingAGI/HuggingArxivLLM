# ElasticMM: 基于弹性多模态并行的高效多模态大语言模型服务

发布时间：2025年07月14日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）的推理效率问题，并提出了一种新的服务范式和系统来优化其性能。研究重点在于如何更高效地部署和使用MLLMs，属于应用层面的创新。` `多模态处理` `云计算服务`

> ElasticMM: Efficient Multimodal LLMs Serving with Elastic Multimodal Parallelism

# 摘要

> 多模态大型语言模型（MLLMs）通过整合特征提取器和投影模块，将大型语言模型（LLMs）的能力扩展至图像、视频和音频处理。然而，这些新增组件与复杂的推理管道和异构工作负载相结合，带来了显著的推理开销，使得高效服务MLLMs成为一项重大挑战。现有的紧耦合服务架构难以区分混合请求类型，也无法根据不同的推理阶段灵活调整并行策略，导致首次生成Token响应时间（TTFT）延迟增加，资源利用率低下。

为了解决这一问题，我们提出了弹性多模态并行（EMP），这是一种能够弹性适应不同请求类型和推理阶段资源异质性的新型服务范式。基于EMP，我们开发了ElasticMM，一个多模态大语言模型服务系统，它具备以下三大核心功能：（1）通过一个多模态感知的负载均衡器，将请求动态分配到独立的模态组；（2）通过弹性分区调度，解耦推理阶段并支持并行策略调整和自适应扩展；（3）通过统一的多模态前缀缓存和非阻塞编码，显著提升推理效率。

在多样化的现实数据集上进行的实验表明，ElasticMM在性能上超越了现有最优（SOTA）服务系统。它将TTFT延迟降低了4.2倍，同时在满足服务级别目标（SLOs）的前提下，实现了3.2至4.5倍的吞吐量提升。

> Multimodal large language models (MLLMs) extend LLMs to handle images, videos, and audio by incorporating feature extractors and projection modules. However, these additional components -- combined with complex inference pipelines and heterogeneous workloads -- introduce significant inference overhead. Therefore, efficiently serving MLLMs remains a major challenge. Current tightly coupled serving architectures struggle to distinguish between mixed request types or adapt parallelism strategies to different inference stages, leading to increased time-to-first-token (TTFT) latency and poor resource utilization. To address this, we propose Elastic Multimodal Parallelism (EMP), a new serving paradigm that elastically adapts to resource heterogeneity across request types and inference stages. Building upon EMP, we develop ElasticMM, an MLLM serving system that (1) separates requests into independent modality groups with dynamic resource allocation via a modality-aware load balancer; (2) decouples inference stages and enables parallelism adjustment and adaptive scaling via elastic partition scheduling; and (3) improves inference efficiency through unified multimodal prefix caching and non-blocking encoding. Experiments on diverse real-world datasets show that ElasticMM outperforms state-of-the-art (SOTA) serving systems, reducing TTFT by up to 4.2x and achieving 3.2-4.5x higher throughput while meeting service-level objectives (SLOs).

[Arxiv](https://arxiv.org/abs/2507.10069)