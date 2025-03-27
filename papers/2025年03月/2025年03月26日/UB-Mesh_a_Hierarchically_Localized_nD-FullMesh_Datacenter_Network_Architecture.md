# UB-Mesh：一种基于层次化本地化n维全连接的数据中心网络架构

发布时间：2025年03月26日

`其他

理由：这篇论文讨论的是AI数据中心网络架构的设计与优化，特别是针对大规模语言模型（LLM）训练中的计算和带宽需求。虽然提到了LLM，但论文的核心内容集中在硬件架构、网络拓扑和系统优化上，属于基础设施层面的改进，不属于Agent、RAG、LLM应用或LLM理论的范畴。因此，将其归类为其他。` `数据中心`

> UB-Mesh: a Hierarchically Localized nD-FullMesh Datacenter Network Architecture

# 摘要

> 随着大规模语言模型（LLMs）的持续扩展，所需的计算能力和带宽也在不断攀升。为应对这一挑战，我们推出了一种全新的AI数据中心网络架构——UB-Mesh，旨在提升可扩展性、性能、成本效益和可用性。与传统数据中心提供对称的节点间带宽不同，UB-Mesh采用了分层本地化的n维全连接网络拓扑结构，通过优先采用短距离直接互连，充分利用了LLM训练中的数据局部性，从而最小化数据传输距离并减少交换机的使用。
    尽管n维全连接拓扑结构在理论上具有诸多优势，但其具体架构设计、物理实现和网络系统优化仍面临新的挑战。在实际构建UB-Mesh时，我们首先设计了基于4维全连接拓扑结构的UB-Mesh-Pod架构。UB-Mesh-Pod通过一系列硬件组件实现，包括专门设计的NPU、CPU、低基数交换机（LRS）、高基数交换机（HRS）、网卡等，这些组件通过一种新颖的统一总线（UB）技术相互连接，实现灵活的I/O带宽分配和硬件资源共享。在网络系统优化方面，我们提出了一种名为All-Path-Routing（APR）的先进路由机制，以有效管理数据流量。这些优化措施，结合拓扑感知的性能增强和64+1备用设计等 robust 可靠性措施，使得UB-Mesh在成本效益上比传统Clos架构高出2.04倍，网络可用性提升7.2%，并在各种LLM训练任务中实现95%以上的线性扩展性。

> As the Large-scale Language Models (LLMs) continue to scale, the requisite computational power and bandwidth escalate. To address this, we introduce UB-Mesh, a novel AI datacenter network architecture designed to enhance scalability, performance, cost-efficiency and availability. Unlike traditional datacenters that provide symmetrical node-to-node bandwidth, UB-Mesh employs a hierarchically localized nD-FullMesh network topology. This design fully leverages the data locality of LLM training, prioritizing short-range, direct interconnects to minimize data movement distance and reduce switch usage.
  Although UB-Mesh's nD-FullMesh topology offers several theoretical advantages, its concrete architecture design, physical implementation and networking system optimization present new challenges. For the actual construction of UB-Mesh, we first design the UB-Mesh-Pod architecture, which is based on a 4D-FullMesh topology. UB-Mesh-Pod is implemented via a suite of hardware components that serve as the foundational building blocks, including specifically-designed NPU, CPU, Low-Radix-Switch (LRS), High-Radix-Switch (HRS), NICs and others. These components are interconnected via a novel Unified Bus (UB) technique, which enables flexible IO bandwidth allocation and hardware resource pooling. For networking system optimization, we propose advanced routing mechanism named All-Path-Routing (APR) to efficiently manage data traffic. These optimizations, combined with topology-aware performance enhancements and robust reliability measures like 64+1 backup design, result in 2.04x higher cost-efficiency, 7.2% higher network availability compared to traditional Clos architecture and 95%+ linearity in various LLM training tasks.

[Arxiv](https://arxiv.org/abs/2503.20377)