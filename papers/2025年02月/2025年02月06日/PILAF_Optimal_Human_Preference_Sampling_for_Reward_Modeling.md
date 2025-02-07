# PILAF：奖励建模中的最优人类偏好采样

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要讨论了如何通过改进强化学习方法来使大型语言模型（LLM）与人类价值观对齐。具体来说，它提出了一种新的策略（PILAF）来优化偏好学习，以最大化潜在的人类价值观。这涉及到对LLM的理论基础和优化方法的深入研究，因此应归类为“LLM理论”。` `人工智能`

> PILAF: Optimal Human Preference Sampling for Reward Modeling

# 摘要

> 随着大型语言模型在现实应用中的广泛应用，如何使其与人类价值观保持一致变得至关重要。基于人类反馈的强化学习（RLHF）应运而生，它通过将偏好数据转化为奖励模型来解决人类价值观难以直接获取的问题。然而，RLHF通常依赖近似的奖励模型，这些模型可能无法始终引导策略最大化潜在的人类价值观。为此，我们提出了一种新颖的偏好标签响应采样策略——PILAF（Policy-Interpolated Learning for Aligned Feedback），它明确地将偏好学习与最大化潜在的人类价值观对齐。PILAF在理论和实践上均表现出色，从优化和统计的角度证明了其最优性。该方法易于实现，并在迭代和在线RLHF设置中展现了强大的性能，尤其是在反馈管理至关重要的场景中。

> As large language models increasingly drive real-world applications, aligning them with human values becomes paramount. Reinforcement Learning from Human Feedback (RLHF) has emerged as a key technique, translating preference data into reward models when oracle human values remain inaccessible. In practice, RLHF mostly relies on approximate reward models, which may not consistently guide the policy toward maximizing the underlying human values. We propose Policy-Interpolated Learning for Aligned Feedback (PILAF), a novel response sampling strategy for preference labeling that explicitly aligns preference learning with maximizing the underlying oracle reward. PILAF is theoretically grounded, demonstrating optimality from both an optimization and a statistical perspective. The method is straightforward to implement and demonstrates strong performance in iterative and online RLHF settings where feedback curation is critical.

[Arxiv](https://arxiv.org/abs/2502.04270)