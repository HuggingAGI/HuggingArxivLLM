# # COSMOS：LLMs的可预测与经济实惠的适配方案

发布时间：2025年04月29日

`LLM理论` `云计算` `大数据处理`

> COSMOS: Predictable and Cost-Effective Adaptation of LLMs

# 摘要

> 大型语言模型 (LLMs) 通过多样化的适应策略在各类任务中表现出色。然而，在资源受限的情况下，如何优化选择模型和策略仍具挑战性，通常需大量实验。我们研究是否能在不进行昂贵试验的情况下，准确预测性能和成本。我们对 LLM 的策略选择问题进行了形式化定义，并引入了 COSMOS，一个统一的预测框架，能够在成本最低的情况下高效估计适应结果。我们通过两个强大的预测器来实现并研究框架的能力：嵌入增强的轻量级代理模型用于预测微调性能，以及低样本规模定律用于预测增强的上下文学习效果。在八个代表性基准上的广泛评估表明，COSMOS 在保持高预测准确性的同时，平均将计算成本降低了 92.72%，在资源密集型场景中最高可降低 98.71%。我们的结果表明，对适应结果的高效预测不仅是可行的，而且可以在减少 LLM 部署的计算开销的同时保持性能标准。

> Large language models (LLMs) achieve remarkable performance across numerous tasks by using a diverse array of adaptation strategies. However, optimally selecting a model and adaptation strategy under resource constraints is challenging and often requires extensive experimentation. We investigate whether it is possible to accurately predict both performance and cost without expensive trials. We formalize the strategy selection problem for LLMs and introduce COSMOS, a unified prediction framework that efficiently estimates adaptation outcomes at minimal cost. We instantiate and study the capability of our framework via a pair of powerful predictors: embedding-augmented lightweight proxy models to predict fine-tuning performance, and low-sample scaling laws to forecast retrieval-augmented in-context learning. Extensive evaluation across eight representative benchmarks demonstrates that COSMOS achieves high prediction accuracy while reducing computational costs by 92.72% on average, and up to 98.71% in resource-intensive scenarios. Our results show that efficient prediction of adaptation outcomes is not only feasible but can substantially reduce the computational overhead of LLM deployment while maintaining performance standards.

[Arxiv](https://arxiv.org/abs/2505.01449)