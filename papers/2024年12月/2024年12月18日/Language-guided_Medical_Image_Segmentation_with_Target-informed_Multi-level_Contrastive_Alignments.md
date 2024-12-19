# 语言引导下基于目标告知的多级对比对齐的医学图像分割

发布时间：2024年12月18日

`LLM应用` `医学图像分析`

> Language-guided Medical Image Segmentation with Target-informed Multi-level Contrastive Alignments

# 摘要

> 医学图像分割在现代医学图像分析中极为关键，有助于诊断各类疾病。近来，语言引导的分割方法在将文本报告作为指引的图像分割自动化领域成果斐然。这些由临床医生给出的包含图像印象和见解的文本报告提供了辅助引导。然而，这些方法忽视了两种不同模态间固有的模式差异，致使在缺乏恰当的跨模态特征对齐时，图像与文本的特征融合效果欠佳。对比对齐在表示学习中常用于关联图像与文本的语义，但其尚未用于弥补依赖于细微的低级图像细节来表征疾病的语言引导分割中的模式差距。现有的对比对齐方法通常对齐高级全局图像语义，却未涉及低级、局部的目标信息，因而无法为语言引导的分割探索细粒度的文本指导。在本研究中，我们提出了一种具备目标告知的多级对比对齐（TMCA）的语言引导分割网络。TMCA 能够实现目标告知的跨模态对齐和细粒度文本指导，以弥合语言引导分割中的模式差距。具体而言，我们引入了：1）一个目标敏感的语义距离模块，可进行细粒度的图像-文本对齐建模；2）一个多级对齐策略，将文本指导引向低级图像特征。此外，还提出了一个语言引导的目标增强模块，利用对齐的文本将注意力重新聚焦于关键的局部图像特征。在 4 个图像-文本数据集上开展的大量实验，涵盖 3 种医学成像模态，表明我们的 TMCA 性能卓越。

> Medical image segmentation is crucial in modern medical image analysis, which can aid into diagnosis of various disease conditions. Recently, language-guided segmentation methods have shown promising results in automating image segmentation where text reports are incorporated as guidance. These text reports, containing image impressions and insights given by clinicians, provides auxiliary guidance. However, these methods neglect the inherent pattern gaps between the two distinct modalities, which leads to sub-optimal image-text feature fusion without proper cross-modality feature alignments. Contrastive alignments are widely used to associate image-text semantics in representation learning; however, it has not been exploited to bridge the pattern gaps in language-guided segmentation that relies on subtle low level image details to represent diseases. Existing contrastive alignment methods typically algin high-level global image semantics without involving low-level, localized target information, and therefore fails to explore fine-grained text guidance for language-guided segmentation. In this study, we propose a language-guided segmentation network with Target-informed Multi-level Contrastive Alignments (TMCA). TMCA enables target-informed cross-modality alignments and fine-grained text guidance to bridge the pattern gaps in language-guided segmentation. Specifically, we introduce: 1) a target-sensitive semantic distance module that enables granular image-text alignment modelling, and 2) a multi-level alignment strategy that directs text guidance on low-level image features. In addition, a language-guided target enhancement module is proposed to leverage the aligned text to redirect attention to focus on critical localized image features. Extensive experiments on 4 image-text datasets, involving 3 medical imaging modalities, demonstrated that our TMCA achieved superior performances.

[Arxiv](https://arxiv.org/abs/2412.13533)