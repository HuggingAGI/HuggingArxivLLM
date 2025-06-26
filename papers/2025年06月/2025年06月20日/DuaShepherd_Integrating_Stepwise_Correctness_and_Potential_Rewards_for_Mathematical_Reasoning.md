# DuaShepherd：数学推理中整合逐步正确性和潜在奖励。

发布时间：2025年06月20日

`LLM理论` `人工智能`

> DuaShepherd: Integrating Stepwise Correctness and Potential Rewards for Mathematical Reasoning

# 摘要

> 本文提出了一种创新的奖励建模框架 DuaShepherd，通过整合正确性和潜在性两种互补信号，显著提升了大型语言模型 (LLMs) 的数学推理能力。基于正确性的信号专注于逐步识别错误，而基于潜在性的信号则评估最终正确答案的可能性。我们设计了一个自动化管道，用于构建大规模奖励建模数据集，涵盖这两种关键信号。通过采用统一的多头架构，在多任务训练中同时学习正确性和潜在性，我们发现这种并行学习方式具有显著优势。将这两种信号融合成一个复合概率后，我们的模型在多个基准测试中均表现出色。实证评估显示，在 MATH500 和 ProcessBench 数据集上，这种结合奖励的方法显著优于仅基于单一奖励类型训练的模型，即使在资源约束相似的情况下，也达到了当前最先进的性能水平。

> In this paper, we propose DuaShepherd, a novel reward modeling framework that integrates two complementary reward signals, correctness and potential, to enhance the mathematical reasoning capabilities of Large Language Models (LLMs). While correctness-based signals emphasize identification of stepwise errors, potential-based signals focus on the likelihood of reaching the correct final answer. We developed an automated pipeline for constructing large-scale reward modeling dataset with both signals. A unified, multi-head architecture was explored to train the two reward models in a multi-task setup, demonstrating benefits from learning both correctness and potential in parallel. By combining these two signals into a compound probability, our model achieves consistent performance improvements across multiple benchmarks. Empirical evaluations on MATH500 and ProcessBench confirm that this combined reward significantly outperforms models trained on either reward type alone, achieving state-of-the-art performance under comparable resource constraints.

[Arxiv](https://arxiv.org/abs/2506.17533)