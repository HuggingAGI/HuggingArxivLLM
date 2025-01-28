# AKVQ-VL: 视觉-语言模型的注意力感知KV缓存自适应2位量化

发布时间：2025年01月24日

`LLM应用

**解释**：这篇论文主要讨论了如何通过改进键值（KV）量化方法来优化视觉语言模型（VLMs）在多模态任务中的性能。虽然涉及多模态任务，但其核心是围绕大型语言模型（LLMs）的应用和优化，特别是针对内存消耗和I/O瓶颈的解决方案。因此，将其分类为LLM应用是合适的。` `计算机视觉`

> AKVQ-VL: Attention-Aware KV Cache Adaptive 2-Bit Quantization for Vision-Language Models

# 摘要

> # 摘要
视觉语言模型（VLMs）在多模态任务中表现卓越，但过长的多模态输入会导致键值（KV）缓存过大，引发内存消耗和I/O瓶颈。尽管现有的LLM KV量化方法能缓解部分问题，却忽视了多模态token的注意力显著性差异，导致性能欠佳。本文提出AKVQ-VL，通过文本显著性注意力（TSA）和关键token显著性注意力（PSA）模式，自适应分配比特预算。此外，AKVQ-VL利用Walsh-Hadamard变换（WHT）构建无异常值的KV缓存，降低量化难度。在12个长上下文和多模态任务上的2位量化评估中，AKVQ-VL不仅保持甚至提升了准确性，还优于面向LLM的方法，峰值内存使用减少2.13倍，批量大小提升3.25倍，吞吐量增加2.46倍。

> Vision-language models (VLMs) show remarkable performance in multimodal tasks. However, excessively long multimodal inputs lead to oversized Key-Value (KV) caches, resulting in significant memory consumption and I/O bottlenecks. Previous KV quantization methods for Large Language Models (LLMs) may alleviate these issues but overlook the attention saliency differences of multimodal tokens, resulting in suboptimal performance. In this paper, we investigate the attention-aware token saliency patterns in VLM and propose AKVQ-VL. AKVQ-VL leverages the proposed Text-Salient Attention (TSA) and Pivot-Token-Salient Attention (PSA) patterns to adaptively allocate bit budgets. Moreover, achieving extremely low-bit quantization requires effectively addressing outliers in KV tensors. AKVQ-VL utilizes the Walsh-Hadamard transform (WHT) to construct outlier-free KV caches, thereby reducing quantization difficulty. Evaluations of 2-bit quantization on 12 long-context and multimodal tasks demonstrate that AKVQ-VL maintains or even improves accuracy, outperforming LLM-oriented methods. AKVQ-VL can reduce peak memory usage by 2.13x, support up to 3.25x larger batch sizes and 2.46x throughput.

[Arxiv](https://arxiv.org/abs/2501.15021)