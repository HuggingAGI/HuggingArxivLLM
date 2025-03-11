# # CASP：基于注意力稀疏性的大型多模态模型压缩

发布时间：2025年03月07日

`LLM应用` `人工智能` `视觉处理`

> CASP: Compression of Large Multimodal Models Based on Attention Sparsity

# 摘要

> 本研究提出了一种针对大规模多模态模型（LMMs）的极端压缩技术。尽管量化已被证明是大型语言模型（LLMs）的高效后训练压缩方法，但多模态模型的低比特压缩仍待深入探索。多模态模型输入的冗余性导致了注意力矩阵的高度稀疏性，我们通过理论和实验验证了这一稀疏性对Query和Key权重矩阵压缩误差的限制。基于此，我们提出了CASP——一种专为LMMs设计的模型压缩技术。该方法首先对Query和Key权重矩阵进行数据感知的低秩分解，然后通过最优比特分配过程对所有层进行量化。CASP不仅兼容任何量化技术，还在图像和视频语言基准测试中将现有2比特量化方法（AQLM和QuIP#）的性能平均提升了21%。

> In this work, we propose an extreme compression technique for Large Multimodal Models (LMMs). While previous studies have explored quantization as an efficient post-training compression method for Large Language Models (LLMs), low-bit compression for multimodal models remains under-explored. The redundant nature of inputs in multimodal models results in a highly sparse attention matrix. We theoretically and experimentally demonstrate that the attention matrix's sparsity bounds the compression error of the Query and Key weight matrices. Based on this, we introduce CASP, a model compression technique for LMMs. Our approach performs a data-aware low-rank decomposition on the Query and Key weight matrix, followed by quantization across all layers based on an optimal bit allocation process. CASP is compatible with any quantization technique and enhances state-of-the-art 2-bit quantization methods (AQLM and QuIP#) by an average of 21% on image- and video-language benchmarks.

[Arxiv](https://arxiv.org/abs/2503.05936)