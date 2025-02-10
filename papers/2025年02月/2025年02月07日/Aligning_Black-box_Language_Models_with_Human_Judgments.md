# # 标题
让黑箱语言模型与人类判断携手同行

发布时间：2025年02月07日

`LLM应用

论文摘要讨论了大型语言模型在评估推荐系统和搜索引擎等主观任务中的应用，提出了一个使LLM评估结果与人工评估一致的框架。这属于LLM的应用层面。` `信息检索` `推荐系统`

> Aligning Black-box Language Models with Human Judgments

# 摘要

> 大型语言模型（LLMs）正越来越多地被用于评估推荐系统、搜索引擎等主观任务，取代成本高昂、耗时且难以扩展的人工评估。LLMs 为持续、自动化的评估提供了高效解决方案。然而，由于这些系统最终是为人设计的，必须确保 LLM 的评估结果与人工评估高度一致，以确保系统始终以人类为中心。然而，由于人类评估中的个体差异和偏见，这一目标颇具挑战性。我们提出了一种简单而有效的框架，在不重新训练或微调 LLM 的情况下，使其评估结果与人工评估保持一致。我们的方法通过学习 LLM 输出与人工评估之间的线性映射关系，在仅使用少量校准样例的情况下，实现了在 29 项任务上的平均改进率超过 142%。值得注意的是，我们的方法在零样本和少样本设置下表现优异，在六项任务中的四项上超过了人与人之间的评估一致性，并使较小规模的 LLM 能够达到与更大模型相当的性能水平。

> Large language models (LLMs) are increasingly used as automated judges to evaluate recommendation systems, search engines, and other subjective tasks, where relying on human evaluators can be costly, time-consuming, and unscalable. LLMs offer an efficient solution for continuous, automated evaluation. However, since the systems that are built and improved with these judgments are ultimately designed for human use, it is crucial that LLM judgments align closely with human evaluators to ensure such systems remain human-centered. On the other hand, aligning LLM judgments with human evaluators is challenging due to individual variability and biases in human judgments. We propose a simple yet effective framework to align LLM judgments with individual human evaluators or their aggregated judgments, without retraining or fine-tuning the LLM. Our approach learns a linear mapping between the LLM's outputs and human judgments, achieving over 142% average improvement in agreement across 29 tasks with only a small number of calibration examples used for training. Notably, our method works in zero-shot and few-shot settings, exceeds inter-human agreement on four out of six tasks, and enables smaller LLMs to achieve performance comparable to that of larger models.

[Arxiv](https://arxiv.org/abs/2502.04997)