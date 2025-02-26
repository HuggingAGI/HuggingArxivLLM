# # 对比式视觉数据增强

发布时间：2025年02月24日

`LLM应用` `计算机视觉`

> Contrastive Visual Data Augmentation

# 摘要

> 大型多模态模型（LMMs）难以准确识别新概念，主要因为它们依赖预训练知识，且难以捕捉细微的视觉细节。训练中领域特定的知识差距也导致它们容易混淆视觉上相似、常被错误表示或资源匮乏的概念。为帮助 LMMs 更好地将视觉特征与语言对齐，提升对新概念或罕见概念的识别与推理能力，我们提出了一种对比视觉数据增强（CoDA）策略。CoDA 通过提取目标概念与易被误识别为的已知概念之间的关键对比文本和视觉特征，利用多模态生成模型生成针对性的合成数据。自动过滤机制确保了提取特征和增强图像的质量，这一点也得到了人工标注者的验证。我们在低资源概念和多样化场景识别数据集（包括 INaturalist 和 SUN）上展示了 CoDA 的高效性。此外，我们还收集了 NovelSpecies 数据集，这是一个由新发现的动物物种组成的基准数据集，确保 LMMs 从未见过这些物种。在 LLaVA-1.6 的 1-shot 更新实验中，CoDA 在 NovelSpecies、SUN 和 iNat 三个数据集上的准确率绝对增益分别为 12.3%、5.1% 和 6.0%，显著优于现有的最优视觉数据增强策略。

> Large multimodal models (LMMs) often struggle to recognize novel concepts, as they rely on pre-trained knowledge and have limited ability to capture subtle visual details. Domain-specific knowledge gaps in training also make them prone to confusing visually similar, commonly misrepresented, or low-resource concepts. To help LMMs better align nuanced visual features with language, improving their ability to recognize and reason about novel or rare concepts, we propose a Contrastive visual Data Augmentation (CoDA) strategy. CoDA extracts key contrastive textual and visual features of target concepts against the known concepts they are misrecognized as, and then uses multimodal generative models to produce targeted synthetic data. Automatic filtering of extracted features and augmented images is implemented to guarantee their quality, as verified by human annotators. We show the effectiveness and efficiency of CoDA on low-resource concept and diverse scene recognition datasets including INaturalist and SUN. We additionally collect NovelSpecies, a benchmark dataset consisting of newly discovered animal species that are guaranteed to be unseen by LMMs. LLaVA-1.6 1-shot updating results on these three datasets show CoDA significantly improves SOTA visual data augmentation strategies by 12.3% (NovelSpecies), 5.1% (SUN), and 6.0% (iNat) absolute gains in accuracy.

[Arxiv](https://arxiv.org/abs/2502.17709)