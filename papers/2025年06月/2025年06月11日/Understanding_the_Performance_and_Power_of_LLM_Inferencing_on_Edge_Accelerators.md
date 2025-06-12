# 探索 LLM 推理在边缘加速器上的性能与潜力

发布时间：2025年06月11日

`LLM应用

论文摘要：大型语言模型（LLMs）在代码生成、机器人导航等众多领域展现出巨大潜力。尽管LLMs通常运行在云端，但关键任务和隐私敏感应用可能需要本地部署开源LLM模型。考虑到LLMs对GPU内存的需求，配备64GB共享GPU-CPU内存的Nvidia Jetson Orin AGX等边缘计算加速器成为理想选择。然而，LLMs在边缘计算加速器上的推理性能尚未得到充分研究。

本研究对NVIDIA Jetson Orin AGX上的LLM推理进行了全面评估，涵盖Meta Llama3.1、Microsoft-Phi2和Deepseek-R1-Qwen等参数从2.7B到32.8B的先进模型。我们深入分析了批次大小、序列长度和量化级别对延迟、吞吐量和困惑度的影响，并通过Orin AGX的多种电源模式进行功耗分析。研究发现揭示了效率、推理速度和资源使用之间的权衡，例如增加序列长度会降低令牌吞吐量，量化会减慢小型LLMs的运行速度。这些成果为优化边缘计算加速器上的LLM服务提供了重要参考，助力实际应用落地。

LLM应用

解释：这篇论文主要探讨了大型语言模型在边缘计算设备上的实际应用，特别是评估和优化其推理性能。它涉及模型部署、性能分析和实际应用优化，因此归类为LLM应用。` `边缘计算` `模型推理`

> Understanding the Performance and Power of LLM Inferencing on Edge Accelerators

# 摘要

> 大型语言模型（LLMs）在代码生成、机器人导航等众多领域展现出巨大潜力。尽管LLMs通常运行在云端，但关键任务和隐私敏感应用可能需要本地部署开源LLM模型。考虑到LLMs对GPU内存的需求，配备64GB共享GPU-CPU内存的Nvidia Jetson Orin AGX等边缘计算加速器成为理想选择。然而，LLMs在边缘计算加速器上的推理性能尚未得到充分研究。

本研究对NVIDIA Jetson Orin AGX上的LLM推理进行了全面评估，涵盖Meta Llama3.1、Microsoft-Phi2和Deepseek-R1-Qwen等参数从2.7B到32.8B的先进模型。我们深入分析了批次大小、序列长度和量化级别对延迟、吞吐量和困惑度的影响，并通过Orin AGX的多种电源模式进行功耗分析。研究发现揭示了效率、推理速度和资源使用之间的权衡，例如增加序列长度会降低令牌吞吐量，量化会减慢小型LLMs的运行速度。这些成果为优化边缘计算加速器上的LLM服务提供了重要参考，助力实际应用落地。

> Large Language Models (LLMs) have demonstrated exceptional benefits to a wide range of domains, for tasks as diverse as code generation and robot navigation. While LLMs are usually served from cloud data centers, mission-critical and privacy-sensitive applications may require local hosting of open LLM models. Given the large GPU memory footprint needed for LLMs, edge accelerators such as Nvidia Jetson Orin AGX with 64GB of shared GPU-CPU RAM are a compelling choice. However, the feasibility and performance of LLM inference on edge accelerators is under-explored. This study presents a detailed evaluation of LLM inference on the NVIDIA Jetson Orin AGX, on four SOTA models ranging from 2.7B to 32.8B parameters, such as Meta Llama3.1, Microsoft-Phi2, Deepseek-R1-Qwen.We investigate the impact of varying batch sizes, sequence lengths, and quantization levels on latency, throughput, and perplexity, and also explore various custom power modes on the Orin AGX to perform power and energy consumption analysis. Our findings offer interesting insights on the trade-offs between efficiency, inference speed and resource use, e.g., increasing the sequence length causes a decrease in token throughput and quantization causes smaller LLMs to be slower. These results can help optimize LLM serving on edge accelerators for practical applications.

[Arxiv](https://arxiv.org/abs/2506.09554)