# Jupiter：在边缘设备上快速、资源高效地协作推理生成式大语言模型

发布时间：2025年04月10日

`LLM应用` `边缘计算` `生成式AI`

> Jupiter: Fast and Resource-Efficient Collaborative Inference of Generative LLMs on Edge Devices

# 摘要

> 生成式大型语言模型（LLMs）凭借其在AI任务中的出色表现引发了广泛关注。传统上部署在云端数据中心的LLMs，如今正逐步向边缘平台迁移，以保护用户数据隐私。然而，边缘设备的有限资源导致推理延迟过长和内存占用过高。现有研究虽通过协作边缘计算突破了设备资源限制，但面临通信开销大和资源利用率低的问题，且仅关注预填充阶段的优化，忽视了生成式LLMs中关键的自回归解码阶段。为此，我们提出了Jupiter——一个快速、可扩展且资源高效的协作边缘AI系统，专为生成式LLMs推理设计。Jupiter采用灵活的流水线架构，并根据预填充和解码阶段的特点进行系统设计。在预填充阶段，Jupiter引入了序列内流水线并行技术和并行规划策略，以提升资源效率；在解码阶段，Jupiter采用了基于大纲的流水线并行解码机制结合推测性解码，进一步加速推理。实验结果表明，Jupiter在多种边缘环境下显著优于现有方法，端到端延迟减少高达26.1倍，同时保持了生成质量。

> Generative large language models (LLMs) have garnered significant attention due to their exceptional capabilities in various AI tasks. Traditionally deployed in cloud datacenters, LLMs are now increasingly moving towards more accessible edge platforms to protect sensitive user data and ensure privacy preservation. The limited computational resources of individual edge devices, however, can result in excessively prolonged inference latency and overwhelmed memory usage. While existing research has explored collaborative edge computing to break the resource wall of individual devices, these solutions yet suffer from massive communication overhead and under-utilization of edge resources. Furthermore, they focus exclusively on optimizing the prefill phase, neglecting the crucial autoregressive decoding phase for generative LLMs. To address that, we propose Jupiter, a fast, scalable, and resource-efficient collaborative edge AI system for generative LLM inference. Jupiter introduces a flexible pipelined architecture as a principle and differentiates its system design according to the differentiated characteristics of the prefill and decoding phases. For prefill phase, Jupiter submits a novel intra-sequence pipeline parallelism and develops a meticulous parallelism planning strategy to maximize resource efficiency; For decoding, Jupiter devises an effective outline-based pipeline parallel decoding mechanism combined with speculative decoding, which further magnifies inference acceleration. Extensive evaluation based on realistic implementation demonstrates that Jupiter remarkably outperforms state-of-the-art approaches under various edge environment setups, achieving up to 26.1x end-to-end latency reduction while rendering on-par generation quality.

[Arxiv](https://arxiv.org/abs/2504.08242)