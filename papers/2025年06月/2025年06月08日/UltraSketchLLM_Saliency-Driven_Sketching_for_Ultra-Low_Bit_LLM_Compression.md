# 显著性驱动素描用于超低比特LLM压缩：UltraSketchLLM

发布时间：2025年06月08日

`LLM理论` `边缘计算` `人工智能`

> UltraSketchLLM: Saliency-Driven Sketching for Ultra-Low Bit LLM Compression

# 摘要

> 大型语言模型（LLMs）的快速发展远远超出了边缘设备的内存限制，迫切需要突破1比特的限制进行极端权重压缩。虽然量化技术能够减小模型规模，但它本质上只能将每个权重压缩到1比特。现有的多对一压缩方法要么依赖映射表（导致内存开销），要么因随机权重分组而造成严重的准确性下降。

我们引入了UltraSketchLLM，这是一个无需索引、基于素描的框架，能够在保持模型性能的同时实现超低比特压缩（每个权重低至0.5比特）。UltraSketchLLM采用数据素描技术，这是一种来自流应用的次线性表示方法，能够将多个权重映射到单个值，同时保证误差在可控范围内。

我们的方法集成了低估AbsMaxMin素描以最小化小权重的相对误差、基于重要性的空间分配以优先处理显著权重，以及用于压缩感知微调的直通估计器。在Llama-3.2-1B上的实验表明，UltraSketchLLM能够实现0.5比特的压缩，同时保持具有竞争力的困惑度，以及可接受的延迟开销。UltraSketchLLM为在资源受限的环境中部署LLMs提供了一种实用的解决方案。


> The rapid growth of large language models (LLMs) has outpaced the memory constraints of edge devices, necessitating extreme weight compression beyond the 1-bit limit. While quantization reduces model size, it is fundamentally limited to 1 bit per weight. Existing multiple-to-one compression methods either rely on mapping tables (inducing memory overhead) or incur severe accuracy degradation due to random weight grouping. We introduce UltraSketchLLM, an index-free, sketch-based framework that achieves ultra-low bit compression (down to 0.5 bits per weight) while preserving model performance. UltraSketchLLM leverages data sketching, a sub-linear representation technique from streaming applications, to map multiple weights to single values with bounded error. Our approach integrates an underestimate AbsMaxMin sketch to minimize relative errors for small weights, importance-aware space allocation to prioritize salient weights, and a straight-through estimator for compression-aware finetuning. Experiments on Llama-3.2-1B demonstrate up to 0.5-bit compression with competitive perplexity, alongside tolerable latency overhead. UltraSketchLLM offers a practical solution for deploying LLMs in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2506.17255)