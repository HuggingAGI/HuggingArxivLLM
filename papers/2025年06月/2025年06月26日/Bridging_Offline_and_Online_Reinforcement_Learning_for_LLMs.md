# 连接离线与在线强化学习，在LLMs中实现桥梁作用

发布时间：2025年06月26日

`LLM应用

摘要讨论了强化学习方法在微调大型语言模型（LLM）中的应用，特别是在线和半在线模式下的直接偏好优化（DPO）和组奖励策略优化（GRPO）目标。研究关注的是如何优化LLM的训练过程，属于应用层面的研究。` `机器学习`

> Bridging Offline and Online Reinforcement Learning for LLMs

# 摘要

> 我们研究了强化学习方法在从离线到半在线再到完全在线模式下微调大型语言模型的有效性，适用于可验证和不可验证的任务。实验涵盖了可验证数学和不可验证指令遵循的训练，并为两者提供了基准评估。在这些设置中，我们广泛比较了在线和半在线的直接偏好优化（DPO）和组奖励策略优化（GRPO）目标，令人惊讶的是，这些变体在性能和收敛性上表现相似，且均显著优于离线方法。我们详细分析了训练动力学和超参数选择策略，以实现最佳结果。最后，我们展示了同时使用可验证和不可验证奖励的多任务学习在两种任务类型上都取得了更好的性能。

> We investigate the effectiveness of reinforcement learning methods for finetuning large language models when transitioning from offline to semi-online to fully online regimes for both verifiable and non-verifiable tasks. Our experiments cover training on verifiable math as well as non-verifiable instruction following with a set of benchmark evaluations for both. Across these settings, we extensively compare online and semi-online Direct Preference Optimization and Group Reward Policy Optimization objectives, and surprisingly find similar performance and convergence between these variants, which all strongly outperform offline methods. We provide a detailed analysis of the training dynamics and hyperparameter selection strategies to achieve optimal results. Finally, we show that multi-tasking with verifiable and non-verifiable rewards jointly yields improved performance across both task types.

[Arxiv](https://arxiv.org/abs/2506.21495)