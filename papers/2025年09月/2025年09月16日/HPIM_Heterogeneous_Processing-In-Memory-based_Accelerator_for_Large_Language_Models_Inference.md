# HPIM：异构存内处理（Processing-In-Memory）基大型语言模型推理加速器

发布时间：2025年09月16日

`其他` `基础理论`

> HPIM: Heterogeneous Processing-In-Memory-based Accelerator for Large Language Models Inference

# 摘要

> 大型语言模型（LLMs）的部署面临诸多挑战：其庞大的内存占用、较低的算术强度以及严苛的延迟要求，尤其是在自回归解码阶段，这些问题尤为突出。传统以计算为核心的加速器（如GPU）在这类内存密集型任务中，普遍存在资源利用率低下和内存带宽瓶颈的问题。为突破这些固有局限，我们提出了HPIM——首个以内存为核心的异构存内处理（PIM）加速器，它集成了专为LLM推理打造的SRAM-PIM与HBM-PIM子系统。HPIM采用软硬件协同设计思路，将专用编译器框架与异构硬件架构深度融合。它能根据工作负载特性智能分配任务：对延迟敏感的注意力操作被分配至SRAM-PIM子系统，以发挥其超低延迟和高计算灵活性优势；权重密集型的GEMV计算则交由HBM-PIM子系统处理，充分利用其高内部带宽和大容量存储能力。此外，HPIM在SRAM-PIM与HBM-PIM子系统间采用紧密耦合的流水线策略，最大化令牌内并行度，有效缓解了自回归解码阶段的串行依赖问题。基于周期精确模拟器的全面评估显示，HPIM性能远超当前最先进的加速器，与NVIDIA A100 GPU相比，峰值加速比可达22.8倍。同时，HPIM相较于现有基于PIM的加速器也展现出更优性能，充分证明了其作为加速大规模LLM推理的高实用性、高可扩展解决方案的巨大潜力。

> The deployment of large language models (LLMs) presents significant challenges due to their enormous memory footprints, low arithmetic intensity, and stringent latency requirements, particularly during the autoregressive decoding stage. Traditional compute-centric accelerators, such as GPUs, suffer from severe resource underutilization and memory bandwidth bottlenecks in these memory-bound workloads. To overcome these fundamental limitations, we propose HPIM, the first memory-centric heterogeneous Processing-In-Memory (PIM) accelerator that integrates SRAM-PIM and HBM-PIM subsystems designed specifically for LLM inference. HPIM employs a software-hardware co-design approach that combines a specialized compiler framework with a heterogeneous hardware architecture. It intelligently partitions workloads based on their characteristics: latency-critical attention operations are mapped to the SRAM-PIM subsystem to exploit its ultra-low latency and high computational flexibility, while weight-intensive GEMV computations are assigned to the HBM-PIM subsystem to leverage its high internal bandwidth and large storage capacity. Furthermore, HPIM introduces a tightly coupled pipeline strategy across SRAM-PIM and HBM-PIM subsystems to maximize intra-token parallelism, thereby significantly mitigating serial dependency of the autoregressive decoding stage. Comprehensive evaluations using a cycle-accurate simulator demonstrate that HPIM significantly outperforms state-of-the-art accelerators, achieving a peak speedup of up to 22.8x compared to the NVIDIA A100 GPU. Moreover, HPIM exhibits superior performance over contemporary PIM-based accelerators, highlighting its potential as a highly practical and scalable solution for accelerating large-scale LLM inference.

[Arxiv](https://arxiv.org/abs/2509.12993)