# EdgeLoRA：面向边缘设备的高效多租户LLM服务系统

发布时间：2025年07月02日

`LLM应用` `边缘计算` `人工智能`

> EdgeLoRA: An Efficient Multi-Tenant LLM Serving System on Edge Devices

# 摘要

> 大型语言模型（LLMs）因其广泛的应用场景而备受关注。通过参数高效适配器（如低秩适配 LoRA）对 LLMs 进行微调，使模型能够高效适应下游任务，而无需大量重新训练。在多租户边缘设备上部署微调后的 LLMs 具有显著优势，包括更低的延迟、更强的隐私保护以及个性化的响应能力。然而，在资源受限的边缘设备上高效运行 LLMs 面临诸多挑战：不同任务下适配器选择的复杂性、频繁适配器切换带来的内存开销，以及多租户环境下串行处理请求导致的计算资源利用率低下和延迟增加问题。本文提出了一种名为 EdgeLoRA 的高效系统，专为多租户环境下的 LLM 边缘设备运行而设计。EdgeLoRA 的三大创新包括：(1) 自适应适配器选择机制，简化适配器配置流程；(2) 异构内存管理，通过智能适配器缓存和池化优化内存操作；(3) 批量 LoRA 推理，实现高效批量处理以显著降低计算延迟。基于 Llama3.1-8B 模型的全面评估显示，与现有方法（llama.cpp）相比，EdgeLoRA 在延迟和吞吐量方面均有显著提升。实验结果表明，EdgeLoRA 最高可实现 4 倍的吞吐量提升。更令人瞩目的是，它能同时支持多个数量级更多的适配器运行。这些结果充分展现了 EdgeLoRA 在多租户场景下变革 LLM 边缘部署的潜力，为资源受限环境提供了可扩展且高效的解决方案。


> Large Language Models (LLMs) have gained significant attention due to their versatility across a wide array of applications. Fine-tuning LLMs with parameter-efficient adapters, such as Low-Rank Adaptation (LoRA), enables these models to efficiently adapt to downstream tasks without extensive retraining. Deploying fine-tuned LLMs on multi-tenant edge devices offers substantial benefits, such as reduced latency, enhanced privacy, and personalized responses. However, serving LLMs efficiently on resource-constrained edge devices presents critical challenges, including the complexity of adapter selection for different tasks and memory overhead from frequent adapter swapping. Moreover, given the multiple requests in multi-tenant settings, processing requests sequentially results in underutilization of computational resources and increased latency. This paper introduces EdgeLoRA, an efficient system for serving LLMs on edge devices in multi-tenant environments. EdgeLoRA incorporates three key innovations: (1) an adaptive adapter selection mechanism to streamline the adapter configuration process; (2) heterogeneous memory management, leveraging intelligent adapter caching and pooling to mitigate memory operation overhead; and (3) batch LoRA inference, enabling efficient batch processing to significantly reduce computational latency. Comprehensive evaluations using the Llama3.1-8B model demonstrate that EdgeLoRA significantly outperforms the status quo (i.e., llama.cpp) in terms of both latency and throughput. The results demonstrate that EdgeLoRA can achieve up to a 4 times boost in throughput. Even more impressively, it can serve several orders of magnitude more adapters simultaneously. These results highlight EdgeLoRA's potential to transform edge deployment of LLMs in multi-tenant scenarios, offering a scalable and efficient solution for resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2507.01438)