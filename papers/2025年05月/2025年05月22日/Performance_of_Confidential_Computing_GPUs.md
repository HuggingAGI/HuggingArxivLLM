# # 机密计算GPU性能表现

发布时间：2025年05月22日

`LLM应用

理由：这篇论文研究了大型语言模型在保密环境下的推理性能，探讨了模型切换和加密对性能的影响，属于模型的应用层面优化。` `人工智能` `数据安全`

> Performance of Confidential Computing GPUs

# 摘要

> 本研究聚焦于在保密 GPU 上进行推理时的性能表现，包括延迟、吞吐量等关键指标。我们采用一台搭载 NVIDIA H100 GPU 的虚拟机，通过调整流量模式与调度策略，对多个大型语言模型（LLMs）进行了松弛批量推理实验，重点考察了模型在内存中动态加载与卸载的场景。实验通过模拟不同流量负载、分布模式、调度策略及服务级别协议（SLA）要求，再现了多样化的实际应用场景。研究发现，在需要频繁模型切换的场景下，保密与非保密环境的性能存在显著差异。具体而言，无保密模式下的松弛批量推理延迟比保密模式低 20-30%，SLA 达成率提升 15-20%。此外，无保密场景的吞吐量比保密模式高出 45-70%，GPU 利用率也高出约 50%。总体来看，保密环境的性能表现逊于无保密场景，主要归因于保密环境下加载模型时额外的加密与解密开销。

> This work examines latency, throughput, and other metrics when performing inference on confidential GPUs. We explore different traffic patterns and scheduling strategies using a single Virtual Machine with one NVIDIA H100 GPU, to perform relaxed batch inferences on multiple Large Language Models (LLMs), operating under the constraint of swapping models in and out of memory, which necessitates efficient control. The experiments simulate diverse real-world scenarios by varying parameters such as traffic load, traffic distribution patterns, scheduling strategies, and Service Level Agreement (SLA) requirements. The findings provide insights into the differences between confidential and non-confidential settings when performing inference in scenarios requiring active model swapping. Results indicate that in No-CC mode, relaxed batch inference with model swapping latency is 20-30% lower than in confidential mode. Additionally, SLA attainment is 15-20% higher in No-CC settings. Throughput in No-CC scenarios surpasses that of confidential mode by 45-70%, and GPU utilization is approximately 50% higher in No-CC environments. Overall, performance in the confidential setting is inferior to that in the No-CC scenario, primarily due to the additional encryption and decryption overhead required for loading models onto the GPU in confidential environments.

[Arxiv](https://arxiv.org/abs/2505.16501)