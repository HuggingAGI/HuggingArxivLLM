# COAP：通过相关性感知梯度投影实现内存高效的训练

发布时间：2024年11月25日

`其他` `多模态`

> COAP: Memory-Efficient Training with Correlation-Aware Gradient Projection

# 摘要

> 在视觉和多模态领域训练大规模神经网络，需要大量内存资源，主要原因在于优化器状态的存储。LoRA 虽是流行的参数高效方法，能减少内存使用，却因低秩更新的限制，常表现欠佳。低秩梯度投影方法（如 GaLore、Flora）通过奇异值分解或随机投影，把梯度和矩估计投射到低秩空间，以降低优化器内存。但它们未考虑投影间的相关性，致使性能降低，且其投影策略往往计算成本颇高。本文中，我们提出了 COAP（相关感知梯度投影），这是一种内存高效的方法，能在维持训练性能的同时，最大程度降低计算开销。在各类视觉、语言和多模态任务中评估，COAP 在训练速度和模型性能上均优于现有方法。对于 LLaMA-1B，它能减少 61%的优化器内存，仅增加 2%的时间成本，实现与 AdamW 相同的 PPL。采用 8 位量化，COAP 能减少 81%的优化器内存，在 LLaVA-v1.5-7B 微调中，比 GaLore 提速 4 倍，同时准确性更高。

> Training large-scale neural networks in vision, and multimodal domains demands substantial memory resources, primarily due to the storage of optimizer states. While LoRA, a popular parameter-efficient method, reduces memory usage, it often suffers from suboptimal performance due to the constraints of low-rank updates. Low-rank gradient projection methods (e.g., GaLore, Flora) reduce optimizer memory by projecting gradients and moment estimates into low-rank spaces via singular value decomposition or random projection. However, they fail to account for inter-projection correlation, causing performance degradation, and their projection strategies often incur high computational costs. In this paper, we present COAP (Correlation-Aware Gradient Projection), a memory-efficient method that minimizes computational overhead while maintaining training performance. Evaluated across various vision, language, and multimodal tasks, COAP outperforms existing methods in both training speed and model performance. For LLaMA-1B, it reduces optimizer memory by 61% with only 2% additional time cost, achieving the same PPL as AdamW. With 8-bit quantization, COAP cuts optimizer memory by 81% and achieves 4x speedup over GaLore for LLaVA-v1.5-7B fine-tuning, while delivering higher accuracy.

[Arxiv](https://arxiv.org/abs/2412.00071)