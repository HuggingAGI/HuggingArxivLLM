# 自适应分组策略优化：致力于稳定训练与高效的代词推理能力

发布时间：2025年03月20日

`LLM理论` `人工智能` `机器学习`

> Adaptive Group Policy Optimization: Towards Stable Training and Token-Efficient Reasoning

# 摘要

> 自 DeepSeek-R1 问世以来，组相对策略优化（GRPO）已成为推理型大语言模型（LLMs）训练的核心技术。然而，我们在实践中发现传统方法存在影响强化学习稳定性与推理效率的不足。为此，我们提出了自适应组策略优化（AGPO），其中包含两个关键改进：一种修正的优势估计方法，能够有效缓解零方差问题；一种基于长度的奖励机制，激励模型避免不必要的过度思考。实验结果表明，我们的方法不仅训练更稳定，而且在推理步骤中以显著更少的tokens实现了相当甚至更优的性能表现。

> Since DeepSeek-R1 popularized, Group Relative Policy Optimization (GRPO) has become the core part of Reasoning LLMs training. However, we find some deficiency that influences RL stability and inference efficiency. Thus, we propose Adaptive Group Policy Optimization (AGPO) which contains two simple but effective modifications: a revised advantage estimation method to mitigate zero-variance situations; a length-based reward, incentivizing the model to avoid overthinking. The experiments demonstrate our methods achieve more stable training and comparable or superior performance with significantly fewer tokens in reasoning steps.

[Arxiv](https://arxiv.org/abs/2503.15952)