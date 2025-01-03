# # 强化学习人类反馈中的奖励模型优化设计

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要讨论了从人类反馈中进行强化学习（RLHF）的理论框架，特别是如何形式化奖励训练模型，并提出了一个离线框架来解决有效数据集选择的问题。论文还推导了简单遗憾的界限，并提供了理论上的上下界。这些内容主要涉及理论分析和模型设计，属于对LLM（大型语言模型）的理论研究，因此分类为LLM理论。` `语言模型`

> Optimal Design for Reward Modeling in RLHF

# 摘要

> # 摘要
从人类反馈中进行强化学习（RLHF）已成为一种流行的方法，用于将语言模型（LMs）与人类偏好对齐。该方法通过收集大量人类对不同文本生成的成对偏好数据集，并利用这些数据推断奖励模型。尽管已有多种方法用于学习奖励模型并实现语言模型的对齐，但收集人类偏好的高成本过程却鲜有研究，且可从理论层面获得启发。本文旨在形式化RLHF中的奖励训练模型，将有效数据集的选择视为一个简单遗憾最小化任务，采用线性上下文对决赌博机方法。鉴于选项数量可能庞大，这种方法比最佳选项识别更为合理。我们进一步提出了一个离线框架来解决这一问题。在奖励模型在嵌入空间中线性且奖励参数有界的假设下，我们推导出简单遗憾的界限，并提供了一个与上界匹配的下界，直到常数和对数项。据我们所知，这是该领域首个提供离线方法及最坏情况保证的理论贡献。

> Reinforcement Learning from Human Feedback (RLHF) has become a popular approach to align language models (LMs) with human preferences. This method involves collecting a large dataset of human pairwise preferences across various text generations and using it to infer (implicitly or explicitly) a reward model. Numerous methods have been proposed to learn the reward model and align a LM with it. However, the costly process of collecting human preferences has received little attention and could benefit from theoretical insights. This paper addresses this issue and aims to formalize the reward training model in RLHF. We frame the selection of an effective dataset as a simple regret minimization task, using a linear contextual dueling bandit method. Given the potentially large number of arms, this approach is more coherent than the best-arm identification setting. We then propose an offline framework for solving this problem. Under appropriate assumptions - linearity of the reward model in the embedding space, and boundedness of the reward parameter - we derive bounds on the simple regret. Finally, we provide a lower bound that matches our upper bound up to constant and logarithmic terms. To our knowledge, this is the first theoretical contribution in this area to provide an offline approach as well as worst-case guarantees.

[Arxiv](https://arxiv.org/abs/2410.17055)