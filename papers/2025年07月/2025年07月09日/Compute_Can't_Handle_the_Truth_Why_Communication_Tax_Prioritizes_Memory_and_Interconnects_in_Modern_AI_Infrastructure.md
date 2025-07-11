# 算力难言真相：通信开销为何偏爱内存与互连

发布时间：2025年07月09日

`其他` `AI基础设施` `数据中心`

> Compute Can't Handle the Truth: Why Communication Tax Prioritizes Memory and Interconnects in Modern AI Infrastructure

# 摘要

> 现代AI工作负载，如大型语言模型（LLMs）和检索增强生成（RAG），对内存、通信带宽和资源灵活性提出了严苛需求。传统以GPU为中心的架构因GPU间通信开销日益增加而难以扩展。本报告介绍关键AI概念，揭示Transformer如何革新LLMs中的数据表示方式。我们深入分析大规模AI硬件和数据中心设计，识别分层系统中的可扩展性瓶颈。为解决这些问题，我们提出了一种基于计算快速链接（CXL）的模块化数据中心架构，支持内存、计算和加速器的分离式扩展。我们进一步探索了优化的加速器互连技术——统称为XLink（如UALink、NVLink、NVLink融合）——并提出了一种混合CXL-over-XLink设计，以减少长距离数据传输同时保持内存一致性。我们还提出了一种结合本地内存和共享内存的分层内存模型，并评估了轻量级CXL实现、高带宽内存（HBM）和硅光子技术以实现高效扩展。我们的评估结果表明，该架构在AI基础设施的可扩展性、吞吐量和灵活性方面均有显著提升。

> Modern AI workloads such as large language models (LLMs) and retrieval-augmented generation (RAG) impose severe demands on memory, communication bandwidth, and resource flexibility. Traditional GPU-centric architectures struggle to scale due to growing inter-GPU communication overheads. This report introduces key AI concepts and explains how Transformers revolutionized data representation in LLMs. We analyze large-scale AI hardware and data center designs, identifying scalability bottlenecks in hierarchical systems. To address these, we propose a modular data center architecture based on Compute Express Link (CXL) that enables disaggregated scaling of memory, compute, and accelerators. We further explore accelerator-optimized interconnects-collectively termed XLink (e.g., UALink, NVLink, NVLink Fusion)-and introduce a hybrid CXL-over-XLink design to reduce long-distance data transfers while preserving memory coherence. We also propose a hierarchical memory model that combines local and pooled memory, and evaluate lightweight CXL implementations, HBM, and silicon photonics for efficient scaling. Our evaluations demonstrate improved scalability, throughput, and flexibility in AI infrastructure.

[Arxiv](https://arxiv.org/abs/2507.07223)