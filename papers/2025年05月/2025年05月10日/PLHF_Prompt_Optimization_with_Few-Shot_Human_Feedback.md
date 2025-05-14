# PLHF: 基于少量人工反馈的提示优化

发布时间：2025年05月10日

`LLM应用

摘要讨论了优化大型语言模型提示的方法，属于应用层面的研究，因此归类为LLM应用。` `人工智能` `机器学习`

> PLHF: Prompt Optimization with Few-Shot Human Feedback

# 摘要

> 自动提示优化框架旨在为大型语言模型（LLMs）生成适合其预期输出质量指标的提示。现有方法在处理固定答案的问题上表现良好，但在输出质量难以通过与标准答案比较来评估时，定义指标变得复杂。因此，在没有明确指标的情况下有效优化提示成为一个关键挑战。为了解决这一问题，我们提出了PLHF框架，它受到著名的RLHF技术启发，是一个基于少量样本的提示优化框架。与简单的策略不同，PLHF使用特定的评估模块作为指标来估计输出质量。PLHF只需要一轮人工反馈就能完成整个提示优化过程。在公共和工业数据集上的实证结果表明，PLHF在LLM提示优化中优于之前的输出评分策略。

> Automatic prompt optimization frameworks are developed to obtain suitable prompts for large language models (LLMs) with respect to desired output quality metrics. Although existing approaches can handle conventional tasks such as fixed-solution question answering, defining the metric becomes complicated when the output quality cannot be easily assessed by comparisons with standard golden samples. Consequently, optimizing the prompts effectively and efficiently without a clear metric becomes a critical challenge. To address the issue, we present PLHF (which stands for "P"rompt "L"earning with "H"uman "F"eedback), a few-shot prompt optimization framework inspired by the well-known RLHF technique. Different from naive strategies, PLHF employs a specific evaluator module acting as the metric to estimate the output quality. PLHF requires only a single round of human feedback to complete the entire prompt optimization process. Empirical results on both public and industrial datasets show that PLHF outperforms prior output grading strategies for LLM prompt optimizations.

[Arxiv](https://arxiv.org/abs/2505.07886)