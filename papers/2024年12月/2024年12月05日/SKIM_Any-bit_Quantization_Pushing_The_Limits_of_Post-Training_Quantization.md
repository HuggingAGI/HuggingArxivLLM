# SKIM：任意位量化 突破训练后量化的限制

发布时间：2024年12月05日

`LLM应用` `语言模型`

> SKIM: Any-bit Quantization Pushing The Limits of Post-Training Quantization

# 摘要

> 大型语言模型（LLMs）在各类任务中表现抢眼，但用于推理时却面临难题。其对资源的高要求往往得依靠复杂、昂贵的多 GPU 管道，或者采用较小且性能稍逊的模型。虽说量化利用较低精度为模型存储带来了希望，可现有方法在低精度水平时常会有明显的性能下滑。另外，它们通常只在特定位级别提供有限的几组解决方案，其中不少还经过大量人工调试。为应对这些挑战，我们提出了一种名为 SKIM 的新方法：带混合精度的缩放 K 均值聚类。我们的方法引入了两项新技术：1. 一种贪婪算法，用于近似求解权重通道的最佳位分配；2. 一个用于不可微 K 均值聚类的可训练缩放向量。这些技术大幅提升了性能，且能适应任何给定的位。值得一提的是，在模型困惑度方面，我们的方法平均将 3 位量化的 LLaMA 模型与全精度模型之间的差距缩小了 16.3%。

> Large Language Models (LLMs) exhibit impressive performance across various tasks, but deploying them for inference poses challenges. Their high resource demands often necessitate complex, costly multi-GPU pipelines, or the use of smaller, less capable models. While quantization offers a promising solution utilizing lower precision for model storage, existing methods frequently experience significant performance drops at lower precision levels. Additionally, they typically provide only a limited set of solutions at specific bit levels, many of which are extensively manually tuned. To address these challenges, we propose a new method called SKIM: Scaled K-means clustering wIth Mixed precision. Our approach introduces two novel techniques: 1. A greedy algorithm to solve approximately optimal bit allocation across weight channels, and 2. A trainable scaling vector for non-differentiable K-means clustering. These techniques substantially improve performance and can be adapted to any given bit. Notably, in terms of model perplexity, our method narrows the gap between 3-bit quantized LLaMA models and their full precision counterparts by 16.3% on average.

[Arxiv](https://arxiv.org/abs/2412.04180)