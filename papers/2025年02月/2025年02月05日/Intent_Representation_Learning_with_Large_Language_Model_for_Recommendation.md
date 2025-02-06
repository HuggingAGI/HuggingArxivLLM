# 基于大型语言模型的意图表示学习在推荐系统中的应用

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论的是如何利用大语言模型（LLMs）来构建多模态意图表示，并应用于推荐系统中。虽然涉及到意图表示学习和多模态对齐等技术，但其核心是利用LLMs来增强推荐系统的性能。因此，这篇论文应归类为LLM应用。` `推荐系统` `多模态学习`

> Intent Representation Learning with Large Language Model for Recommendation

# 摘要

> # 摘要
基于意图的推荐系统在挖掘潜在细粒度偏好方面备受瞩目。意图作为交互的底层因素，对提升推荐的可解释性至关重要。现有方法大多将意图定义为可学习参数，随交互更新。然而，这些框架常忽视文本信息（如用户评论、物品描述），而这对缓解交互意图的稀疏性至关重要。探索多模态意图，尤其是表示空间中的固有差异，带来了两大挑战：i）如何对齐多模态意图并有效降噪；ii）如何提取并匹配跨模态的潜在关键意图。为此，我们提出了一个模型无关的框架——基于大语言模型的意图表示学习（IRLLRec），利用大语言模型（LLMs）构建多模态意图并增强推荐。IRLLRec采用双塔架构学习多模态意图表示，并通过成对对齐和翻译对齐消除模态差异，增强对噪声输入的鲁棒性。最后，我们使用动量蒸馏对融合的意图表示进行师生学习，以更好地匹配文本与交互意图。在三个数据集上的实验表明，IRLLRec优于基线模型。代码已开源：https://github.com/wangyu0627/IRLLRec。

> Intent-based recommender systems have garnered significant attention for uncovering latent fine-grained preferences. Intents, as underlying factors of interactions, are crucial for improving recommendation interpretability. Most methods define intents as learnable parameters updated alongside interactions. However, existing frameworks often overlook textual information (e.g., user reviews, item descriptions), which is crucial for alleviating the sparsity of interaction intents. Exploring these multimodal intents, especially the inherent differences in representation spaces, poses two key challenges: i) How to align multimodal intents and effectively mitigate noise issues; ii) How to extract and match latent key intents across modalities. To tackle these challenges, we propose a model-agnostic framework, Intent Representation Learning with Large Language Model (IRLLRec), which leverages large language models (LLMs) to construct multimodal intents and enhance recommendations. Specifically, IRLLRec employs a dual-tower architecture to learn multimodal intent representations. Next, we propose pairwise and translation alignment to eliminate inter-modal differences and enhance robustness against noisy input features. Finally, to better match textual and interaction-based intents, we employ momentum distillation to perform teacher-student learning on fused intent representations. Empirical evaluations on three datasets show that our IRLLRec framework outperforms baselines. The implementation is available at https://github.com/wangyu0627/IRLLRec.

[Arxiv](https://arxiv.org/abs/2502.03307)