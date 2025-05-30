# MemAscend：针对 SSD 卸载的大语言模型微调进行系统内存优化

发布时间：2025年05月29日

`其他

理由：这篇论文主要关注的是在训练大型语言模型时遇到的系统级挑战，特别是内存管理和资源优化。虽然它提到了LLMs的应用，但核心内容集中在如何通过优化系统资源来提升训练效率，而不是直接讨论LLMs的应用场景或理论发展。因此，最适合的分类是其他。` `人工智能` `计算机系统`

> MemAscend: System Memory Optimization for SSD-Offloaded LLM Fine-Tuning

# 摘要

> 生成式人工智能（AI）的成功推动了大型语言模型（LLMs）的崛起，使其成为支撑问答、文本生成和代码补全等应用的核心技术。尽管在特定领域数据上进行微调能显著提升性能，但这一过程对计算资源提出了巨大挑战，尤其对硬件有限的研究者和小机构而言。虽然SSD卸载技术（如ZeRO-Infinity）通过结合CPU内存和SSD存储解决了GPU内存瓶颈，但其设计主要聚焦于模型性能优化，忽视了系统级问题，如内存碎片、固定缓冲区分配低效、CPU负载峰值及文件系统开销，这些问题严重制约了扩展性并推高了成本。为应对这些挑战，我们提出了MemAscend框架，专注于解决SSD卸载训练中被忽视的系统内存瓶颈，特别是在资源受限的环境中。通过优化固定内存分配、消除碎片化并降低峰值开销，MemAscend释放了大量系统内存资源，支持在有限硬件条件下训练更大模型、更长上下文窗口及更大批次规模。实验结果显示，与传统SSD卸载方法相比，MemAscend将系统内存峰值消耗平均降低了55.7%，显著降低了微调所需的硬件门槛，并为资源有限设备上的大规模高效训练开辟了新路径。

> Owing to the huge success of generative artificial intelligence (AI), large language models (LLMs) have emerged as a core subclass, underpinning applications such as question answering, text generation, and code completion. While fine-tuning these models on domain-specific data can yield significant performance gains, it also poses daunting computational challenges, especially for researchers and small organizations with limited hardware resources. Although SSD offloading (i.e., ZeRO-Infinity) has emerged as a viable strategy to overcome the GPU memory barrier via leveraging both system memory (i.e., CPU DRAM) and storage space (i.e., solid-state devices, SSDs), its design primarily targets model-centric performance issues. As a result, key system-level issues, including system memory fragmentation, inefficient pinned buffer allocation, peak CPU usage spikes, and file system overhead, remain unaddressed, stifling scalability and inflating costs. Such an observation motivates this paper to introduce MemAscend, a framework that systematically tackles the underexplored system memory bottlenecks in SSD-offloaded LLM training, with a focus on resource-constrained environments. By streamlining pinned-memory allocation, eradicating fragmentation, and mitigating peak overhead, MemAscend reclaims a substantial system memory budget, enabling larger models, longer context windows, and higher batch sizes without exceeding modest hardware limits. Across diverse LLM benchmarks, MemAscend reduces peak system-memory consumption by an average of 55.7% compared with standard SSD offloading techniques, lowering the hardware barrier for fine-tuning and unlocking new possibilities for cost-effective large-scale training on limited-resource machines.

[Arxiv](https://arxiv.org/abs/2505.23254)