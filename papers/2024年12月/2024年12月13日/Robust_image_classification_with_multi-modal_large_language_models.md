# 利用多模态大型语言模型实现鲁棒的图像分类

发布时间：2024年12月13日

`LLM应用` `图像识别` `网络安全`

> Robust image classification with multi-modal large language models

# 摘要

> 深度神经网络易受对抗样本的侵扰，也就是那些精心设计的输入样本，能让模型满怀自信地给出错误预测。为降低此类漏洞的影响，已有人提出对抗训练和基于检测的防御手段，提前强化模型。然而，这些方法大多聚焦于单一数据模态，忽略了输入的视觉模式与文本描述的关系。在本文中，我们提出了一种全新的防御手段——Multi-Shield，旨在结合多模态信息对这些防御手段进行补充，进一步提升其稳健性。Multi-Shield 借助多模态大型语言模型检测对抗样本，当输入的文本和视觉表示不匹配时，避免做出不确定的分类。对 CIFAR-10 和 ImageNet 数据集，使用鲁棒和非鲁棒图像分类模型进行的大量评估显示，Multi-Shield 能够轻松集成来检测和拒绝对抗样本，表现优于原始防御手段。

> Deep Neural Networks are vulnerable to adversarial examples, i.e., carefully crafted input samples that can cause models to make incorrect predictions with high confidence. To mitigate these vulnerabilities, adversarial training and detection-based defenses have been proposed to strengthen models in advance. However, most of these approaches focus on a single data modality, overlooking the relationships between visual patterns and textual descriptions of the input. In this paper, we propose a novel defense, Multi-Shield, designed to combine and complement these defenses with multi-modal information to further enhance their robustness. Multi-Shield leverages multi-modal large language models to detect adversarial examples and abstain from uncertain classifications when there is no alignment between textual and visual representations of the input. Extensive evaluations on CIFAR-10 and ImageNet datasets, using robust and non-robust image classification models, demonstrate that Multi-Shield can be easily integrated to detect and reject adversarial examples, outperforming the original defenses.

[Arxiv](https://arxiv.org/abs/2412.10353)