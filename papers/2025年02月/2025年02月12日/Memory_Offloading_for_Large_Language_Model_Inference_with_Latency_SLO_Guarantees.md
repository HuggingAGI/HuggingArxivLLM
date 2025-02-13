# 内存分担：保障延迟SLO的大型语言模型推理

发布时间：2025年02月12日

`LLM应用

理由：这篇论文讨论了如何优化大型语言模型（LLMs）在推理过程中的内存使用，以提高服务吞吐量和满足延迟目标。它提出了一种新的内存卸载系统Select-N，专注于在实际应用中优化LLM的性能，属于LLM的应用层面。` `人工智能` `云计算`

> Memory Offloading for Large Language Model Inference with Latency SLO Guarantees

# 摘要

> 在推理过程中将大型语言模型（LLMs）的状态卸载到主机内存，能够支持更大模型、更长输入和更大批次，从而降低运营成本。然而，现有内存卸载机制的设计并未考虑延迟服务级别目标（SLO）。因此，它们要么导致频繁的SLO违规，要么未能充分利用主机内存，从而造成经济损失，进而违背了内存卸载的初衷。本文介绍了Select-N，这是一种针对LLM服务的延迟-SLO感知内存卸载系统。设计Select-N的一个关键挑战在于平衡满足SLO与最大化主机内存使用之间的紧张关系。Select-N通过利用现代LLMs的独特特性克服了这一挑战：在服务过程中，每个解码器层的计算时间是确定性的。基于此，Select-N引入了卸载间隔，这是一个可调内部旋钮，能够捕捉SLO与主机内存使用之间的权衡，从而将上述挑战转化为选择一个最优卸载间隔的问题。为此，Select-N提出了一种两阶段方法来自动选择卸载间隔。第一阶段是离线阶段，生成最优卸载间隔的范围；第二阶段则根据运行时硬件状态，以推理迭代的粒度调整卸载间隔。我们的评估表明，Select-N始终满足SLO，并通过最大化主机内存的使用，使服务吞吐量比现有机制提高了1.85倍。

> Offloading large language models (LLMs) state to host memory during inference promises to reduce operational costs by supporting larger models, longer inputs, and larger batch sizes. However, the design of existing memory offloading mechanisms does not take latency service-level objectives (SLOs) into consideration. As a result, they either lead to frequent SLO violations or underutilize host memory, thereby incurring economic loss and thus defeating the purpose of memory offloading.
  This paper presents Select-N, a latency-SLO-aware memory offloading system for LLM serving. A key challenge in designing Select-N is to reconcile the tension between meeting SLOs and maximizing host memory usage. Select-N overcomes it by exploiting a unique characteristic of modern LLMs: during serving, the computation time of each decoder layer is deterministic. Leveraging this, Select-N introduces offloading interval, an internal tunable knob that captures the tradeoff between SLOs and host memory usage, thereby reducing the aforementioned challenge to pick an optimal offloading interval. With that, Select-N proposes a two-stage approach to automatically pick the offloading interval. The first stage is offline that generates the range of optimal offloading interval, while the second stage adjusts offloading interval at the granularity of inference iteration based on runtime hardware status. Our evaluation shows that Select-N consistently meets SLOs and improves the serving throughput over existing mechanisms by 1.85X due to maximizing the use of host memory.

[Arxiv](https://arxiv.org/abs/2502.08182)