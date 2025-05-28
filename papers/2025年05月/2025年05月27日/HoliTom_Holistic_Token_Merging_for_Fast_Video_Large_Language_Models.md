# HoliTom：面向高效视频大语言模型的全面令牌融合

发布时间：2025年05月27日

`LLM应用` `视频处理` `计算效率`

> HoliTom: Holistic Token Merging for Fast Video Large Language Models

# 摘要

> 视频大语言模型在视频理解方面表现出色，但冗余的视频令牌导致计算效率低下。现有的剪枝方法提供了解决方案，但在LLM内部进行剪枝的方法会在浅层引入计算开销。外层LLM剪枝方法主要解决帧内空间冗余或有限时间窗口内的冗余，忽视了全局时间动态和长序列间的关联，导致次优的空间-时间缩减。我们提出HoliTom，一个无训练的全局令牌合并框架。通过全局冗余感知的时间分割进行外层LLM剪枝，随后进行空间-时间合并，将视觉令牌减少90%以上，显著降低了计算负担。我们还提出了一种基于令牌相似性的内层LLM合并方法，实现更优性能并兼容外层剪枝。在LLaVA-OneVision-7B上，计算成本降至6.9%的浮点运算次数，同时保持99.1%的性能。此外，我们实现了2.28倍的首次令牌生成时间减少和1.32倍的解码加速，展示了集成剪枝方法在高效视频LLM推理中的实际优势。

> Video large language models (video LLMs) excel at video comprehension but face significant computational inefficiency due to redundant video tokens. Existing token pruning methods offer solutions. However, approaches operating within the LLM (inner-LLM pruning), such as FastV, incur intrinsic computational overhead in shallow layers. In contrast, methods performing token pruning before the LLM (outer-LLM pruning) primarily address spatial redundancy within individual frames or limited temporal windows, neglecting the crucial global temporal dynamics and correlations across longer video sequences. This leads to sub-optimal spatio-temporal reduction and does not leverage video compressibility fully. Crucially, the synergistic potential and mutual influence of combining these strategies remain unexplored. To further reduce redundancy, we introduce HoliTom, a novel training-free holistic token merging framework. HoliTom employs outer-LLM pruning through global redundancy-aware temporal segmentation, followed by spatial-temporal merging to reduce visual tokens by over 90%, significantly alleviating the LLM's computational burden. Complementing this, we introduce a robust inner-LLM token similarity-based merging approach, designed for superior performance and compatibility with outer-LLM pruning. Evaluations demonstrate our method's promising efficiency-performance trade-off on LLaVA-OneVision-7B, reducing computational costs to 6.9% of FLOPs while maintaining 99.1% of the original performance. Furthermore, we achieve a 2.28x reduction in Time-To-First-Token (TTFT) and a 1.32x acceleration in decoding throughput, highlighting the practical benefits of our integrated pruning approach for efficient video LLMs inference.

[Arxiv](https://arxiv.org/abs/2505.21334)