# InfinitePOD：利用光路交换收发器为LLM打造数据中心级高带宽域

发布时间：2025年02月06日

`其他

理由：这篇论文主要讨论的是大型语言模型（LLM）训练中的硬件架构设计，特别是高带宽域（HBD）的创新架构InfinitePOD。虽然论文提到了LLM的训练，但其核心内容集中在硬件架构的设计、故障恢复能力、成本优化等方面，属于计算机体系结构和硬件优化的范畴，而不是直接讨论LLM的理论、应用、Agent或RAG。因此，将其分类为“其他”更为合适。` `数据中心` `高性能计算`

> InfinitePOD: Building Datacenter-Scale High-Bandwidth Domain for LLM with Optical Circuit Switching Transceivers

# 摘要

> # 摘要
扩展大型语言模型（LLM）训练依赖于多维并行性，其中高带宽域（HBDs）对通信密集型并行性（如张量并行性（TP）和专家并行性（EP））至关重要。然而，现有HBD架构在可扩展性、成本和故障恢复能力方面存在根本性限制：以交换机为中心的HBD（如NVL-72）扩展成本高昂，而以GPU为中心的HBD（如TPUv3/Dojo）则面临严重的故障传播问题。TPUv4等交换机-GPU混合HBD采用光路交换机作为折衷方案，但故障爆炸半径在立方体级别（如64个TPU）仍然较大。
我们提出了InfinitePOD，一种创新的以收发器为中心的HBD架构，利用光路交换（OCS）在收发器级别统一连接和动态切换。通过在每个收发器中嵌入OCS，InfinitePOD实现了可重新配置的点对多点连接，使拓扑能够适应可变大小的环。这种设计具有以下优势：i）数据中心范围内的可扩展性，且不会导致成本爆炸；ii）通过将故障隔离到单个节点实现故障恢复能力；iii）无故障GPU的完全带宽利用率。关键创新包括基于硅光子（SiPh）的低成本OCS收发器（OCSTrx）、与节点内/节点间通信共同设计的可重新配置k跳环拓扑，以及最大化GPU利用率同时最小化跨ToR数据中心网络流量的HBD-DCN编排算法。评估结果显示，InfinitePOD的成本仅为NVL-72的31%，GPU浪费率接近零（比NVL-72和TPUv4低一个数量级），在节点故障率低于7%时跨ToR流量接近零，并且与NVIDIA DGX（每节点8个GPU）相比，模型FLOPs利用率提高了3.37倍。

> Scaling Large Language Model (LLM) training relies on multi-dimensional parallelism, where High-Bandwidth Domains (HBDs) are critical for communication-intensive parallelism like Tensor Parallelism (TP) and Expert Parallelism (EP). However, existing HBD architectures face fundamental limitations in scalability, cost, and fault resiliency: switch-centric HBDs (e.g., NVL-72) incur prohibitive scaling costs, while GPU-centric HBDs (e.g., TPUv3/Dojo) suffer from severe fault propagation. Switch-GPU hybrid HBDs such as TPUv4 takes a middle-ground approach by leveraging Optical Circuit Switches, but the fault explosion radius remains large at the cube level (e.g., 64 TPUs).
  We propose InfinitePOD, a novel transceiver-centric HBD architecture that unifies connectivity and dynamic switching at the transceiver level using Optical Circuit Switching (OCS). By embedding OCS within each transceiver, InfinitePOD achieves reconfigurable point-to-multipoint connectivity, allowing the topology to adapt into variable-size rings. This design provides: i) datacenter-wide scalability without cost explosion; ii) fault resilience by isolating failures to a single node, and iii) full bandwidth utilization for fault-free GPUs. Key innovations include a Silicon Photonic (SiPh) based low-cost OCS transceiver (OCSTrx), a reconfigurable k-hop ring topology co-designed with intra-/inter-node communication, and an HBD-DCN orchestration algorithm maximizing GPU utilization while minimizing cross-ToR datacenter network traffic. The evaluation demonstrates that InfinitePOD achieves 31% of the cost of NVL-72, near-zero GPU waste ratio (over one order of magnitude lower than NVL-72 and TPUv4), near-zero cross-ToR traffic when node fault ratios under 7%, and improves Model FLOPs Utilization by 3.37x compared to NVIDIA DGX (8 GPUs per Node).

[Arxiv](https://arxiv.org/abs/2502.03885)