# L3: 面向可扩展长上下文 LLM 推理的 DIMM-PIM 集成架构与协调机制

发布时间：2025年04月24日

`LLM应用` `人工智能` `计算机体系结构`

> L3: DIMM-PIM Integrated Architecture and Coordination for Scalable Long-Context LLM Inference

# 摘要

> 大语言模型（LLMs）在处理长文本序列时面临内存挑战。GPU内存的限制让容量与带宽的权衡变得艰难。HBM加速虽然带宽高，但容量有限；而主机侧DIMM虽能提升容量，却增加了数据交换的开销。我们发现，内存瓶颈仅存在于多头注意力（MHA）的解码阶段，这一阶段需要大量KV缓存存储空间和高带宽注意力计算。这一操作与现代DIMM-计算内存（PIM）架构完美契合，后者在容量和带宽上都具备扩展性。

基于这一发现，我们提出了L3系统，它通过软硬件协同设计整合了DIMM-PIM和GPU设备。L3的三大创新包括：硬件重构解决DIMM-PIM的数据布局和计算单元不匹配问题，提升LLM推理效率；通信优化隐藏数据传输开销；自适应调度器协调GPU-DIMM-PIM操作，最大化设备间的并行性。实测数据显示，L3较现有HBM-PIM方案提速6.1倍，同时显著提升批量处理规模。

> Large Language Models (LLMs) increasingly require processing long text sequences, but GPU memory limitations force difficult trade-offs between memory capacity and bandwidth. While HBM-based acceleration offers high bandwidth, its capacity remains constrained. Offloading data to host-side DIMMs improves capacity but introduces costly data swapping overhead. We identify that the critical memory bottleneck lies in the decoding phase of multi-head attention (MHA) exclusively, which demands substantial capacity for storing KV caches and high bandwidth for attention computation. Our key insight reveals this operation uniquely aligns with modern DIMM-based processing-in-memory (PIM) architectures, which offers scalability of both capacity and bandwidth.
  Based on this observation and insight, we propose L3, a hardware-software co-designed system integrating DIMM-PIM and GPU devices. L3 introduces three innovations: First, hardware redesigns resolve data layout mismatches and computational element mismatches in DIMM-PIM, enhancing LLM inference utilization. Second, communication optimization enables hiding the data transfer overhead with the computation. Third, an adaptive scheduler coordinates GPU-DIMM-PIM operations to maximize parallelism between devices. Evaluations using real-world traces show L3 achieves up to 6.1$\times$ speedup over state-of-the-art HBM-PIM solutions while significantly improving batch sizes.

[Arxiv](https://arxiv.org/abs/2504.17584)