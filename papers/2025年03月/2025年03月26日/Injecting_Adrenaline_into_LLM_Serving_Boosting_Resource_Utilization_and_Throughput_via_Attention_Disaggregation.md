# 为LLM服务注入肾上腺素——通过注意力解耦提升资源利用率与吞吐量

发布时间：2025年03月26日

`LLM应用

摘要中讨论的是如何优化大型语言模型服务系统的资源利用率和性能，特别是通过提出一种新的机制来改进计算和内存的使用效率。这属于大型语言模型的实际应用和优化，因此归类为LLM应用。` `云计算` `大数据`

> Injecting Adrenaline into LLM Serving: Boosting Resource Utilization and Throughput via Attention Disaggregation

# 摘要

> 在大型语言模型 (LLM) 服务系统中，请求处理分为两个阶段：计算密集的填充计算阶段和内存密集的解码阶段。为避免两者互相干扰，现有系统通常采用分离式架构，将两个阶段部署在不同机器上。然而，这种设计导致了严重的资源浪费问题：计算密集的填充实例内存利用率低，而内存密集的解码实例计算利用率不足。针对这一问题，本研究提出了一种名为 Adrenaline 的注意力计算分离与卸载机制，旨在提升 LLM 服务系统的资源利用率和性能表现。Adrenaline 的核心创新在于将解码阶段的部分注意力计算从解码实例中分离出来，并将其卸载到填充实例上执行。这一设计充分利用了解码阶段注意力计算的内存密集型特性，带来两大互补优势：1) 提高填充实例的内存容量和带宽利用率，2) 增加解码批次规模以提升解码实例的计算利用率，从而整体上提升了系统性能。Adrenaline 通过三项关键技术实现这些提升：低延迟解码同步、资源高效的填充实例共存以及负载感知的卸载调度。实验结果表明，与现有最优系统相比，Adrenaline 在填充实例中实现了 2.28 倍的内存容量提升和 2.07 倍的内存带宽利用率提升，解码实例的计算利用率提高了高达 1.67 倍，整体推理吞吐量提升了 1.68 倍。

> In large language model (LLM) serving systems, executing each request consists of two phases: the compute-intensive prefill phase and the memory-intensive decoding phase. To prevent performance interference between the two phases, current LLM serving systems typically adopt prefill-decoding disaggregation, where the two phases are split across separate machines. However, we observe this approach leads to significant resource underutilization. Specifically, prefill instances that are compute-intensive suffer from low memory utilization, while decoding instances that are memory-intensive experience low compute utilization. To address this problem, this paper proposes Adrenaline, an attention disaggregation and offloading mechanism designed to enhance resource utilization and performance in LLM serving systems. Adrenaline's key innovation lies in disaggregating part of the attention computation in the decoding phase and offloading them to prefill instances. The memory-bound nature of decoding-phase attention computation inherently enables an effective offloading strategy, yielding two complementary advantages: 1) improved memory capacity and bandwidth utilization in prefill instances, and 2) increased decoding batch sizes that enhance compute utilization in decoding instances, collectively boosting overall system performance. Adrenaline achieves these gains through three key techniques: low-latency decoding synchronization, resource-efficient prefill colocation, and load-aware offloading scheduling. Experimental results show that Adrenaline achieves 2.28x higher memory capacity and 2.07x better memory bandwidth utilization in prefill instances, up to 1.67x improvements in compute utilization for decoding instances, and 1.68x higher overall inference throughput compared to state-of-the-art systems.

[Arxiv](https://arxiv.org/abs/2503.20552)