# # 刻画分布式训练的效率：功耗、性能与热学视角

发布时间：2025年09月12日

`其他` `基础理论`

> Characterizing the Efficiency of Distributed Training: A Power, Performance, and Thermal Perspective

# 摘要

> 大型语言模型（LLMs）的快速扩展使得训练工作负载远超单节点分析的极限，因此亟需深入理解这些模型在大规模多GPU系统中的运行机制。本文针对不同真实工作负载与硬件平台（包括NVIDIA H100/H200及AMD MI250 GPU），对LLM训练展开了全面表征。我们分析了密集型与稀疏型模型在张量、流水线、数据及专家并行等多种并行策略下的表现，并评估了它们对硬件利用率、功耗及热行为的影响，同时验证了激活重计算、计算-通信重叠等优化方法的实际效果。研究发现，性能并非仅由硬件容量的扩展决定：在通信受限场景下，配备数量更少但内存更大的GPU的纵向扩展系统可能优于横向扩展系统，但这需要精心的配置调优；而在其他情况下，横向扩展部署反而能实现更高吞吐量。此外，某些并行组合（如张量与流水线并行）因数据分块效率低下会导致带宽利用率不足；当微批量大小超过特定阈值时，会引发突发执行和峰值功率波动，进而加剧热节流现象。这些发现揭示了训练性能是如何通过硬件、系统拓扑与模型执行之间的复杂交互来塑造的。最后，我们为系统及硬件设计提出建议，旨在提升未来LLM系统与工作负载的可扩展性和可靠性。本项目源代码可访问https://github.com/sitar-lab/CharLLM-PPT。

> The rapid scaling of Large Language Models (LLMs) has pushed training workloads far beyond the limits of single-node analysis, demanding a deeper understanding of how these models behave across large-scale, multi-GPU systems. In this paper, we present a comprehensive characterization of LLM training across diverse real-world workloads and hardware platforms, including NVIDIA H100/H200 and AMD MI250 GPUs. We analyze dense and sparse models under various parallelism strategies -- tensor, pipeline, data, and expert -- and evaluate their effects on hardware utilization, power consumption, and thermal behavior. We further evaluate the effectiveness of optimizations such as activation recomputation and compute-communication overlap. Our findings show that performance is not determined solely by scaling hardware capacity. Scale-up systems with fewer, higher-memory GPUs can outperform scale-out systems in communication-bound regimes, but only under carefully tuned configurations; in other cases, scale-out deployments achieve superior throughput. We also show that certain parallelism combinations, such as tensor with pipeline, lead to bandwidth underutilization due to inefficient data chunking, while increasing microbatch sizes beyond a certain point induces bursty execution and peak power excursions that worsen thermal throttling. These insights reveal how training performance is shaped by complex interactions between hardware, system topology, and model execution. We conclude by offering recommendations for system and hardware design to improve the scalability and reliability of future LLM systems and workloads. The source code of this project is available at https://github.com/sitar-lab/CharLLM-PPT.

[Arxiv](https://arxiv.org/abs/2509.10371)