# # 基于鲁棒无标签学习的自迭代标签优化

发布时间：2025年02月18日

`LLM应用` `生物技术`

> Self Iterative Label Refinement via Robust Unlabeled Learning

# 摘要

> 大型语言模型（LLMs）在各类任务中表现优异，但其性能往往依赖于获取成本高昂的高质量反馈。自优化方法试图在少量人工干预下利用 LLMs 的内部评估机制，然而这些方法常因内在偏见和过度自信而导致性能下降，尤其在模型知识储备不足的领域。为提升自优化能力并扩大其应用范围，我们提出了一种基于 Unlabeled-Unlabeled 学习框架的迭代优化流水线，用于提升 LLM 生成的伪标签质量。通过利用两个具有不同正类比率的无标签数据集，我们的方法能够迭代地去除噪声并优化初始伪标签，从而在少量人工干预下有效缓解内部偏见带来的负面影响。在低资源语言语料库、专利分类和蛋白质结构分类等多种数据集上的评估表明，我们的方法在分类性能上不仅优于初始 LLM 的表现，同时也超越了前沿模型（如 GPT-4o 和 DeepSeek-R1）的自优化方法。

> Recent advances in large language models (LLMs) have yielded impressive performance on various tasks, yet they often depend on high-quality feedback that can be costly. Self-refinement methods attempt to leverage LLMs' internal evaluation mechanisms with minimal human supervision; however, these approaches frequently suffer from inherent biases and overconfidence, especially in domains where the models lack sufficient internal knowledge, resulting in performance degradation. As an initial step toward enhancing self-refinement for broader applications, we introduce an iterative refinement pipeline that employs the Unlabeled-Unlabeled learning framework to improve LLM-generated pseudo-labels for classification tasks. By exploiting two unlabeled datasets with differing positive class ratios, our approach iteratively denoises and refines the initial pseudo-labels, thereby mitigating the adverse effects of internal biases with minimal human supervision. Evaluations on diverse datasets, including low-resource language corpora, patent classifications, and protein structure categorizations, demonstrate that our method consistently outperforms both initial LLM's classification performance and the self-refinement approaches by cutting-edge models (e.g., GPT-4o and DeepSeek-R1).

[Arxiv](https://arxiv.org/abs/2502.12565)