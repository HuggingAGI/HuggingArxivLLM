# RePO：基于回放增强的策略优化方法

发布时间：2025年06月10日

`LLM应用` `人工智能`

> RePO: Replay-Enhanced Policy Optimization

# 摘要

> 强化学习（RL）在优化大型语言模型（LLMs）中扮演着关键角色。近期的组相对策略优化（GRPO）方法通过每个提示使用多个在线策略输出来估计优势，但这种做法导致了高昂的计算成本和低数据效率。为了解决这一问题，我们提出了回放增强策略优化（RePO），该方法通过多样化的回放策略从回放缓冲区中检索离线策略样本，从而能够基于每个提示更广泛且多样的样本集进行策略优化。在涵盖七个数学推理基准的五种大型语言模型上进行的实验表明，与GRPO相比，RePO为Qwen2.5-Math-1.5B和Qwen3-1.7B分别带来了绝对平均性能提升，具体为18.4和4.1分。进一步分析表明，RePO在Qwen3-1.7B上将计算成本增加了15%，同时将有效优化步骤的数量提高了48%，其中在线策略和离线策略样本数量均设置为8。该仓库可访问地址为https://github.com/SihengLi99/RePO。


> Reinforcement learning (RL) is vital for optimizing large language models (LLMs). Recent Group Relative Policy Optimization (GRPO) estimates advantages using multiple on-policy outputs per prompt, leading to high computational costs and low data efficiency. To address this, we introduce Replay-Enhanced Policy Optimization (RePO), which leverages diverse replay strategies to retrieve off-policy samples from a replay buffer, allowing policy optimization based on a broader and more diverse set of samples for each prompt. Experiments on five LLMs across seven mathematical reasoning benchmarks demonstrate that RePO achieves absolute average performance gains of $18.4$ and $4.1$ points for Qwen2.5-Math-1.5B and Qwen3-1.7B, respectively, compared to GRPO. Further analysis indicates that RePO increases computational cost by $15\%$ while raising the number of effective optimization steps by $48\%$ for Qwen3-1.7B, with both on-policy and off-policy sample numbers set to $8$. The repository can be accessed at https://github.com/SihengLi99/RePO.

[Arxiv](https://arxiv.org/abs/2506.09340)