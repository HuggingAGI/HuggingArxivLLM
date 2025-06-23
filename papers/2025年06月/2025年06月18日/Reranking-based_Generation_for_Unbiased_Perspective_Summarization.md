# 基于重排序的生成实现无偏见视角的摘要

发布时间：2025年06月18日

`LLM应用` `摘要生成`

> Reranking-based Generation for Unbiased Perspective Summarization

# 摘要

> 在实际应用场景中生成无偏见的摘要（例如政治观点总结）仍是大型语言模型（LLMs）的一项关键应用。然而，现有的评估框架依赖于传统的指标来衡量关键属性（如覆盖范围和忠实度），而没有验证这些指标的适用性，同时改进摘要生成器的努力仍处于初期阶段。我们通过以下两个方面来解决这些问题：（1）识别可靠的指标来衡量观点摘要的质量；（2）研究基于LLMs的方法在零-shot推理之外的有效性。具体来说，我们构建了一个测试集，用于通过人工标注来评估指标的可靠性，并表明传统指标的表现不如基于语言模型的指标，后者被证明是强大的评估工具。利用这些指标，我们展示了基于重排序的方法能够产生强大的结果，并且通过使用合成生成并带有重排序标签的数据进行偏好调优，性能可以进一步提升。我们的研究发现旨在为观点摘要方法的可靠评估和开发做出贡献。

> Generating unbiased summaries in real-world settings such as political perspective summarization remains a crucial application of Large Language Models (LLMs). Yet, existing evaluation frameworks rely on traditional metrics for measuring key attributes such as coverage and faithfulness without verifying their applicability, and efforts to develop improved summarizers are still nascent. We address these gaps by (1) identifying reliable metrics for measuring perspective summary quality, and (2) investigating the efficacy of LLM-based methods beyond zero-shot inference. Namely, we build a test set for benchmarking metric reliability using human annotations and show that traditional metrics underperform compared to language model-based metrics, which prove to be strong evaluators. Using these metrics, we show that reranking-based methods yield strong results, and preference tuning with synthetically generated and reranking-labeled data further boosts performance. Our findings aim to contribute to the reliable evaluation and development of perspective summarization methods.

[Arxiv](https://arxiv.org/abs/2506.15925)