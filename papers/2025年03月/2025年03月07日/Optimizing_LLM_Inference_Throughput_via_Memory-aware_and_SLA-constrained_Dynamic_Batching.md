# # 优化 LLM 推理吞吐量的内存感知与 SLA 约束动态分批方法
本研究提出了一种基于内存感知和 SLA 约束的动态分批方法，旨在优化大型语言模型 (LLM) 的推理吞吐量。

发布时间：2025年03月07日

`LLM应用` `云计算` `推理服务`

> Optimizing LLM Inference Throughput via Memory-aware and SLA-constrained Dynamic Batching

# 摘要

> 随着大规模语言模型（LLMs）的广泛应用，亟需一种既能实现高吞吐量又能保证低延迟的推理服务系统。然而，将具有数百亿参数的LLMs部署在内存受限的GPU上时，静态批处理方法的局限性逐渐显现。现有推理服务系统往往将批处理大小固定为超参数，无法实时适应系统条件的变化。针对这一问题，本文提出了一种动态批处理方法，通过持续监控内存利用率并遵循服务级别协议（SLA），实现实时批处理大小配置的灵活调整。该方法包含两个核心组件：基于内存感知的批处理调度器，用于动态分配GPU资源；以及延迟反馈机制，在SLA约束下优化解码过程。数值实验结果表明，与传统静态批处理方法相比，该方法在吞吐量上提升了8%至28%，容量提升了22%，同时保持了与现有推理基础设施的完全兼容性。这些结果充分展示了动态批处理在平衡计算效率和服务质量要求方面的能力，尤其适用于当代LLM的部署场景。本研究的源代码已在GitHub上公开，地址为https://github.com/KevinLee1110/dynamic-batching。

> The increasing adoption of large language models (LLMs) necessitates inference serving systems that can deliver both high throughput and low latency. Deploying LLMs with hundreds of billions of parameters on memory-constrained GPUs exposes significant limitations in static batching methods. Current inference serving systems often treat batch sizes as fixed hyper-parameters, hindering real-time adaptation to varying system conditions. In this paper, we propose a dynamic batching method that continuously monitors memory utilization and adheres to service-level agreements (SLAs) to enable real-time batch size configuration adjustment. The method comprises two core components: a memory-aware batch scheduler that dynamically allocates GPU resources and a latency feedback mechanism that optimizes decoding processes under SLA constraints. The numerical experiments demonstrate throughput gains of 8% to 28% and capacity improvements of 22% compared to traditional static batching methods, while maintaining full compatibility with existing inference infrastructure. These results highlight the effectiveness of dynamic batching in balancing computational efficiency and quality-of-service requirements for contemporary LLM deployment scenarios. The source code of this work is publicly available at https://github.com/KevinLee1110/dynamic-batching.

[Arxiv](https://arxiv.org/abs/2503.05248)