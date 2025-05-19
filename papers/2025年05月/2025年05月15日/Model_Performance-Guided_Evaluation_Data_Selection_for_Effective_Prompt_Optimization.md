# 基于模型性能的评估数据选择，助力有效提示优化

发布时间：2025年05月15日

`LLM应用` `大型语言模型` `机器学习`

> Model Performance-Guided Evaluation Data Selection for Effective Prompt Optimization

# 摘要

> 优化大型语言模型（LLM）性能需要精心设计的提示，但手动提示工程耗时且低效。自动化提示优化技术虽解决了这一难题，但大多数方法依赖随机选择的评估子集，无法代表完整数据集，导致评估不可靠、提示效果不佳。现有的核心集选择方法专为LLM基准测试设计，但由于聚类相似样本困难、数据收集成本高昂以及新数据集或私有数据集缺乏性能数据等问题，不适合用于提示优化。为解决这些问题，我们提出IPOMP（迭代评估数据选择用于有效提示优化，基于实时模型性能）。IPOMP采用两阶段方法：首先利用语义聚类和边界分析选择具有代表性和多样性的样本，然后通过实时模型性能数据迭代优化，替换冗余样本。在BIG-bench数据集上的评估表明，与现有最优基线相比，IPOMP在有效性方面提升了1.6%至5.3%，稳定性提升了至少57%，同时计算开销极低，低于1%。此外，结果表明，我们基于实时性能引导的优化方法具有普适性，可用于提升现有核心集选择方法。

> Optimizing Large Language Model (LLM) performance requires well-crafted prompts, but manual prompt engineering is labor-intensive and often ineffective. Automated prompt optimization techniques address this challenge but the majority of them rely on randomly selected evaluation subsets, which fail to represent the full dataset, leading to unreliable evaluations and suboptimal prompts. Existing coreset selection methods, designed for LLM benchmarking, are unsuitable for prompt optimization due to challenges in clustering similar samples, high data collection costs, and the unavailability of performance data for new or private datasets. To overcome these issues, we propose IPOMP, an Iterative evaluation data selection for effective Prompt Optimization using real-time Model Performance. IPOMP is a two-stage approach that selects representative and diverse samples using semantic clustering and boundary analysis, followed by iterative refinement with real-time model performance data to replace redundant samples. Evaluations on the BIG-bench dataset show that IPOMP improves effectiveness by 1.6% to 5.3% and stability by at least 57% compared with SOTA baselines, with minimal computational overhead below 1%. Furthermore, the results demonstrate that our real-time performance-guided refinement approach can be universally applied to enhance existing coreset selection methods.

[Arxiv](https://arxiv.org/abs/2505.10736)