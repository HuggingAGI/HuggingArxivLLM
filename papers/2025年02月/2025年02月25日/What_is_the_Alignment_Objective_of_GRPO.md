# GRPO 的对齐目标是什么？

发布时间：2025年02月25日

`LLM理论

理由：这篇论文深入探讨了组策略优化（GRPO）算法的理论机制，分析了其偏好聚合的方式，与其他方法的比较，以及参数对聚合效果的影响。这些内容属于强化学习算法的理论层面，因此归类为LLM理论。` `AI模型`

> What is the Alignment Objective of GRPO?

# 摘要

> 在这份报告中，我们深入研究了组策略优化（GRPO）算法在偏好聚合方面的表现。GRPO作为一种强化学习方法，被用于训练如DeepSeek-R1-Zero和DeepSeekMath等先进AI模型。该算法通过奖励偏好模型训练策略，具体包括：针对特定上下文采样输出，观察奖励，并对奖励值进行移位和缩放归一化处理。此外，还引入惩罚函数以抑制偏离参考策略的行为。

    我们构建了一个分析框架，用于表征GRPO算法的稳定策略。研究发现，GRPO的偏好聚合方式与其它方法（如RLHF）采用的标准对数池化存在本质区别。这种差异源于奖励偏好模型的定义和惩罚函数的设计，我们发现其本质上对应于聚合策略与参考策略之间的逆向Kullback-Leibler（KL）散度。

    值得一提的是，当群体规模为两人时，奖励偏好模型对应于成对比较偏好，与基于成对比较反馈的其他对齐方法相似。我们对二元问题、两人群体以及大规模群体情况下的聚合偏好进行了明确表征。这为我们理解聚合偏好与正则化常数、问题答案置信度边界等参数之间的依赖关系提供了重要洞见。

    最后，我们探讨了通过修改GRPO算法以直接使用KL散度作为惩罚项，或在不进行尺度归一化的情况下使用奖励所获得的偏好聚合效果。

> In this note, we examine the aggregation of preferences achieved by the Group Policy Optimisation (GRPO) algorithm, a reinforcement learning method used to train advanced artificial intelligence models such as DeepSeek-R1-Zero and DeepSeekMath. The GRPO algorithm trains a policy using a reward preference model, which is computed by sampling a set of outputs for a given context, observing the corresponding rewards, and applying shift-and-scale normalisation to these reward values. Additionally, it incorporates a penalty function to discourage deviations from a reference policy.
  We present a framework that enables us to characterise the stationary policies of the GRPO algorithm. This analysis reveals that the aggregation of preferences differs fundamentally from standard logarithmic pooling, which is implemented by other approaches such as RLHF. The precise form of preference aggregation arises from the way the reward preference model is defined and from the penalty function, which we show to essentially correspond to the reverse Kullback-Leibler (KL) divergence between the aggregation policy and the reference policy.
  Interestingly, we demonstrate that for groups of size two, the reward preference model corresponds to pairwise comparison preferences, similar to those in other alignment methods based on pairwise comparison feedback. We provide explicit characterisations of the aggregate preference for binary questions, for groups of size two, and in the limit of large group size. This provides insights into the dependence of the aggregate preference on parameters such as the regularisation constant and the confidence margin of question answers.
  Finally, we discuss the aggregation of preferences obtained by modifying the GRPO algorithm to use direct KL divergence as the penalty or to use rewards without scale normalisation.

[Arxiv](https://arxiv.org/abs/2502.18548)