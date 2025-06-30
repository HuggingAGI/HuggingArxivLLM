# 大型语言模型不确定性量化中的“一致性假设”

发布时间：2025年06月26日

`LLM理论

摘要中讨论了大型语言模型的置信度估计和不确定性量化（UQ）方法，研究了生成一致性作为置信度的替代指标，并通过数学和统计方法验证了这些假设。这属于对模型理论的深入探讨，因此归类为LLM理论。` `不确定性量化`

> The Consistency Hypothesis in Uncertainty Quantification for Large Language Models

# 摘要

> 大型语言模型（LLM）输出的置信度估计在需要用户高度信任的现实应用中至关重要。仅依赖模型API访问的黑盒不确定性量化（UQ）方法因其实际优势而备受关注。本文深入探讨了几种UQ方法背后的隐含假设，这些方法将生成一致性作为置信度的替代指标，我们将其形式化为一致性假设。通过三个数学陈述及其统计测试，我们捕捉了这一假设的不同变体，并提出了评估LLM输出在不同任务中一致性的指标。基于8个基准数据集和3个任务（问答、文本摘要和文本到SQL）的实证研究，我们揭示了该假设在不同设置下的普遍性。在这些陈述中，`Sim-Any'假设因其可操作性脱颖而出，我们展示了如何通过提出基于生成之间相似性聚合的无数据黑盒UQ方法来利用它，从而实现置信度估计。这些方法在性能上超越了最接近的基线，充分体现了实证观察到的一致性假设的实际价值。

> Estimating the confidence of large language model (LLM) outputs is essential for real-world applications requiring high user trust. Black-box uncertainty quantification (UQ) methods, relying solely on model API access, have gained popularity due to their practical benefits. In this paper, we examine the implicit assumption behind several UQ methods, which use generation consistency as a proxy for confidence, an idea we formalize as the consistency hypothesis. We introduce three mathematical statements with corresponding statistical tests to capture variations of this hypothesis and metrics to evaluate LLM output conformity across tasks. Our empirical investigation, spanning 8 benchmark datasets and 3 tasks (question answering, text summarization, and text-to-SQL), highlights the prevalence of the hypothesis under different settings. Among the statements, we highlight the `Sim-Any' hypothesis as the most actionable, and demonstrate how it can be leveraged by proposing data-free black-box UQ methods that aggregate similarities between generations for confidence estimation. These approaches can outperform the closest baselines, showcasing the practical value of the empirically observed consistency hypothesis.

[Arxiv](https://arxiv.org/abs/2506.21849)