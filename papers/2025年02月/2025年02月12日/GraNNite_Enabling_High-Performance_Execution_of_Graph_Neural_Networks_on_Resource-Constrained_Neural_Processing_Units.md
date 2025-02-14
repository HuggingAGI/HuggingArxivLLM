# # GraNNite：在资源受限的神经处理单元上实现高性能图神经网络

发布时间：2025年02月12日

`其他` `边缘计算` `图神经网络`

> GraNNite: Enabling High-Performance Execution of Graph Neural Networks on Resource-Constrained Neural Processing Units

# 摘要

> 图神经网络（GNNs）在图结构数据学习中发挥着关键作用，广泛应用于网络分析、推荐系统和语音分析等领域。将其部署在边缘设备如PC和笔记本电脑上，能够显著提升实时处理能力、隐私保护和对云端的独立性。GNNs不仅助力大型语言模型（LLMs）的检索增强生成（RAG），还能支持基于事件的视觉任务。然而，在资源受限的设备上，不规则内存访问、稀疏性和动态结构导致了高延迟和高能耗。尽管现代边缘处理器集成了CPU、GPU和NPU，但针对数据并行任务设计的NPU在处理不规则的GNN计算时表现不佳。为此，我们提出了GraNNite——首个硬件感知框架，通过结构化的三步方法优化图神经网络在商业现货（COTS）最优DNN加速器上的执行。首先，通过GraphSplit实现工作负载分配和StaGr进行静态聚合，GrAd和NodePad则负责处理动态图。其次，通过EffOp提升控制密集型任务性能，GraSp用于稀疏性优化，图卷积优化PreG、SymG和CacheG则减少冗余和内存传输。最后，在质量与效率之间取得平衡，其中QuantGr应用INT8量化，GrAx1、GrAx2和GrAx3分别加速注意力、广播加法和SAGE-max聚合。实验结果显示，在Intel Core Ultra AI电脑上，GraNNite相比默认NPU映射实现2.6倍至7.6倍的加速，相比CPU和GPU实现最高8.6倍的能效提升，整体性能相比CPU和GPU分别高出10.8倍和6.7倍，适用于各种GNN模型。

> Graph Neural Networks (GNNs) are vital for learning from graph-structured data, enabling applications in network analysis, recommendation systems, and speech analytics. Deploying them on edge devices like client PCs and laptops enhances real-time processing, privacy, and cloud independence. GNNs aid Retrieval-Augmented Generation (RAG) for Large Language Models (LLMs) and enable event-based vision tasks. However, irregular memory access, sparsity, and dynamic structures cause high latency and energy overhead on resource-constrained devices. While modern edge processors integrate CPUs, GPUs, and NPUs, NPUs designed for data-parallel tasks struggle with irregular GNN computations. We introduce GraNNite, the first hardware-aware framework optimizing GNN execution on commercial-off-the-shelf (COTS) SOTA DNN accelerators via a structured three-step methodology: (1) enabling NPU execution, (2) optimizing performance, and (3) trading accuracy for efficiency gains. Step 1 employs GraphSplit for workload distribution and StaGr for static aggregation, while GrAd and NodePad handle dynamic graphs. Step 2 boosts performance using EffOp for control-heavy tasks and GraSp for sparsity exploitation. Graph Convolution optimizations PreG, SymG, and CacheG reduce redundancy and memory transfers. Step 3 balances quality versus efficiency, where QuantGr applies INT8 quantization, and GrAx1, GrAx2, and GrAx3 accelerate attention, broadcast-add, and SAGE-max aggregation. On Intel Core Ultra AI PCs, GraNNite achieves 2.6X to 7.6X speedups over default NPU mappings and up to 8.6X energy gains over CPUs and GPUs, delivering 10.8X and 6.7X higher performance than CPUs and GPUs, respectively, across GNN models.

[Arxiv](https://arxiv.org/abs/2502.06921)