# # 奖励建模中的基础模型选择系统性分析
系统性分析奖励建模中的基础模型选择

发布时间：2025年05月15日

`LLM理论` `人工智能`

> A Systematic Analysis of Base Model Choice for Reward Modeling

# 摘要

> 强化学习从人类反馈中学习（RLHF）及其核心——奖励建模——已成为训练强大大型语言模型（LLMs）的关键部分。在训练高质量奖励模型（RMs）时，一个常被忽视的因素是基础模型的影响，随着LLMs数量的快速增长，选择合适的模型变得更具挑战性。在本研究中，我们系统地分析了基础模型选择对奖励建模性能的影响。我们的结果显示，与最常见的（即默认）选择相比，性能可以提升高达14%。此外，我们展示了现有基准与下游性能之间存在的强统计关系。我们还证明，通过结合一小部分基准的结果，可以显著提升模型选择的效果（前5-10名的平均提升为+18%）。最后，我们探讨了不同后训练步骤对最终性能的影响，并研究了利用估计的数据分布来减少性能预测误差的可能性。

> Reinforcement learning from human feedback (RLHF) and, at its core, reward modeling have become a crucial part of training powerful large language models (LLMs). One commonly overlooked factor in training high-quality reward models (RMs) is the effect of the base model, which is becoming more challenging to choose given the rapidly growing pool of LLMs. In this work, we present a systematic analysis of the effect of base model selection on reward modeling performance. Our results show that the performance can be improved by up to 14% compared to the most common (i.e., default) choice. Moreover, we showcase the strong statistical relation between some existing benchmarks and downstream performances. We also demonstrate that the results from a small set of benchmarks could be combined to boost the model selection ($+$18% on average in the top 5-10). Lastly, we illustrate the impact of different post-training steps on the final performance and explore using estimated data distributions to reduce performance prediction error.

[Arxiv](https://arxiv.org/abs/2505.10775)