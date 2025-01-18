# 克隆鲁棒的AI对齐

发布时间：2025年01月15日

`LLM理论

理由：这篇论文主要讨论了如何通过改进基于人类反馈的强化学习（RLHF）算法来使大型语言模型（LLMs）更好地与人类偏好对齐。论文提出了新的算法（加权MLE）来解决现有RLHF算法在备选方案分布不均情况下的不足，并证明了其理论特性。这些内容属于对LLM训练和优化方法的理论研究，因此应归类为LLM理论。` `人工智能`

> Clone-Robust AI Alignment

# 摘要

> 训练大型语言模型（LLMs）的一个核心挑战是如何使其与人类偏好精准对齐。基于人类反馈的强化学习（RLHF）通过人类标注者的成对比较来训练奖励函数，已成为一种主流对齐方法。然而，RLHF的输入数据集在问题和答案类型上往往不平衡。因此，我们希望RLHF算法即使在备选方案分布不均的情况下也能表现出色。借鉴社会选择理论的洞见，我们引入了对近似克隆的鲁棒性，这是RLHF算法的一个重要特性，要求添加近似重复的备选方案不会显著改变学习到的奖励函数。我们首先证明，基于正则化最大似然估计（MLE）的标准RLHF算法无法满足这一特性。接着，我们提出了加权MLE，这是一种新的RLHF算法，它通过根据备选方案与其他备选方案的相似性进行加权，改进了标准的正则化MLE。这一新算法不仅保证了对近似克隆的鲁棒性，还保留了理想的理论特性。

> A key challenge in training Large Language Models (LLMs) is properly aligning them with human preferences. Reinforcement Learning with Human Feedback (RLHF) uses pairwise comparisons from human annotators to train reward functions and has emerged as a popular alignment method. However, input datasets in RLHF are not necessarily balanced in the types of questions and answers that are included. Therefore, we want RLHF algorithms to perform well even when the set of alternatives is not uniformly distributed. Drawing on insights from social choice theory, we introduce robustness to approximate clones, a desirable property of RLHF algorithms which requires that adding near-duplicate alternatives does not significantly change the learned reward function. We first demonstrate that the standard RLHF algorithm based on regularized maximum likelihood estimation (MLE) fails to satisfy this property. We then propose the weighted MLE, a new RLHF algorithm that modifies the standard regularized MLE by weighting alternatives based on their similarity to other alternatives. This new algorithm guarantees robustness to approximate clones while preserving desirable theoretical properties.

[Arxiv](https://arxiv.org/abs/2501.09254)