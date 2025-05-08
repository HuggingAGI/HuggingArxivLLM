# Cer-Eval：可认证且成本高效的LLM评估体系

发布时间：2025年05月02日

`LLM理论` `人工智能` `数据科学`

> Cer-Eval: Certifiable and Cost-Efficient Evaluation Framework for LLMs

# 摘要

> 随着基础模型的持续扩展，模型规模呈指数级增长，这为模型评估带来了重大挑战。目前的评估实践依赖于整理日益庞大的数据集来评估大型语言模型（LLMs）的性能。然而，目前尚缺乏系统性的分析和指导来确定测试数据的充分性或选择有代表性的样本用于评估。本文提出了一种可认证且成本高效的大型语言模型评估框架。我们的框架能够灵活适应不同的评估目标，并输出高概率包含真实值的置信区间。我们通过“测试样本复杂度”量化认证评估所需的测试点数量，并推导出测试样本复杂度的紧致界限。基于此理论，我们开发了一种基于分区的算法——Cer-Eval，该算法能够自适应地选择测试点，从而显著降低大型语言模型评估的成本。实验证明，Cer-Eval在各种基准测试中可节省20%至40%的测试点，同时保持与当前评估过程相当的估计误差水平，并提供95%的置信保证。

> As foundation models continue to scale, the size of trained models grows exponentially, presenting significant challenges for their evaluation. Current evaluation practices involve curating increasingly large datasets to assess the performance of large language models (LLMs). However, there is a lack of systematic analysis and guidance on determining the sufficiency of test data or selecting informative samples for evaluation. This paper introduces a certifiable and cost-efficient evaluation framework for LLMs. Our framework adapts to different evaluation objectives and outputs confidence intervals that contain true values with high probability. We use ``test sample complexity'' to quantify the number of test points needed for a certifiable evaluation and derive tight bounds on test sample complexity. Based on the developed theory, we develop a partition-based algorithm, named Cer-Eval, that adaptively selects test points to minimize the cost of LLM evaluation. Real-world experiments demonstrate that Cer-Eval can save 20% to 40% test points across various benchmarks, while maintaining an estimation error level comparable to the current evaluation process and providing a 95% confidence guarantee.

[Arxiv](https://arxiv.org/abs/2505.03814)