# 多变量符合性选择

发布时间：2025年05月01日

`其他` `医疗健康` `数据科学`

> Multivariate Conformal Selection

# 摘要

> 在药物发现、精准医疗和大型语言模型 (LLMs) 对齐等关键应用中，如何从海量数据中高效筛选出高质量候选者至关重要。虽然传统的符合性选择 (CS) 方法提供了严格的不确定性量化，但其应用范围仅限于单变量响应和标量标准。为突破这一限制，我们提出了多元符合性选择 (mCS)，这一创新性方法将 CS 的适用范围扩展至多元响应场景。通过引入区域单调性和多元非符合性分数，mCS 实现了有限样本量下的错误发现率 (FDR) 控制。我们进一步开发了两种实用变体：基于距离分数的 mCS-dist，以及通过可微优化学习最优分数的 mCS-learn。在模拟和真实世界数据集上的实验结果表明，mCS 不仅显著提升了选择能力，同时保持了严格的 FDR 控制，从而为多元选择任务提供了一个强大可靠的框架。

> Selecting high-quality candidates from large datasets is critical in applications such as drug discovery, precision medicine, and alignment of large language models (LLMs). While Conformal Selection (CS) provides rigorous uncertainty quantification, it is limited to univariate responses and scalar criteria. To address this issue, we propose Multivariate Conformal Selection (mCS), a generalization of CS designed for multivariate response settings. Our method introduces regional monotonicity and employs multivariate nonconformity scores to construct conformal p-values, enabling finite-sample False Discovery Rate (FDR) control. We present two variants: mCS-dist, using distance-based scores, and mCS-learn, which learns optimal scores via differentiable optimization. Experiments on simulated and real-world datasets demonstrate that mCS significantly improves selection power while maintaining FDR control, establishing it as a robust framework for multivariate selection tasks.

[Arxiv](https://arxiv.org/abs/2505.00917)