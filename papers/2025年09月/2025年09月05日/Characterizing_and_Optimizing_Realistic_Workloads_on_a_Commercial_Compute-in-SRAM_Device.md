# 商用计算型SRAM器件实际工作负载的表征与优化

发布时间：2025年09月05日

`RAG` `基础理论`

> Characterizing and Optimizing Realistic Workloads on a Commercial Compute-in-SRAM Device

# 摘要

> 存内计算（Compute-in-SRAM）架构为各类数据密集型应用带来了提升性能与能效的新希望。但以往的评估多依赖模拟器或小型原型，难以充分展现其实际应用潜力。为此，我们对商用存内计算设备GSI APU在真实工作负载下的性能与能耗展开了全面分析，通过与CPU、GPU等成熟架构对比，量化了其能效优势与性能潜力。同时，我们还为通用存内计算设备构建了分析框架，通过建模性能权衡揭示核心优化准则，为程序优化提供指导。
  要充分发挥存储-计算紧密集成架构的细粒度并行能力，离不开高效的数据管理。为此，我们提出三项优化策略：通信感知约简映射、合并DMA及广播友好数据布局。将这些优化应用于大型语料库（10GB–200GB）的检索增强生成（RAG）任务后，存内计算系统的检索速度较优化后的CPU基准提升4.8–6.6倍，端到端RAG延迟缩短1.1–1.8倍。实验中，共享片外内存带宽通过模拟HBM建模，其余组件则基于真实存内计算设备实测。值得关注的是，该系统在RAG任务中性能媲美NVIDIA A6000 GPU，能耗却降低54.4–117.9倍，能效优势显著。这些结果验证了存内计算在复杂实际场景中的实用价值，也为该技术的进一步发展指明了方向。

> Compute-in-SRAM architectures offer a promising approach to achieving higher performance and energy efficiency across a range of data-intensive applications. However, prior evaluations have largely relied on simulators or small prototypes, limiting the understanding of their real-world potential. In this work, we present a comprehensive performance and energy characterization of a commercial compute-in-SRAM device, the GSI APU, under realistic workloads. We compare the GSI APU against established architectures, including CPUs and GPUs, to quantify its energy efficiency and performance potential. We introduce an analytical framework for general-purpose compute-in-SRAM devices that reveals fundamental optimization principles by modeling performance trade-offs, thereby guiding program optimizations.
  Exploiting the fine-grained parallelism of tightly integrated memory-compute architectures requires careful data management. We address this by proposing three optimizations: communication-aware reduction mapping, coalesced DMA, and broadcast-friendly data layouts. When applied to retrieval-augmented generation (RAG) over large corpora (10GB--200GB), these optimizations enable our compute-in-SRAM system to accelerate retrieval by 4.8$\times$--6.6$\times$ over an optimized CPU baseline, improving end-to-end RAG latency by 1.1$\times$--1.8$\times$. The shared off-chip memory bandwidth is modeled using a simulated HBM, while all other components are measured on the real compute-in-SRAM device. Critically, this system matches the performance of an NVIDIA A6000 GPU for RAG while being significantly more energy-efficient (54.4$\times$-117.9$\times$ reduction). These findings validate the viability of compute-in-SRAM for complex, real-world applications and provide guidance for advancing the technology.

[Arxiv](https://arxiv.org/abs/2509.05451)