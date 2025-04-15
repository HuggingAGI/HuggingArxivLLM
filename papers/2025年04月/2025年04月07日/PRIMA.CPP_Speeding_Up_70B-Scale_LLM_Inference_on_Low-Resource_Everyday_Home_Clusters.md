# # PRIMA.CPP：加速700亿参数级LLM推理，于低资源日常家用计算集群环境实现高效运行

发布时间：2025年04月07日

`LLM应用` `家庭设备` `分布式计算`

> PRIMA.CPP: Speeding Up 70B-Scale LLM Inference on Low-Resource Everyday Home Clusters

# 摘要

> DeepSeek-R1和QwQ-32B的问世突破了家庭设备运行前沿大语言模型（LLMs）的性能瓶颈。尽管消费级硬件性能提升，模型量化技术也在进步，但现有端侧方案仍需GPU集群、大内存/显存和高带宽，远超普通家庭集群能力。本文介绍的prima.cpp是一款分布式推理系统，它能在日常家庭设备上，利用CPU/GPU混合计算、低内存/显存、Wi-Fi和跨平台支持，运行700亿参数规模模型。通过mmap管理模型权重，并采用带预取的环形流水并行机制隐藏磁盘加载延迟。建模计算、通信、磁盘、内存（及其管理行为）和操作系统的异构性，它能将模型层最优分配至每台设备的CPU和GPU，进一步降低令牌延迟。本文提出Halda算法解决这一NP难的分配问题。我们在普通四节点家庭集群上评估prima.cpp。在300亿参数以上模型上，其性能优于llama.cpp、exo和dllama，同时将内存压力控制在6%以下。这使得前沿300亿至700亿参数模型，如Llama 3、DeepSeek-R1、Qwen 2.5和QwQ，能够运行在家庭助手设备上，让先进AI真正走进千家万户。代码已开源，地址为https://github.com/Lizonghang/prima.cpp。

> Emergency of DeepSeek R1 and QwQ 32B have broken through performance barriers for running frontier large language models (LLMs) on home devices. While consumer hardware is getting stronger and model quantization is improving, existing end-side solutions still demand GPU clusters, large RAM/VRAM, and high bandwidth, far beyond what a common home cluster can handle. This paper introduces prima.cpp, a distributed inference system that runs 70B-scale models on everyday home devices using a mix of CPU/GPU, low RAM/VRAM, Wi-Fi, and cross-platform support. It uses mmap to manage model weights and introduces piped-ring parallelism with prefetching to hide disk loading. By modeling heterogeneity in computation, communication, disk, memory (and its management behavior), and OS, it optimally assigns model layers to each device's CPU and GPU, further reducing token latency. An elegant algorithm named Halda is proposed to solve this NP-hard assignment problem. We evaluate prima.cpp on a common four-node home cluster. It outperforms llama.cpp, exo, and dllama on 30B+ models while keeping memory pressure below 6%. This brings frontier 30B-70B models, such as Llama 3, DeepSeek R1, Qwen 2.5, and QwQ to home assistants, making advanced AI truly accessible to individuals. The code is open source and available at https://github.com/Lizonghang/prima.cpp.

[Arxiv](https://arxiv.org/abs/2504.08791)