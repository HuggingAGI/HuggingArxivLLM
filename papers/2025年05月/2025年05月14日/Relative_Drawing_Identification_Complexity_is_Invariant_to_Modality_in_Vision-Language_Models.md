# 视觉-语言模型中的相对绘图识别复杂度与模态无关

发布时间：2025年05月14日

`LLM理论` `视觉语言模型` `机器学习`

> Relative Drawing Identification Complexity is Invariant to Modality in Vision-Language Models

# 摘要

> 大型语言模型迈向多模态，据称它们通过共同表示整合了不同模态。如果这一说法成立，那么一张汽车的图像应该与描述该图像笔触的文字在潜在空间映射到相似区域。为了在对这些模型进行黑盒访问时探索这一现象，我们提出了机器教学理论的应用，该理论研究教师需要选择的最小示例集，以便学习者能够掌握概念。在本文中，我们使用两种表示方法评估视觉语言模型学习Quick, Draw!数据集中小部分对象的复杂性：原始图像作为位图和TikZ格式的绘制轨迹坐标。结果显示，基于图像的表示通常需要较少的片段，且比基于坐标的表示实现更高的准确性。然而，令人惊讶的是，教学规模通常在两种模态中对概念进行相似排序，即使控制了（人类代理的）概念先验，这表明概念的简单性可能是超越模态表示的固有属性。

> Large language models have become multimodal, and many of them are said to integrate their modalities using common representations. If this were true, a drawing of a car as an image, for instance, should map to the similar area in the latent space as a textual description of the strokes that conform the drawing. To explore this in a black-box access regime to these models, we propose the use of machine teaching, a theory that studies the minimal set of examples a teacher needs to choose so that the learner captures the concept. In this paper we evaluate the complexity of teaching visual-language models a subset of objects in the Quick, Draw! dataset using two presentations: raw images as bitmaps and trace coordinates in TikZ format. The results indicate that image-based representations generally require fewer segments and achieve higher accuracy than coordinate-based representations. But, surprisingly, the teaching size usually ranks concepts similarly across both modalities, even when controlling for (a human proxy of) concept priors, suggesting that the simplicity of concepts may be an inherent property that transcends modality representations.

[Arxiv](https://arxiv.org/abs/2505.10583)