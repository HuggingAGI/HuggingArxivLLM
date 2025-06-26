# 单义性的度量与引导

发布时间：2025年06月24日

`LLM理论` `人工智能`

> Measuring and Guiding Monosemanticity

# 摘要

> 人们对利用机制可解释性和可控性来理解大型语言模型（LLMs）的内部动态越来越感兴趣。然而，现有方法在定位和操作特征表示方面仍面临根本性挑战。稀疏自动编码器（SAEs）作为一种有前景的特征提取方法出现，但受限于特征隔离和单义性问题。为此，我们引入了特征单义性评分（FMS），用于量化潜在表示的单义性。在此基础上，我们提出了指导稀疏自动编码器（G-SAE），在训练中将潜在表示与标签化概念结合。我们发现，对潜在空间中目标概念的可靠定位和分离可提升可解释性、行为检测和控制能力。具体而言，G-SAE在毒性检测、写作风格识别和隐私属性识别中的评估表明，其不仅增强了单义性，还实现了更有效且精细的引导，同时减少了质量下降。我们的发现为衡量和推进LLMs的机制可解释性和控制提供了实用的指导方针。

> There is growing interest in leveraging mechanistic interpretability and controllability to better understand and influence the internal dynamics of large language models (LLMs). However, current methods face fundamental challenges in reliably localizing and manipulating feature representations. Sparse Autoencoders (SAEs) have recently emerged as a promising direction for feature extraction at scale, yet they, too, are limited by incomplete feature isolation and unreliable monosemanticity. To systematically quantify these limitations, we introduce Feature Monosemanticity Score (FMS), a novel metric to quantify feature monosemanticity in latent representation. Building on these insights, we propose Guided Sparse Autoencoders (G-SAE), a method that conditions latent representations on labeled concepts during training. We demonstrate that reliable localization and disentanglement of target concepts within the latent space improve interpretability, detection of behavior, and control. Specifically, our evaluations on toxicity detection, writing style identification, and privacy attribute recognition show that G-SAE not only enhances monosemanticity but also enables more effective and fine-grained steering with less quality degradation. Our findings provide actionable guidelines for measuring and advancing mechanistic interpretability and control of LLMs.

[Arxiv](https://arxiv.org/abs/2506.19382)