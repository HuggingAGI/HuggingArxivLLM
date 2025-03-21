# 软提示调优实现大型语言模型的文化适配

发布时间：2025年03月20日

`LLM理论` `社会科学` `文化研究`

> Cultural Alignment in Large Language Models Using Soft Prompt Tuning

# 摘要

> 传统上，大型语言模型（LLM）的对齐依赖于监督微调或基于强化学习的框架，这些方法通常需要标注或偏好数据，并通过更新模型权重来实现对齐。在社会科学领域，如跨文化研究中，因子分析被广泛用于揭示潜在变量，以解释调查数据中的观察模式。然而，由于测量方法的非可微性质，传统的对齐方法难以与文化维度结合。为解决这一问题，我们提出了一种参数高效的策略，结合软提示微调（保持模型参数不变，仅修改输入提示嵌入）与差分进化（DE）——一种适用于无法获得可微目标的黑箱优化方法。该策略无需偏好数据或参数更新，即可实现一致的对齐，显著提升了效率并减少了过拟合风险。我们的方法在LLama-3-8B-Instruct模型的多个地区文化维度上表现优异，超越了Naive LLM和In-context Learning（ICL）基线，成功将计算模型与人类文化细微差别相结合。

> Large Language Model (LLM) alignment conventionally relies on supervised fine-tuning or reinforcement learning based alignment frameworks. These methods typically require labeled or preference datasets and involve updating model weights to align the LLM with the training objective or reward model. Meanwhile, in social sciences such as cross-cultural studies, factor analysis is widely used to uncover underlying dimensions or latent variables that explain observed patterns in survey data. The non-differentiable nature of these measurements deriving from survey data renders the former alignment methods infeasible for alignment with cultural dimensions. To overcome this, we propose a parameter efficient strategy that combines soft prompt tuning, which freezes the model parameters while modifying the input prompt embeddings, with Differential Evolution (DE), a black-box optimization method for cases where a differentiable objective is unattainable. This strategy ensures alignment consistency without the need for preference data or model parameter updates, significantly enhancing efficiency and mitigating overfitting. Our method demonstrates significant improvements in LLama-3-8B-Instruct's cultural dimensions across multiple regions, outperforming both the Naive LLM and the In-context Learning (ICL) baseline, and effectively bridges computational models with human cultural nuances.

[Arxiv](https://arxiv.org/abs/2503.16094)