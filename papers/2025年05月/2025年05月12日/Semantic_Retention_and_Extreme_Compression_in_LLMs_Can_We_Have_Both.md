# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月12日

`LLM理论` `模型压缩` `评估框架`

> Semantic Retention and Extreme Compression in LLMs: Can We Have Both?

# 摘要

> 随着大型语言模型（LLM）部署规模的指数级增长，高效模型压缩技术的需求日益迫切，以降低计算和内存成本。虽然剪枝和量化技术已展现出巨大潜力，但它们的联合应用仍有待深入探索。本文聚焦于联合压缩技术，研究了如何通过战略性结合剪枝和量化方法，实现优于单一技术的性能与压缩比。为应对准确评估LLM性能的挑战，我们改进了现有评估框架，提出了语义保留压缩率（SrCr）这一创新指标，用于量化模型压缩与语义保留的平衡关系，从而优化剪枝-量化配置。实验结果表明，与相同压缩率下的纯量化模型相比，我们的推荐组合平均性能提升了20%。

> The exponential growth in Large Language Model (LLM) deployment has intensified the need for efficient model compression techniques to reduce computational and memory costs. While pruning and quantization have shown promise, their combined potential remains largely unexplored. In this paper, we examine joint compression and how strategically combining pruning and quantization could yield superior performance-to-compression ratios compared to single-method approaches. Recognizing the challenges in accurately assessing LLM performance, we address key limitations of previous evaluation frameworks and introduce the Semantic Retention Compression Rate (SrCr), a novel metric that quantifies the trade-off between model compression and semantic preservation, facilitating the optimization of pruning-quantization configurations. Experiments demonstrate that our recommended combination achieves, on average, a 20% performance increase compared to an equivalent quantization-only model at the same theoretical compression rate.

[Arxiv](https://arxiv.org/abs/2505.07289)