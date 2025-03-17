# FastVID: 通过动态密度剪枝实现快速视频大型语言模型

发布时间：2025年03月14日

`LLM应用

摘要中提到的论文主要讨论了如何优化视频大型语言模型的推理效率，通过剪枝技术减少计算成本，同时保持模型性能。这属于在实际应用中对LLM的优化和改进，因此归类为LLM应用。` `视频处理`

> FastVID: Dynamic Density Pruning for Fast Video Large Language Models

# 摘要

> 视频大型语言模型在视频理解方面展现了令人印象深刻的潜力，但冗余视频令牌带来的高昂推理成本阻碍了其实际应用。现有的剪枝技术未能充分利用视频数据固有的时空冗余特性。为了解决这一问题，我们从时间上下文和视觉上下文两个角度对视频冗余进行了系统性分析。基于这一洞察，我们提出了一种名为FastVID的动态密度剪枝方法，用于加速视频LLM。具体而言，FastVID将视频动态划分为按时间顺序排列的片段以保留时间结构，并采用基于密度的令牌剪枝策略以保持关键视觉信息。我们的方法在显著降低计算开销的同时，维持了时间和视觉信息的完整性。大量评估表明，FastVID在领先的视频LLM（包括LLaVA-OneVision和LLaVA-Video）的多个短片和长视频基准测试中实现了最先进性能。值得注意的是，FastVID成功剪枝了90%的视频令牌，同时保留了LLaVA-OneVision 98.0%的原始性能。代码可在https://github.com/LunarShen/FastVID获取。

> Video Large Language Models have shown impressive capabilities in video comprehension, yet their practical deployment is hindered by substantial inference costs caused by redundant video tokens. Existing pruning techniques fail to fully exploit the spatiotemporal redundancy inherent in video data. To bridge this gap, we perform a systematic analysis of video redundancy from two perspectives: temporal context and visual context. Leveraging this insight, we propose Dynamic Density Pruning for Fast Video LLMs termed FastVID. Specifically, FastVID dynamically partitions videos into temporally ordered segments to preserve temporal structure and applies a density-based token pruning strategy to maintain essential visual information. Our method significantly reduces computational overhead while maintaining temporal and visual integrity. Extensive evaluations show that FastVID achieves state-of-the-art performance across various short- and long-video benchmarks on leading Video LLMs, including LLaVA-OneVision and LLaVA-Video. Notably, FastVID effectively prunes 90% of video tokens while retaining 98.0% of LLaVA-OneVision's original performance. The code is available at https://github.com/LunarShen/FastVID.

[Arxiv](https://arxiv.org/abs/2503.11187)