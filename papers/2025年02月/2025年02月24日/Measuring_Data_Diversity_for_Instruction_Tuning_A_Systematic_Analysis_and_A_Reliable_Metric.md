# 衡量指令微调中的数据多样性：系统性分析与可靠指标

发布时间：2025年02月24日

`LLM应用` `数据工程` `机器学习`

> Measuring Data Diversity for Instruction Tuning: A Systematic Analysis and A Reliable Metric

# 摘要

> 数据多样性是大型语言模型指令微调中不可或缺的因素。尽管现有研究已经探索了多种考虑多样性的数据选择方法来构建高质量数据集并提升模型性能，但如何精确定义和衡量数据多样性这一核心问题仍未得到充分解决，这为数据工程实践带来了诸多挑战。为了解决这一难题，我们通过广泛的微调实验，系统性地分析了11种现有多样性衡量方法与模型性能之间的关系。研究结果表明，可靠的多样性衡量指标应当能够恰当反映样本间差异以及样本空间中的信息分布。基于此，我们提出了基于样本级别“新颖性”的新多样性指标NovelSum。无论是模拟数据还是真实世界数据的实验结果均表明，NovelSum能够准确捕捉数据多样性变化，并与指令微调模型性能达到0.97的相关性，充分展现了其在指导数据工程实践中的重要价值。以NovelSum作为优化目标，我们进一步开发了一种面向多样性的贪心数据选择策略，其性能超越现有方法，充分验证了我们的指标在有效性和实际意义方面均表现优异。

> Data diversity is crucial for the instruction tuning of large language models. Existing studies have explored various diversity-aware data selection methods to construct high-quality datasets and enhance model performance. However, the fundamental problem of precisely defining and measuring data diversity remains underexplored, limiting clear guidance for data engineering. To address this, we systematically analyze 11 existing diversity measurement methods by assessing their correlation with model performance through extensive fine-tuning experiments. Our results indicate that a reliable diversity measure should properly account for both inter-sample differences and the information distribution in the sample space. Building on this, we propose NovelSum, a new diversity metric based on sample-level "novelty." Experiments on both simulated and real-world data show that NovelSum accurately captures diversity variations and achieves a 0.97 correlation with instruction-tuned model performance, highlighting its value in guiding data engineering practices. With NovelSum as an optimization objective, we further develop a greedy, diversity-oriented data selection strategy that outperforms existing approaches, validating both the effectiveness and practical significance of our metric.

[Arxiv](https://arxiv.org/abs/2502.17184)