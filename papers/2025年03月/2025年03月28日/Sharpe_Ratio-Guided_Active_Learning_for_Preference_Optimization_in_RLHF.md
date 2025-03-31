# 基于夏普比率的主动学习方法在RLHF中的偏好优化

发布时间：2025年03月28日

`LLM理论` `人工智能`

> Sharpe Ratio-Guided Active Learning for Preference Optimization in RLHF

# 摘要

> 从人类反馈中强化学习（RLHF）已成为大型语言模型（LLMs）训练与对齐的核心技术。近期，直接偏好优化（DPO）等方法简化了偏好学习过程。然而，收集偏好数据仍面临成本高昂、耗时耗力的挑战，尤其需要依赖专家标注。为降低这一成本，我们提出了一种主动学习方法，通过基于夏普比率的风险评估策略，高效选择提示与偏好对。为解决标注前偏好未知的问题，我们的方法评估了所有潜在偏好标注的梯度，以判断其对模型更新的影响。这些基于梯度的评估使我们能够全面评估数据点的风险，无论标注结果如何。通过结合DPO损失的推导，我们得出了一个闭合形式的表达式，用于逐元组计算夏普比率，确保方法既高效又易于实现。此外，我们还提出了两种方法变体，分别基于不同的先验信息假设。实验结果显示，与基线方法相比，我们的方法在有限的人类偏好数据下，针对多个语言模型和真实世界数据集，胜率提升了5%。


> Reinforcement learning from human feedback (RLHF) has become a cornerstone of the training and alignment pipeline for large language models (LLMs). Recent advances, such as direct preference optimization (DPO), have simplified the preference learning step. However, collecting preference data remains a challenging and costly process, often requiring expert annotation. This cost can be mitigated by carefully selecting the data points presented for annotation. In this work, we propose an active learning approach to efficiently select prompt and preference pairs using a risk assessment strategy based on the Sharpe Ratio. To address the challenge of unknown preferences prior to annotation, our method evaluates the gradients of all potential preference annotations to assess their impact on model updates. These gradient-based evaluations enable risk assessment of data points regardless of the annotation outcome. By leveraging the DPO loss derivations, we derive a closed-form expression for computing these Sharpe ratios on a per-tuple basis, ensuring our approach remains both tractable and computationally efficient. We also introduce two variants of our method, each making different assumptions about prior information. Experimental results demonstrate that our method outperforms the baseline by up to 5% in win rates against the chosen completion with limited human preference data across several language models and real-world datasets.

[Arxiv](https://arxiv.org/abs/2503.22137)