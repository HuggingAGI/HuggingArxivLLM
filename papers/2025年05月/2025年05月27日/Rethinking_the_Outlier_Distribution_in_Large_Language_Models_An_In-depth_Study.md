# 重新审视大型语言模型中的异常分布：一项深度研究

发布时间：2025年05月27日

`LLM应用` `人工智能` `模型优化`

> Rethinking the Outlier Distribution in Large Language Models: An In-depth Study

# 摘要

> 大型语言模型 (LLMs) 中的异常值研究至关重要，因其显著影响模型的量化和压缩性能。这些异常值常引发严重量化误差，导致模型性能下降。识别并处理异常值可提升量化过程的准确性和效率，从而实现模型在边缘设备或专用硬件上的更顺畅部署。近期研究表明，LLMs 中存在两类主要异常值：大规模激活和通道级异常值。尽管已有诸多量化算法提出以缓解这些异常值的影响并保持精度，但对这些异常值根源的深入探究却较少。本文全面调查了这些异常值的形成机制，并提出潜在策略以减轻其发生。最终，我们提出了一些高效方法，能够在几乎不影响精度的情况下消除大部分大规模激活和通道级异常值。

> Investigating outliers in large language models (LLMs) is crucial due to their significant impact on various aspects of LLM performance, including quantization and compression. Outliers often cause considerable quantization errors, leading to degraded model performance. Identifying and addressing these outliers can enhance the accuracy and efficiency of the quantization process, enabling smoother deployment on edge devices or specialized hardware. Recent studies have identified two common types of outliers in LLMs: massive activations and channel-wise outliers. While numerous quantization algorithms have been proposed to mitigate their effects and maintain satisfactory accuracy, few have thoroughly explored the root causes of these outliers in depth. In this paper, we conduct a comprehensive investigation into the formation mechanisms of these outliers and propose potential strategies to mitigate their occurrence. Ultimately, we introduce some efficient approaches to eliminate most massive activations and channel-wise outliers with minimal impact on accuracy.

[Arxiv](https://arxiv.org/abs/2505.21670)