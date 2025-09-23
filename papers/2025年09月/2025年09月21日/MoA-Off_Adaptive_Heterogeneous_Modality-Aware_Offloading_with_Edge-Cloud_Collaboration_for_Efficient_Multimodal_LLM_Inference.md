# MoA-Off：通过边缘-云协作的自适应异构模态感知卸载实现高效多模态LLM推理

发布时间：2025年09月21日

`LLM应用` `工业与制造`

> MoA-Off: Adaptive Heterogeneous Modality-Aware Offloading with Edge-Cloud Collaboration for Efficient Multimodal LLM Inference

# 摘要

> 多模态大型语言模型（MLLMs）虽能实现强大的跨模态推理，却带来了显著的计算与延迟负担，给资源受限环境下的部署带来了严峻挑战。为此，本文提出MoA-Off——一种基于边缘-云协作的自适应异构模态感知卸载框架，旨在实现高效的MLLM推理。该框架包含一个轻量级异构模态感知模块，通过多维特征分析来估计异构输入的复杂度；此外，还提出了一种自适应边缘-云协作卸载策略，能根据模态感知复杂度分数和实时系统状态，在边缘与云之间动态调度工作负载。实验结果显示，与传统方法相比，MoA-Off在保持精度竞争力的同时，可将延迟降低30%以上，资源开销减少30%-65%。

> Multimodal large language models (MLLMs) enable powerful cross-modal inference but impose significant computational and latency burdens, posing severe challenges for deployment in resource-constrained environments. In this paper, we propose MoA-Off, an adaptive heterogeneous modality-aware offloading framework with edge-cloud collaboration for efficient MLLM inference. MoA-Off introduces a lightweight heterogeneous modality-aware module that estimates the complexity of heterogeneous inputs through multi-dimensional feature analysis. Then, an adaptive edge-cloud collaborative offloading strategy is proposed that dynamically schedules workloads between edge and cloud based on modality-aware complexity scores and real-time system states. The experimental results demonstrate that MoA-Off can achieve over 30% reduction in latency and 30%-65% decrease in resource overhead while maintaining competitive accuracy compared to traditional approaches.

[Arxiv](https://arxiv.org/abs/2509.16995)