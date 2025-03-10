# 软策略优化：针对序列模型的在线离策略强化学习方法

发布时间：2025年03月07日

`Agent` `代码竞赛`

> Soft Policy Optimization: Online Off-Policy RL for Sequence Models

# 摘要

> 当前，基于强化学习的语言模型微调几乎完全依赖于on-policy方法，如PPO。然而，这些方法存在诸多限制：它们无法从任意序列中学习，包括训练早期、先前运行、人类专家或其他策略生成的序列，以及通过解码和探索方法生成的序列。这不仅导致了样本效率低下和探索困难，还可能造成策略响应多样性的损失。此外，异步PPO实现需要频繁且昂贵的模型传输，并且通常依赖需要大量内存的价值模型。

为了解决这些问题，本文引入了Soft Policy Optimization (SPO)——一种简单、可扩展且基于原理的Soft RL方法。SPO专为序列模型策略设计，能够从任意在线和离线轨迹中学习，且无需依赖单独的价值模型。在代码竞赛实验中，SPO展现了显著优势：它在pass@10指标上超越PPO，运行速度更快、内存效率更高，能够有效利用离策略数据，具有更好的稳定性，并能学习到更多样化的（即soft）策略。

> RL-based post-training of language models is almost exclusively done using on-policy methods such as PPO. These methods cannot learn from arbitrary sequences such as those produced earlier in training, in earlier runs, by human experts or other policies, or by decoding and exploration methods. This results in severe sample inefficiency and exploration difficulties, as well as a potential loss of diversity in the policy responses. Moreover, asynchronous PPO implementations require frequent and costly model transfers, and typically use value models which require a large amount of memory. In this paper we introduce Soft Policy Optimization (SPO), a simple, scalable and principled Soft RL method for sequence model policies that can learn from arbitrary online and offline trajectories and does not require a separate value model. In experiments on code contests, we shows that SPO outperforms PPO on pass@10, is significantly faster and more memory efficient, is able to benefit from off-policy data, enjoys improved stability, and learns more diverse (i.e. soft) policies.

[Arxiv](https://arxiv.org/abs/2503.05453)