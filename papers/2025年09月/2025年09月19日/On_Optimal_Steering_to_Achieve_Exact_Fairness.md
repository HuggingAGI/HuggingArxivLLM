# # 论实现精确公平的最优引导

发布时间：2025年09月19日

`LLM应用` `基础理论`

> On Optimal Steering to Achieve Exact Fairness

# 摘要

> 为解决公平机器学习中“输入有偏，输出有偏”的难题，关键在于将数据的特征分布或大型语言模型（LLMs）的内部表示引导至理想分布——这类分布能确保群体公平结果。在公平生成模型与表示引导领域，先前研究若能为模型输出提供可证明的公平性保证，其价值将大幅提升。我们将理想分布定义为：在该分布上，任何成本敏感风险的最小化器都能确保精确的群体公平结果（如人口统计学平等、机会平等），即不存在公平与效用的权衡。我们提出通过KL散度寻找最近的理想分布，构建最优引导的优化方案；当基础分布属于常见参数族（如正态分布、对数正态分布）时，还提供了高效求解算法。实验验证，无论是合成数据还是真实数据集，我们的最优引导技术均能在不降低效用的前提下提升公平性（有时甚至能增强效用）。例如，在Bios数据集（De-Arteaga等人）中，我们通过对LLM表示的仿射引导，有效减少了基于短传记文本预测职业时的多分类偏差。此外，我们还将LLM的内部表示引导至期望输出，使其在不同群体上表现一致。

> To fix the 'bias in, bias out' problem in fair machine learning, it is important to steer feature distributions of data or internal representations of Large Language Models (LLMs) to ideal ones that guarantee group-fair outcomes. Previous work on fair generative models and representation steering could greatly benefit from provable fairness guarantees on the model output. We define a distribution as ideal if the minimizer of any cost-sensitive risk on it is guaranteed to have exact group-fair outcomes (e.g., demographic parity, equal opportunity)-in other words, it has no fairness-utility trade-off. We formulate an optimization program for optimal steering by finding the nearest ideal distribution in KL-divergence, and provide efficient algorithms for it when the underlying distributions come from well-known parametric families (e.g., normal, log-normal). Empirically, our optimal steering techniques on both synthetic and real-world datasets improve fairness without diminishing utility (and sometimes even improve utility). We demonstrate affine steering of LLM representations to reduce bias in multi-class classification, e.g., occupation prediction from a short biography in Bios dataset (De-Arteaga et al.). Furthermore, we steer internal representations of LLMs towards desired outputs so that it works equally well across different groups.

[Arxiv](https://arxiv.org/abs/2509.15759)