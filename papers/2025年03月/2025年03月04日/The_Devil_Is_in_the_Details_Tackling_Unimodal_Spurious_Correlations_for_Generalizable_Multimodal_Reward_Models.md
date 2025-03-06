# 魔鬼在细节中：解决单模态虚假相关性，构建通用的多模态奖励模型

发布时间：2025年03月04日

`LLM理论` `人工智能`

> The Devil Is in the Details: Tackling Unimodal Spurious Correlations for Generalizable Multimodal Reward Models

# 摘要

> 多模态奖励模型（MM-RMs）在使大型语言模型（LLMs）与人类偏好对齐方面发挥着关键作用，特别是在处理多模态数据时尤为重要。然而，现有MM-RMs在面对分布外数据时往往表现不佳，主要原因是它们过度依赖训练数据中的纯文本捷径和单模态虚假相关性，而忽视了真正的多模态奖励机制。针对这一问题，我们提出了一种基于捷径感知的MM-RM学习算法，通过动态调整训练样本权重，推动模型向更优的多模态理解方向发展，并减少对单模态虚假相关性的依赖。实验结果表明，该算法在泛化能力、任务性能和扩展性方面均有显著提升，为多模态奖励建模提供了更 robust 的解决方案。

> Multimodal Reward Models (MM-RMs) are crucial for aligning Large Language Models (LLMs) with human preferences, particularly as LLMs increasingly interact with multimodal data. However, we find that MM-RMs trained on existing datasets often struggle to generalize to out-of-distribution data due to their reliance on unimodal spurious correlations, primarily text-only shortcuts within the training distribution, which prevents them from leveraging true multimodal reward functions. To address this, we introduce a Shortcut-aware MM-RM learning algorithm that mitigates this issue by dynamically reweighting training samples, shifting the distribution toward better multimodal understanding, and reducing dependence on unimodal spurious correlations. Our experiments demonstrate significant improvements in generalization, downstream task performance, and scalability, establishing a more robust framework for multimodal reward modeling.

[Arxiv](https://arxiv.org/abs/2503.03122)