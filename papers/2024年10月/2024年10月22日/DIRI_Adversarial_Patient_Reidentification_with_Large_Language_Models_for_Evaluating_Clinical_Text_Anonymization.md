# DIRI：利用大型语言模型进行对抗性患者重识别，评估临床文本匿名化效果

发布时间：2024年10月22日

`LLM应用

**理由**：该论文摘要描述了利用大型语言模型（LLM）进行去标识化和重新识别患者信息的方法，并评估了其性能。这属于LLM在具体应用场景（医疗数据去标识化）中的使用，因此分类为LLM应用。` `数据隐私`

> DIRI: Adversarial Patient Reidentification with Large Language Models for Evaluating Clinical Text Anonymization

# 摘要

> 共享受保护的健康信息（PHI）对生物医学研究至关重要。在数据分发前，从业者通常会对文本中的PHI进行去标识化处理。然而，现有的去标识化方法在高度饱和的数据集上表现优异（工具准确率接近完美），但这可能无法完全反映真实世界临床文本的复杂性和多样性，且注释过程资源密集，成为实际应用的障碍。为解决这一问题，我们开发了一种对抗性方法，利用大型语言模型（LLM）重新识别与删减的临床笔记对应的患者，并通过一种新颖的去标识化/重新识别（DIRI）方法评估性能。我们在Weill Cornell Medicine的医疗数据上展示了该方法，数据使用了三种去标识化工具：基于规则的Philter和两种深度学习模型BiLSTM-CRF与ClinicalBERT。尽管ClinicalBERT表现最佳，屏蔽了所有识别的PII，但我们的工具仍成功重新识别了9%的临床笔记。这项研究揭示了当前去标识化技术的显著不足，同时为迭代开发和改进提供了工具。

> Sharing protected health information (PHI) is critical for furthering biomedical research. Before data can be distributed, practitioners often perform deidentification to remove any PHI contained in the text. Contemporary deidentification methods are evaluated on highly saturated datasets (tools achieve near-perfect accuracy) which may not reflect the full variability or complexity of real-world clinical text and annotating them is resource intensive, which is a barrier to real-world applications. To address this gap, we developed an adversarial approach using a large language model (LLM) to re-identify the patient corresponding to a redacted clinical note and evaluated the performance with a novel De-Identification/Re-Identification (DIRI) method. Our method uses a large language model to reidentify the patient corresponding to a redacted clinical note. We demonstrate our method on medical data from Weill Cornell Medicine anonymized with three deidentification tools: rule-based Philter and two deep-learning-based models, BiLSTM-CRF and ClinicalBERT. Although ClinicalBERT was the most effective, masking all identified PII, our tool still reidentified 9% of clinical notes Our study highlights significant weaknesses in current deidentification technologies while providing a tool for iterative development and improvement.

[Arxiv](https://arxiv.org/abs/2410.17035)