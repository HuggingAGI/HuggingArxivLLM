# ViLa-MIL：双尺度视觉-语言多示例学习在全幻灯片图像分类中的应用

发布时间：2025年02月12日

`LLM应用` `图像处理`

> ViLa-MIL: Dual-scale Vision-Language Multiple Instance Learning for Whole Slide Image Classification

# 摘要

> 多示例学习（MIL）框架在数字病理学中已成为处理千兆像素级全玻片图像（WSI）及其层次化图像上下文的主流方法。然而，这些方法严重依赖大量袋级标签，并仅从原始切片学习，因此容易受到数据分布变化的影响。近期，基于视觉语言模型（VLM）的方法通过在大规模病理图像-文本对上进行预训练引入了语言先验。然而，之前的文本提示缺乏对病理先验知识的考虑，因此未能显著提升模型性能。此外，收集这些图像-文本对并进行预训练的过程非常耗时且资源密集。

为了解决上述问题，我们提出了一种双尺度视觉语言多示例学习（ViLa-MIL）框架，用于全玻片图像分类。具体而言，我们提出了一种基于冻结大型语言模型（LLM）的双尺度视觉描述性文本提示，以有效提升VLM的性能。为了高效地将VLM迁移到处理WSI上，针对图像分支，我们提出了一种基于原型引导的补丁解码器，通过将相似补丁分组到同一原型中逐步聚合补丁特征；针对文本分支，我们引入了一种基于上下文引导的文本解码器，通过融合多粒度图像上下文来增强文本特征。在三个多癌种和多中心分型数据集上的广泛研究表明，ViLa-MIL具有显著优势。


> Multiple instance learning (MIL)-based framework has become the mainstream for processing the whole slide image (WSI) with giga-pixel size and hierarchical image context in digital pathology. However, these methods heavily depend on a substantial number of bag-level labels and solely learn from the original slides, which are easily affected by variations in data distribution. Recently, vision language model (VLM)-based methods introduced the language prior by pre-training on large-scale pathological image-text pairs. However, the previous text prompt lacks the consideration of pathological prior knowledge, therefore does not substantially boost the model's performance. Moreover, the collection of such pairs and the pre-training process are very time-consuming and source-intensive.To solve the above problems, we propose a dual-scale vision-language multiple instance learning (ViLa-MIL) framework for whole slide image classification. Specifically, we propose a dual-scale visual descriptive text prompt based on the frozen large language model (LLM) to boost the performance of VLM effectively. To transfer the VLM to process WSI efficiently, for the image branch, we propose a prototype-guided patch decoder to aggregate the patch features progressively by grouping similar patches into the same prototype; for the text branch, we introduce a context-guided text decoder to enhance the text features by incorporating the multi-granular image contexts. Extensive studies on three multi-cancer and multi-center subtyping datasets demonstrate the superiority of ViLa-MIL.

[Arxiv](https://arxiv.org/abs/2502.08391)