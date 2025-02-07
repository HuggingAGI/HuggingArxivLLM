# 基于CLIP的基础模型在X射线图像分类中的公平性分析

发布时间：2025年01月31日

`LLM应用

**理由**：这篇论文讨论了视觉-语言模型（如CLIP）在医疗诊断中的应用，特别是X射线图像分类。虽然CLIP最初并非为医学图像设计，但论文探讨了如何通过微调技术提升其性能，并分析了公平性问题。这属于将大型语言模型（LLM）或类似模型应用于特定领域（医疗诊断）的研究，因此归类为LLM应用。` `公平性分析`

> Fairness Analysis of CLIP-Based Foundation Models for X-Ray Image Classification

# 摘要

> # X射线成像在医疗诊断中扮演着关键角色，提供了对多种健康状况的非侵入性洞察。最近，视觉-语言模型，如对比语言-图像预训练（CLIP）模型，通过利用大规模图像-文本数据集，展现了提升诊断准确性的潜力。然而，由于CLIP最初并非为医学图像设计，因此已开发出多种专门针对医学图像训练的类似CLIP的模型。尽管这些模型的性能有所提升，但公平性问题——特别是关于人口统计属性的问题——仍然在很大程度上未得到解决。在本研究中，我们对应用于X射线图像分类的类似CLIP模型进行了全面的公平性分析。我们使用零-shot推理和各种微调技术（包括线性探测、多层感知器（MLP）、低秩适应（LoRA）和完全微调）评估了它们在不同患者人口统计和疾病类别中的表现和公平性。我们的结果表明，尽管微调提高了模型的准确性，但公平性问题仍然存在，这突显了在这些基础模型中进一步进行公平性干预的必要性。

> X-ray imaging is pivotal in medical diagnostics, offering non-invasive insights into a range of health conditions. Recently, vision-language models, such as the Contrastive Language-Image Pretraining (CLIP) model, have demonstrated potential in improving diagnostic accuracy by leveraging large-scale image-text datasets. However, since CLIP was not initially designed for medical images, several CLIP-like models trained specifically on medical images have been developed. Despite their enhanced performance, issues of fairness - particularly regarding demographic attributes - remain largely unaddressed. In this study, we perform a comprehensive fairness analysis of CLIP-like models applied to X-ray image classification. We assess their performance and fairness across diverse patient demographics and disease categories using zero-shot inference and various fine-tuning techniques, including Linear Probing, Multilayer Perceptron (MLP), Low-Rank Adaptation (LoRA), and full fine-tuning. Our results indicate that while fine-tuning improves model accuracy, fairness concerns persist, highlighting the need for further fairness interventions in these foundational models.

[Arxiv](https://arxiv.org/abs/2501.19086)