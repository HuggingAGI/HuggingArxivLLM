# 利用单一算法，从on-policy和off-policy数据中微调大型语言模型的强化学习方法。

发布时间：2025年03月25日

`LLM应用` `数学推理`

> RL-finetuning LLMs from on- and off-policy data with a single algorithm

# 摘要

> 我们提出了一种新型强化学习算法 AGRO（Any-Generation Reward Optimization），用于微调大型语言模型。AGRO 算法基于生成一致性概念，即最优策略在模型的任何可能生成中都保持一致。我们通过基于样本的策略梯度方法推导出寻找最优解的算法，并提供了理论保证以确保其收敛性。实验结果表明，AGRO 在 both on-policy 和 off-policy 设置下均表现优异，并在数学推理数据集上显著超越了基线算法。

> We introduce a novel reinforcement learning algorithm (AGRO, for Any-Generation Reward Optimization) for fine-tuning large-language models. AGRO leverages the concept of generation consistency, which states that the optimal policy satisfies the notion of consistency across any possible generation of the model. We derive algorithms that find optimal solutions via the sample-based policy gradient and provide theoretical guarantees on their convergence. Our experiments demonstrate the effectiveness of AGRO in both on-policy and off-policy settings, showing improved performance on the mathematical reasoning dataset over baseline algorithms.

[Arxiv](https://arxiv.org/abs/2503.19612)