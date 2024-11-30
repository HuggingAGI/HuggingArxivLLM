# 针对大型语言模型（LLM）的Text-to-SQL转换能力，本研究进行了深入且全面的基准评测。

发布时间：2024年03月05日

`LLM应用`

> Benchmarking the Text-to-SQL Capability of Large Language Models: A Comprehensive Evaluation

# 摘要

> 随着LLMs在Text-to-SQL任务上展现出强大实力，其性能远超传统方法，但关于最优提示模板和设计框架的选择仍存在争议，且当前基准测试未能全面考察LLMs在该任务各子阶段的表现，限制了对LLMs认知能力和相关解决方案优化的评估。为此，我们首先精心设计了一种新数据集以减轻LLMs过拟合的风险，接着设立了五个评价任务，全方位审视多种LLMs在Text-to-SQL全流程中的表现差异。研究过程中，我们揭示了不同LLMs间性能的显著差距，并针对各个任务定制了最优的ICL策略。这些重要发现为提升基于LLM的Text-to-SQL系统的开发质量提供了极具价值的洞见。

> Large Language Models (LLMs) have emerged as a powerful tool in advancing the Text-to-SQL task, significantly outperforming traditional methods. Nevertheless, as a nascent research field, there is still no consensus on the optimal prompt templates and design frameworks. Additionally, existing benchmarks inadequately explore the performance of LLMs across the various sub-tasks of the Text-to-SQL process, which hinders the assessment of LLMs' cognitive capabilities and the optimization of LLM-based solutions.To address the aforementioned issues, we firstly construct a new dataset designed to mitigate the risk of overfitting in LLMs. Then we formulate five evaluation tasks to comprehensively assess the performance of diverse methods across various LLMs throughout the Text-to-SQL process.Our study highlights the performance disparities among LLMs and proposes optimal in-context learning solutions tailored to each task. These findings offer valuable insights for enhancing the development of LLM-based Text-to-SQL systems.

[Arxiv](https://arxiv.org/abs/2403.02951)