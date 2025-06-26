# DuaShepherd：融合逐步正确性与潜在奖励提升数学推理能力

发布时间：2025年06月20日

`LLM理论`

> DuaShepherd: Integrating Stepwise Correctness and Potential Rewards for Mathematical Reasoning

# 摘要

> 本文提出了一种名为DuaShepherd的创新奖励建模框架，通过整合正确性和潜力两大互补奖励信号，助力提升大型语言模型（LLMs）的数学推理能力。其中，基于正确性的奖励信号专注于逐步错误的识别，而基于潜力的信号则着眼于最终正确答案的可能性。我们开发了一套自动化流水线，用于构建包含这两种信号的大规模奖励建模数据集。通过采用统一的多头架构，在多任务环境下同步训练这两个奖励模型，充分展现了并行学习正确性和潜力的优势。将这两种信号整合为一个复合概率后，我们的模型在多个基准测试中均实现了显著的性能提升。实证评估显示，在MATH500和ProcessBench数据集上，这种组合奖励较单一奖励类型训练的模型表现更优，并在资源约束相似的情况下达到了当前最佳性能水平。

> In this paper, we propose DuaShepherd, a novel reward modeling framework that integrates two complementary reward signals, correctness and potential, to enhance the mathematical reasoning capabilities of Large Language Models (LLMs). While correctness-based signals emphasize identification of stepwise errors, potential-based signals focus on the likelihood of reaching the correct final answer. We developed an automated pipeline for constructing large-scale reward modeling dataset with both signals. A unified, multi-head architecture was explored to train the two reward models in a multi-task setup, demonstrating benefits from learning both correctness and potential in parallel. By combining these two signals into a compound probability, our model achieves consistent performance improvements across multiple benchmarks. Empirical evaluations on MATH500 and ProcessBench confirm that this combined reward significantly outperforms models trained on either reward type alone, achieving state-of-the-art performance under comparable resource constraints.

[Arxiv](https://arxiv.org/abs/2506.17533)