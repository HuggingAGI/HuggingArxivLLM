# # 非对比头颅CT基础模型：用于全面神经创伤分诊

发布时间：2025年02月28日

`LLM应用` `医学影像`

> A Non-contrast Head CT Foundation Model for Comprehensive Neuro-Trauma Triage

# 摘要

> 人工智能（AI）与医学影像技术的最新突破为急诊头颅CT解读带来革新，尤其在扫描需求激增和放射科医生短缺的背景下，显著缩短了评估时间并提升了诊断精度。本研究推出了一种3D基础模型，以高精度和高效率检测多种神经创伤。借助大型语言模型（LLMs）的自动标注功能，我们为危重病情生成了详尽的多标签注释。我们的创新方法包括预训练神经网络实现出血亚型分割和脑部解剖分区，通过多模态微调将其整合到预训练的综合神经创伤检测网络中。与专家标注的对比及与CT-CLIP的比较证实，该方法在主要神经创伤（如出血和中线移位）及少见危重状况（如脑水肿和动脉高密度）的分类上表现出色。引入神经特异性特征显著提升了诊断效能，16种神经创伤状况的平均AUC达0.861。本研究推动了医学影像基础模型的发展，为未来急诊放射学中的AI辅助神经创伤诊断树立了新标杆。

> Recent advancements in AI and medical imaging offer transformative potential in emergency head CT interpretation for reducing assessment times and improving accuracy in the face of an increasing request of such scans and a global shortage in radiologists. This study introduces a 3D foundation model for detecting diverse neuro-trauma findings with high accuracy and efficiency. Using large language models (LLMs) for automatic labeling, we generated comprehensive multi-label annotations for critical conditions. Our approach involved pretraining neural networks for hemorrhage subtype segmentation and brain anatomy parcellation, which were integrated into a pretrained comprehensive neuro-trauma detection network through multimodal fine-tuning. Performance evaluation against expert annotations and comparison with CT-CLIP demonstrated strong triage accuracy across major neuro-trauma findings, such as hemorrhage and midline shift, as well as less frequent critical conditions such as cerebral edema and arterial hyperdensity. The integration of neuro-specific features significantly enhanced diagnostic capabilities, achieving an average AUC of 0.861 for 16 neuro-trauma conditions. This work advances foundation models in medical imaging, serving as a benchmark for future AI-assisted neuro-trauma diagnostics in emergency radiology.

[Arxiv](https://arxiv.org/abs/2502.21106)