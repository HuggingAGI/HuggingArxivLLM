# 综合多模态原型是用于大量词汇对象检测的既简单又有效的分类器

发布时间：2024年12月23日

`其他` `目标检测` `计算机视觉`

> Comprehensive Multi-Modal Prototypes are Simple and Effective Classifiers for Vast-Vocabulary Object Detection

# 摘要

> 在目标检测领域，让模型能够识别众多的开放世界类别一直是长期以来的追求。借助视觉语言模型的泛化能力，当下的开放世界探测器即便在有限类别上训练，也能识别更广泛的词汇。然而，当训练时的类别词汇规模拓展至现实世界水平，与粗略类别名称相匹配的先前分类器会大幅降低这些探测器的识别性能。本文中，我们推出了 Prova，这是一种用于大量词汇对象检测的多模态原型分类器。Prova 提取全面的多模态原型作为对齐分类器的初始化，以应对大量词汇对象识别失败的问题。在 V3Det 上，这种简便方法仅通过额外的投影层，在有监督和开放词汇的设定下，极大地提升了一阶段、两阶段以及基于 DETR 的探测器的性能。特别是在 V3Det 的有监督设定中，Prova 分别让 Faster R-CNN、FCOS 和 DINO 的性能提升了 3.3、6.2 和 2.9 的 AP。对于开放词汇设定，Prova 达成了新的顶尖性能，基础 AP 为 32.8，新 AP 为 11.0，分别比之前的方法提高了 2.6 和 4.3。

> Enabling models to recognize vast open-world categories has been a longstanding pursuit in object detection. By leveraging the generalization capabilities of vision-language models, current open-world detectors can recognize a broader range of vocabularies, despite being trained on limited categories. However, when the scale of the category vocabularies during training expands to a real-world level, previous classifiers aligned with coarse class names significantly reduce the recognition performance of these detectors. In this paper, we introduce Prova, a multi-modal prototype classifier for vast-vocabulary object detection. Prova extracts comprehensive multi-modal prototypes as initialization of alignment classifiers to tackle the vast-vocabulary object recognition failure problem. On V3Det, this simple method greatly enhances the performance among one-stage, two-stage, and DETR-based detectors with only additional projection layers in both supervised and open-vocabulary settings. In particular, Prova improves Faster R-CNN, FCOS, and DINO by 3.3, 6.2, and 2.9 AP respectively in the supervised setting of V3Det. For the open-vocabulary setting, Prova achieves a new state-of-the-art performance with 32.8 base AP and 11.0 novel AP, which is of 2.6 and 4.3 gain over the previous methods.

[Arxiv](https://arxiv.org/abs/2412.17800)