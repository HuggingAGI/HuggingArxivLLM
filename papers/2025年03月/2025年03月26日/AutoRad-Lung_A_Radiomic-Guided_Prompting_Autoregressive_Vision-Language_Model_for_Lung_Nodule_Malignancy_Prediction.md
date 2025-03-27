# AutoRad-Lung: 基于放射组学引导的提示自回归视觉语言模型，用于肺结节恶性预测。

发布时间：2025年03月26日

`LLM应用` `多模态模型`

> AutoRad-Lung: A Radiomic-Guided Prompting Autoregressive Vision-Language Model for Lung Nodule Malignancy Prediction

# 摘要

> 肺癌仍是全球癌症相关死亡的主要原因之一。早期诊断的难点在于区分那些具有相似视觉特征和相近标注分数的不确定病例。在临床实践中，放射科医生依赖于从CT图像中提取的定量放射组学特征，而近期研究主要集中在深度学习解决方案上。最近，视觉-语言模型（VLM），特别是基于对比语言-图像预训练（CLIP）的模型，因其能够将文本知识整合到肺癌诊断中而受到关注。尽管CLIP-Lung模型展现了有前景的结果，但我们发现了以下潜在限制：（a）依赖放射科医生标注的属性，这些属性本质上主观且容易出错；（b）仅在训练过程中使用文本信息，限制了在推理阶段的直接应用；（c）使用基于卷积的视觉编码器，其权重随机初始化，忽视了先验知识。为了解决这些问题，我们引入了AutoRad-Lung，它结合了自回归预训练的VLM与基于手工设计放射组学生成的提示。AutoRad-Lung采用了大规模自回归图像模型（AIMv2）的视觉编码器，该编码器通过多模态自回归目标进行预训练。鉴于肺肿瘤通常较小、形状不规则且与健康组织视觉相似，AutoRad-Lung在捕捉像素级差异方面相较于其基于CLIP的同类模型具有显著优势。此外，我们引入了条件上下文优化，根据输入的放射组学动态生成特定上下文的提示，从而提升了跨模态对齐效果。

> Lung cancer remains one of the leading causes of cancer-related mortality worldwide. A crucial challenge for early diagnosis is differentiating uncertain cases with similar visual characteristics and closely annotation scores. In clinical practice, radiologists rely on quantitative, hand-crafted Radiomic features extracted from Computed Tomography (CT) images, while recent research has primarily focused on deep learning solutions. More recently, Vision-Language Models (VLMs), particularly Contrastive Language-Image Pre-Training (CLIP)-based models, have gained attention for their ability to integrate textual knowledge into lung cancer diagnosis. While CLIP-Lung models have shown promising results, we identified the following potential limitations: (a) dependence on radiologists' annotated attributes, which are inherently subjective and error-prone, (b) use of textual information only during training, limiting direct applicability at inference, and (c) Convolutional-based vision encoder with randomly initialized weights, which disregards prior knowledge. To address these limitations, we introduce AutoRad-Lung, which couples an autoregressively pre-trained VLM, with prompts generated from hand-crafted Radiomics. AutoRad-Lung uses the vision encoder of the Large-Scale Autoregressive Image Model (AIMv2), pre-trained using a multi-modal autoregressive objective. Given that lung tumors are typically small, irregularly shaped, and visually similar to healthy tissue, AutoRad-Lung offers significant advantages over its CLIP-based counterparts by capturing pixel-level differences. Additionally, we introduce conditional context optimization, which dynamically generates context-specific prompts based on input Radiomics, improving cross-modal alignment.

[Arxiv](https://arxiv.org/abs/2503.20662)