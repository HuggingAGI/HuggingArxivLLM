# R.I.P.: 适者生存的提示，打造更优模型

发布时间：2025年01月30日

`LLM应用

**解释**：这篇论文主要讨论了如何通过改进训练数据的质量来提升大型语言模型（LLM）的表现。具体来说，它提出了一种名为“拒绝指令偏好”（RIP）的方法，用于过滤低质量的提示或生成高质量的合成数据集，从而显著提升模型在各种基准测试中的表现。这种方法直接应用于LLM的训练和优化过程，因此属于LLM应用的范畴。` `机器学习` `数据质量`

> R.I.P.: Better Models by Survival of the Fittest Prompts

# 摘要

> 训练数据的质量是决定模型最终表现的关键因素之一。本文提出了一种基于低质量输入提示会导致高方差和低质量响应的假设来评估数据完整性的方法。通过测量被拒绝响应的质量以及所选和被拒绝偏好对之间的奖励差距，我们的方法——拒绝指令偏好（RIP）——可用于从现有训练集中过滤提示，或生成高质量的合成数据集。与未过滤的数据相比，RIP 在各种基准测试中带来了显著的性能提升。使用 Llama 3.1-8B-Instruct，RIP 将 AlpacaEval2 LC 胜率提高了 9.4%，Arena-Hard 提高了 8.7%，WildBench 提高了 9.9%。使用 Llama 3.3-70B-Instruct，RIP 将 Arena-Hard 从 67.5 提升至 82.9，使模型在排行榜上的排名从第 18 位跃升至第 6 位。

> Training data quality is one of the most important drivers of final model quality. In this work, we introduce a method for evaluating data integrity based on the assumption that low-quality input prompts result in high variance and low quality responses. This is achieved by measuring the rejected response quality and the reward gap between the chosen and rejected preference pair. Our method, Rejecting Instruction Preferences (RIP) can be used to filter prompts from existing training sets, or to make high quality synthetic datasets, yielding large performance gains across various benchmarks compared to unfiltered data. Using Llama 3.1-8B-Instruct, RIP improves AlpacaEval2 LC Win Rate by 9.4%, Arena-Hard by 8.7%, and WildBench by 9.9%. Using Llama 3.3-70B-Instruct, RIP improves Arena-Hard from 67.5 to 82.9, which is from 18th place to 6th overall in the leaderboard.

[Arxiv](https://arxiv.org/abs/2501.18578)