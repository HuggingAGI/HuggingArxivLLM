# NestedFP：为大型语言模型提供高性能与内存高效的双精度浮点支持

发布时间：2025年05月29日

`LLM应用` `虚拟助手` `代码生成`

> NestedFP: High-Performance, Memory-Efficient Dual-Precision Floating Point Support for LLMs

# 摘要

> 大型语言模型（LLMs）在虚拟助手和代码生成等延迟敏感、高吞吐量服务中发挥着关键作用。虽然连续批处理和分页注意力等技术能够满足服务级别目标（SLOs），而量化方法可以加速推理过程，但在运行时动态且高效地调整精度仍是一个重要且尚未充分探索的挑战。

硬件对FP8算术的支持，其吞吐量可达FP16的两倍，为交互式LLM服务提供了极具吸引力的机会。然而，当前方法如同时部署FP8和FP16模型，面临着存储开销增加的问题，并未能充分发挥FP8的全部潜力。为了解决这些限制，我们引入了NestedFP，这是一种新型的精度自适应服务技术，能够从单一的16位模型表示中无缝实现FP8和FP16推理，从而不增加额外的内存成本。

NestedFP将每个FP16权重分解为两个8位组件，从而在保持完整的FP16精度的同时，实现高效的FP8执行。我们通过实现一个基于定制CUTLASS的GEMM内核，该内核能够在推理过程中实时重建FP16操作数，并将其集成到vLLM服务框架中，展示了我们方法的实际可行性。

我们的评估表明，与FP16精度相比，NestedFP在FP8模式下实现了高达1.55倍的吞吐量提升，且精度损失可忽略不计，同时在FP16模式下仅引入了3.9%的平均性能开销。因此，NestedFP为动态、SLO感知的精度选择提供了一个灵活的基础，为在突发和异构工作负载下实现更可扩展和高效的LLM服务铺平了道路。

> Large Language Models (LLMs) are playing a crucial role in latency-critical, high-throughput services like virtual assistants and code generation. While techniques such as continuous batching and paged attention address service-level objectives (SLOs), and quantization methods accelerate inference, the dynamic and efficient adaptation of precision at runtime remains a significant, largely underexplored challenge. The emergence of hardware support for FP8 arithmetic, offering up to 2x the throughput of FP16, presents an attractive opportunity for interactive LLM serving. However, current approaches like co-deploying FP8 and FP16 models suffer from increased storage overhead and fail to unlock FP8's full potential. To address these limitations, we introduce NestedFP, a novel precision-adaptive serving technique enabling seamless FP8 and FP16 inference from a single 16-bit model representation, thereby incurring no additional memory cost. NestedFP decomposes each FP16 weight into two 8-bit components, facilitating efficient FP8 execution while preserving full FP16 accuracy. We demonstrate the practical viability of our approach by implementing a custom CUTLASS-based GEMM kernel that reconstructs FP16 operands on-the-fly, integrated within the vLLM serving framework. Our evaluation shows that NestedFP delivers up to 1.55x throughput improvement in FP8 mode with negligible accuracy degradation compared to FP16 precision, while introducing only 3.9% performance overhead on average in FP16 mode across various models. NestedFP thus provides a flexible foundation for dynamic, SLO-aware precision selection, paving the way for more scalable and efficient LLM serving under bursty and heterogeneous workloads.

[Arxiv](https://arxiv.org/abs/2506.02024)