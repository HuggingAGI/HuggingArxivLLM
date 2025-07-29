# 几何平均策略优化方法

发布时间：2025年07月28日

`LLM理论` `人工智能`

> Geometric-Mean Policy Optimization

# 摘要

> 近期，组相对策略优化（GRPO）等技术通过优化词级别奖励的算术平均值，显著提升了大型语言模型的推理能力。然而，GRPO在处理具有异常值加权奖励的词时，存在策略更新不稳定的问题，这表现为训练过程中极端的重采样比率。本研究提出了一种稳定的GRPO变体——几何均值策略优化（GMPO）。与GRPO不同，GMPO最大化词级别奖励的几何平均值，这使其天然对异常值不敏感，并保持更稳定的重采样比率范围。我们通过全面的理论和实验分析，验证了GMPO的设计优势和稳定性。实验结果表明，GMPO-7B不仅稳定性更佳，在多个数学基准测试中比GRPO平均高出4.1%，并在多模态推理基准测试中高出1.4%，包括AIME24、AMC、MATH500、OlympiadBench、Minerva和Geometry3K。代码可在GitHub仓库获取：https://github.com/callsys/GMPO。


> Recent advancements, such as Group Relative Policy Optimization (GRPO), have enhanced the reasoning capabilities of large language models by optimizing the arithmetic mean of token-level rewards. However, GRPO suffers from unstable policy updates when processing tokens with outlier importance-weighted rewards, which manifests as extreme importance sampling ratios during training, i.e., the ratio between the sampling probabilities assigned to a token by the current and old policies. In this work, we propose Geometric-Mean Policy Optimization (GMPO), a stabilized variant of GRPO. Instead of optimizing the arithmetic mean, GMPO maximizes the geometric mean of token-level rewards, which is inherently less sensitive to outliers and maintains a more stable range of importance sampling ratio. In addition, we provide comprehensive theoretical and experimental analysis to justify the design and stability benefits of GMPO. Beyond improved stability, GMPO-7B outperforms GRPO by an average of 4.1% on multiple mathematical benchmarks and 1.4% on multimodal reasoning benchmark, including AIME24, AMC, MATH500, OlympiadBench, Minerva, and Geometry3K. Code is available at https://github.com/callsys/GMPO.

[Arxiv](https://arxiv.org/abs/2507.20673)