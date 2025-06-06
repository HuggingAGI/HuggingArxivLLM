# FPTQuant：保持功能的LLM量化变换

发布时间：2025年06月05日

`LLM理论` `人工智能` `计算机科学`

> FPTQuant: Function-Preserving Transforms for LLM Quantization

# 摘要

> 大型语言模型 (LLMs) 在推理时需要大量计算资源，因此也会消耗大量能源。虽然量化技术能够有效提升效率，但简单粗暴的量化却可能导致性能大幅下降，尤其是因为大范围的异常值。本文介绍了 FPTQuant，它引入了四个新颖、轻量且表达能力强的功能保持变换 (FPTs)，以促进 Transformer 的量化：(1) 用于查询和键的可合并预 RoPE 变换，(2) 用于值的可合并变换，(3) 用于 MLP 块内的可合并缩放变换，(4) 一种廉价的动态缩放变换。通过利用标准 Transformer 运算中固有的等变性和独立性，我们设计了这些 FPTs，在保持模型功能的同时，调整中间激活分布，使其更适合量化。FPTQuant 无需自定义内核，推理时几乎不增加额外开销。这些 FPTs 既通过局部训练来减少异常值，也通过端到端训练使量化模型和全精度模型的输出相匹配。FPTQuant 支持静态 INT4 量化，开销极小，与 FP 相比实现了高达 3.9 倍的最先进加速。实验证明，FPTQuant 在准确性和速度之间取得了极佳的平衡——其性能与大多数先前工作持平或更优，仅在精度上略逊于一种速度慢 29% 的方法。


> Large language models (LLMs) require substantial compute, and thus energy, at inference time. While quantizing weights and activations is effective at improving efficiency, naive quantization of LLMs can significantly degrade performance due to large magnitude outliers. This paper describes FPTQuant, which introduces four novel, lightweight, and expressive function-preserving transforms (FPTs) to facilitate quantization of transformers: (1) a mergeable pre-RoPE transform for queries and keys, (2) a mergeable transform for values, (3) a mergeable scaling transform within the MLP block, and (4) a cheap, dynamic scaling transform. By leveraging the equivariances and independencies inherent to canonical transformer operation, we designed these FPTs to maintain the model's function while shaping the intermediate activation distributions to be more quantization friendly. FPTQuant requires no custom kernels and adds virtually no overhead during inference. The FPTs are trained both locally to reduce outliers, and end-to-end such that the outputs of the quantized and full-precision models match. FPTQuant enables static INT4 quantization with minimal overhead and shows SOTA speed-up of up to 3.9 times over FP. Empirically, FPTQuant has an excellent accuracy-speed trade-off -- it is performing on par or exceeding most prior work and only shows slightly lower accuracy compared to a method that is up to 29% slower.

[Arxiv](https://arxiv.org/abs/2506.04985)