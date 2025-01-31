# LLM系统预测性能的统计多指标评估与可视化

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何评估基于大型语言模型（LLM）的系统，并提出了一个框架来自动执行统计测试、汇总结果并可视化。这涉及到对LLM在不同配置下的性能进行评估和比较，属于LLM在实际应用中的评估和优化问题，因此归类为“LLM应用”。` `代码生成`

> Statistical multi-metric evaluation and visualization of LLM system predictive performance

# 摘要

> 基于生成式或判别式大型语言模型（LLM）的系统评估通常是一个复杂的多维度问题。通常，我们会在一组基准数据集上评估多个系统配置备选方案，每个数据集可能使用不同的评估指标。我们希望通过统计显著性来衡量系统在单一指标、跨指标汇总或跨数据集上的表现差异。这类评估可用于决策支持，例如判断某个系统组件的更改（如LLM选择或超参数调整）是否显著提升了性能，或者一组固定配置（如排行榜列表）是否在关键指标上表现显著不同。我们提出了一个框架，能够自动执行正确的统计测试，跨指标和数据集汇总统计结果（这是一项复杂任务），并可视化结果。该框架已在多语言代码生成基准CrossCodeEval上验证，适用于多种最先进的LLM。

> The evaluation of generative or discriminative large language model (LLM)-based systems is often a complex multi-dimensional problem. Typically, a set of system configuration alternatives are evaluated on one or more benchmark datasets, each with one or more evaluation metrics, which may differ between datasets. We often want to evaluate -- with a statistical measure of significance -- whether systems perform differently either on a given dataset according to a single metric, on aggregate across metrics on a dataset, or across datasets. Such evaluations can be done to support decision-making, such as deciding whether a particular system component change (e.g., choice of LLM or hyperparameter values) significantly improves performance over the current system configuration, or, more generally, whether a fixed set of system configurations (e.g., a leaderboard list) have significantly different performances according to metrics of interest. We present a framework implementation that automatically performs the correct statistical tests, properly aggregates the statistical results across metrics and datasets (a nontrivial task), and can visualize the results. The framework is demonstrated on the multi-lingual code generation benchmark CrossCodeEval, for several state-of-the-art LLMs.

[Arxiv](https://arxiv.org/abs/2501.18243)