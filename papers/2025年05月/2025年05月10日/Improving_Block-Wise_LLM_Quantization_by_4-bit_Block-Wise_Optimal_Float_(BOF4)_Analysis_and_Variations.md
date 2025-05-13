# # 提升基于块的LLM量化：4位块最优浮点（BOF4）分析与变体研究

发布时间：2025年05月10日

`LLM理论`

> Improving Block-Wise LLM Quantization by 4-bit Block-Wise Optimal Float (BOF4): Analysis and Variations

# 摘要

> 大型语言模型（LLMs）在微调和推理过程中都需要大量内存。为实现内存高效的微调，现有方法采用块量化技术（如NF4和AF4）处理网络权重，但这些技术会导致次优量化误差。因此，我们首先提出了一种块量化优化方法，并设计了一组名为4位块最优浮点（BOF4）的量化器，显著降低了量化误差。我们通过理论和数据驱动的解决方案证明了其优化效果。其次，我们改进了基于有符号绝对块最大值（BOF4-S）的归一化方法，进一步减少了量化误差并提升了语言建模性能。第三，我们通过实验研究了准确表示零权重和大振幅权重的重要性，以及针对不同误差指标的优化方向，探索了更多适用于LLMs的块量化方法。最后，我们提出了一种名为异常值保留量化（OPQ）的混合精度量化策略，通过将异常值权重以16位精度存储，结合BOF4-S，在4位块量化技术中实现了最佳的困惑度性能。

> Large language models (LLMs) demand extensive memory capacity during both fine-tuning and inference. To enable memory-efficient fine-tuning, existing methods apply block-wise quantization techniques, such as NF4 and AF4, to the network weights. We show that these quantization techniques incur suboptimal quantization errors. Therefore, as a first novelty, we propose an optimization approach for block-wise quantization. Using this method, we design a family of quantizers named 4-bit block-wise optimal float (BOF4), which consistently reduces the quantization error compared to both baseline methods. We provide both a theoretical and a data-driven solution for the optimization process and prove their practical equivalence. Secondly, we propose a modification to the employed normalization method based on the signed absolute block maximum (BOF4-S), enabling further reduction of the quantization error and empirically achieving less degradation in language modeling performance. Thirdly, we explore additional variations of block-wise quantization methods applied to LLMs through an experimental study on the importance of accurately representing zero and large-amplitude weights on the one hand, and optimization towards various error metrics on the other hand. Lastly, we introduce a mixed-precision quantization strategy dubbed outlier-preserving quantization (OPQ) to address the distributional mismatch induced by outlier weights in block-wise quantization. By storing outlier weights in 16-bit precision (OPQ) while applying BOF4-S, we achieve top performance among 4-bit block-wise quantization techniques w.r.t. perplexity.

[Arxiv](https://arxiv.org/abs/2505.06653)