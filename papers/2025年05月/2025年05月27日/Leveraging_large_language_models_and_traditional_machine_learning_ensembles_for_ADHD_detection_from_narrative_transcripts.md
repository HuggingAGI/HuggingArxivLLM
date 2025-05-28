# 基于叙述性转录文本，利用大型语言模型与传统机器学习集成进行 ADHD 检测

发布时间：2025年05月27日

`LLM应用

LLM应用`

> Leveraging large language models and traditional machine learning ensembles for ADHD detection from narrative transcripts

# 摘要

> 尽管大型语言模型（LLMs）取得了迅速发展，但将其与传统监督机器学习（ML）技术相结合以应用于医疗数据的潜力仍未被充分挖掘。特别是在精神病学领域，叙述性数据往往具有复杂的语言和情境特征，可以通过结合不同特性的多种模型来获益。本研究提出了一种集成框架，用于通过叙述性转录本自动分类注意缺陷/多动障碍（ADHD）诊断（二分类）。我们的方法整合了三种互补模型：开源LLM LLaMA3，能够捕捉长距离语义结构；经过标记化临床叙述微调的预训练Transformer模型RoBERTa；以及基于TF-IDF词法特征训练的支持向量机（SVM）分类器。这些模型通过多数投票机制聚合，以增强预测稳健性。数据集包含441个实例，其中352个用于训练，89个用于验证。实证结果显示，集成模型优于单一模型，实现了【F1】分数为0.71（95%置信区间：[0.60-0.80]）。与表现最佳的单一模型（SVM）相比，集成模型在保持竞争力精度的同时提升了召回率。这表明集成模型在识别与ADHD相关的语言线索方面具有高度敏感性。这些发现展示了结合LLMs的语义丰富性和传统监督ML的可解释性及模式识别能力的混合架构的潜力，为构建稳健且可推广的精神科文本分类提供了新方向。

> Despite rapid advances in large language models (LLMs), their integration with traditional supervised machine learning (ML) techniques that have proven applicability to medical data remains underexplored. This is particularly true for psychiatric applications, where narrative data often exhibit nuanced linguistic and contextual complexity, and can benefit from the combination of multiple models with differing characteristics. In this study, we introduce an ensemble framework for automatically classifying Attention-Deficit/Hyperactivity Disorder (ADHD) diagnosis (binary) using narrative transcripts. Our approach integrates three complementary models: LLaMA3, an open-source LLM that captures long-range semantic structure; RoBERTa, a pre-trained transformer model fine-tuned on labeled clinical narratives; and a Support Vector Machine (SVM) classifier trained using TF-IDF-based lexical features. These models are aggregated through a majority voting mechanism to enhance predictive robustness. The dataset includes 441 instances, including 352 for training and 89 for validation. Empirical results show that the ensemble outperforms individual models, achieving an F$_1$ score of 0.71 (95\% CI: [0.60-0.80]). Compared to the best-performing individual model (SVM), the ensemble improved recall while maintaining competitive precision. This indicates the strong sensitivity of the ensemble in identifying ADHD-related linguistic cues. These findings demonstrate the promise of hybrid architectures that leverage the semantic richness of LLMs alongside the interpretability and pattern recognition capabilities of traditional supervised ML, offering a new direction for robust and generalizable psychiatric text classification.

[Arxiv](https://arxiv.org/abs/2505.21324)