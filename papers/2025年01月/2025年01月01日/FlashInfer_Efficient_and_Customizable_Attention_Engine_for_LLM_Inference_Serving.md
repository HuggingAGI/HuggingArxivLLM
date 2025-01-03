# FlashInfer: 高效且可定制的LLM推理注意力引擎

发布时间：2025年01月01日

`LLM应用

理由：这篇论文主要介绍了一个名为FlashInfer的注意力引擎，该引擎专为大型语言模型（LLMs）服务设计，旨在提高LLM推理的效率和性能。论文讨论了如何通过优化KV缓存存储、提供可定制的注意力模板以及动态调度算法来提升LLM服务的性能。这些内容直接涉及到LLM在实际应用中的性能优化和部署，因此应归类为LLM应用。` `高性能计算`

> FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving

# 摘要

> # 摘要
基于注意力机制的Transformer是大型语言模型（LLMs）的核心。随着模型规模的扩大，高效的GPU注意力内核成为高吞吐量和低延迟推理的关键。多样化的LLM应用需要灵活且高性能的注意力解决方案。我们推出了FlashInfer：一个可定制且高效的注意力引擎，专为LLM服务设计。FlashInfer通过块稀疏格式和可组合格式优化KV缓存存储，减少内存访问冗余。它还提供可定制的注意力模板，支持即时（JIT）编译以适应不同场景。此外，FlashInfer的负载均衡调度算法能够动态适应用户请求，同时兼容需要静态配置的CUDAGraph。FlashInfer已集成到SGLang、vLLM和MLC-Engine等主流LLM服务框架中。全面的内核级和端到端评估显示，FlashInfer在各种推理场景下显著提升了性能：与现有最佳LLM服务方案相比，FlashInfer在LLM服务基准测试中减少了29-69%的令牌间延迟，长上下文推理中减少了28-30%的延迟，并行生成LLM服务中提升了13-17%的速度。

> Transformers, driven by attention mechanisms, form the foundation of large language models (LLMs). As these models scale up, efficient GPU attention kernels become essential for high-throughput and low-latency inference. Diverse LLM applications demand flexible and high-performance attention solutions. We present FlashInfer: a customizable and efficient attention engine for LLM serving. FlashInfer tackles KV-cache storage heterogeneity using block-sparse format and composable formats to optimize memory access and reduce redundancy. It also offers a customizable attention template, enabling adaptation to various settings through Just-In-Time (JIT) compilation. Additionally, FlashInfer's load-balanced scheduling algorithm adjusts to dynamism of user requests while maintaining compatibility with CUDAGraph which requires static configuration. FlashInfer have been integrated into leading LLM serving frameworks like SGLang, vLLM and MLC-Engine. Comprehensive kernel-level and end-to-end evaluations demonstrate FlashInfer's ability to significantly boost kernel performance across diverse inference scenarios: compared to state-of-the-art LLM serving solutions, FlashInfer achieve 29-69% inter-token-latency reduction compared to compiler backends for LLM serving benchmark, 28-30% latency reduction for long-context inference, and 13-17% speedup for LLM serving with parallel generation.

[Arxiv](https://arxiv.org/abs/2501.01005)