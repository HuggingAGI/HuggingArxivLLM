# 在移动设备上高效部署视觉语言模型：以一加13R为例

发布时间：2025年07月11日

`LLM应用

理由：这篇论文探讨了视觉语言模型在移动设备上的部署挑战，评估了不同框架的性能表现，属于模型的实际应用和优化，因此归类为LLM应用。` `移动计算` `计算机视觉`

> Efficient Deployment of Vision-Language Models on Mobile Devices: A Case Study on OnePlus 13R

# 摘要

> # 视觉语言模型在移动设备上的部署挑战与框架评估

视觉语言模型（VLMs）为移动设备带来了巨大潜力，但在实际部署中却面临计算资源有限和能耗过高的难题，尤其是在实时应用中。本研究对移动设备上的VLM部署框架进行了全面调研，重点评估了在OnePlus 13R设备上运行LLaVA-1.5 7B、MobileVLM-3B和Imp-v1.5 3B等典型工作负载时的llama.cpp、MLC-Imp和mllm框架表现。

研究通过在OnePlus 13R设备上运行VLMs，从CPU、GPU和NPU利用率、设备温度、推理时间、功耗及用户体验等多个维度对各部署框架进行了全面测试。测试结果揭示了当前框架在性能上的主要瓶颈：CPU资源在生成令牌过程中持续过载，而GPU和NPU加速器则大部分未被有效利用。当GPU被用于图像特征提取时，往往会出现资源饱和，导致设备响应性能下降。

本研究为VLMs的移动部署提供了框架级基准测试、实用性能分析工具，并深入剖析了硬件资源利用率瓶颈，揭示了当前部署框架中CPU过度使用以及GPU和NPU使用效率低下或不稳定的普遍问题。


> Vision-Language Models (VLMs) offer promising capabilities for mobile devices, but their deployment faces significant challenges due to computational limitations and energy inefficiency, especially for real-time applications. This study provides a comprehensive survey of deployment frameworks for VLMs on mobile devices, evaluating llama.cpp, MLC-Imp, and mllm in the context of running LLaVA-1.5 7B, MobileVLM-3B, and Imp-v1.5 3B as representative workloads on a OnePlus 13R. Each deployment framework was evaluated on the OnePlus 13R while running VLMs, with measurements covering CPU, GPU, and NPU utilization, temperature, inference time, power consumption, and user experience. Benchmarking revealed critical performance bottlenecks across frameworks: CPU resources were consistently over-utilized during token generation, while GPU and NPU accelerators were largely unused. When the GPU was used, primarily for image feature extraction, it was saturated, leading to degraded device responsiveness. The study contributes framework-level benchmarks, practical profiling tools, and an in-depth analysis of hardware utilization bottlenecks, highlighting the consistent overuse of CPUs and the ineffective or unstable use of GPUs and NPUs in current deployment frameworks.

[Arxiv](https://arxiv.org/abs/2507.08505)