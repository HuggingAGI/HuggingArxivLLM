# 压缩与模型压缩的邂逅：面向大语言模型的内存高效双压缩方案

发布时间：2025年02月21日

`LLM应用` `人工智能` `机器学习`

> When Compression Meets Model Compression: Memory-Efficient Double Compression for Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类任务中表现优异，但其内存需求在部署至内存受限设备时仍面临巨大挑战，即使经过量化处理亦然。本文提出了一种量化后进一步压缩LLMs的框架，实现约2.2倍压缩比。首先，我们提出一种压缩感知量化方法，通过量化前重新缩放模型参数提升权重可压缩性，并辅以剪枝方法进一步优化。在此基础上，我们发现解压缩可能成为实际应用中的瓶颈。因此，我们详细分析了所提方法带来的内存使用与延迟权衡，并提出速度自适应方法以克服这一问题。实验结果表明，压缩后模型推理可在几乎无损准确性和速度的情况下，将内存占用减少40%。

> Large language models (LLMs) exhibit excellent performance in various tasks. However, the memory requirements of LLMs present a great challenge when deploying on memory-limited devices, even for quantized LLMs. This paper introduces a framework to compress LLM after quantization further, achieving about 2.2x compression ratio. A compression-aware quantization is first proposed to enhance model weight compressibility by re-scaling the model parameters before quantization, followed by a pruning method to improve further. Upon this, we notice that decompression can be a bottleneck during practical scenarios. We then give a detailed analysis of the trade-off between memory usage and latency brought by the proposed method. A speed-adaptive method is proposed to overcome it. The experimental results show inference with the compressed model can achieve a 40% reduction in memory size with negligible loss in accuracy and inference speed.

[Arxiv](https://arxiv.org/abs/2502.15443)