# 革新放射科工作流程，实现精准高效的胸片报告生成。

发布时间：2025年06月01日

`LLM应用` `医学影像`

> Revolutionizing Radiology Workflow with Factual and Efficient CXR Report Generation

# 摘要

> 医学影像解读需求的激增凸显了对先进AI解决方案的迫切需求，以提升放射诊断的效率与准确性。本文介绍的CXR-PathFinder是一款专为自动胸部X光片（CXR）报告生成而设计的新型大型语言模型（LLM）基础模型。

我们提出了一种独特的训练范式——临床专家指导的对抗式微调（CGAFT）。该方法将专家临床反馈细致融入对抗学习框架，有效缓解事实不一致问题，显著提升诊断精度。此外，我们的知识图谱增强模块（KGAM）作为推理时的安全保障，动态验证生成的医学陈述与权威知识库的一致性，从而最大限度减少幻觉，确保术语标准化。

通过一个包含数百万对CXR图像和专家报告的全面数据集，我们的实验表明，CXR-PathFinder在多个定量指标上显著超越现有最先进的医学视觉-语言模型。具体而言，临床准确性方面表现突出（宏观F1（14类）：46.5，微观F1（14类）：59.5）。

由认证放射科医生进行的盲评进一步验证了CXR-PathFinder在临床实用性、完整性和准确性方面的优势，证实了其作为放射实践可靠且高效辅助工具的潜力。该方法成功实现了高诊断保真度与计算效率的平衡，为自动医学报告生成提供了一个强大的解决方案。


> The escalating demand for medical image interpretation underscores the critical need for advanced artificial intelligence solutions to enhance the efficiency and accuracy of radiological diagnoses. This paper introduces CXR-PathFinder, a novel Large Language Model (LLM)-centric foundation model specifically engineered for automated chest X-ray (CXR) report generation. We propose a unique training paradigm, Clinician-Guided Adversarial Fine-Tuning (CGAFT), which meticulously integrates expert clinical feedback into an adversarial learning framework to mitigate factual inconsistencies and improve diagnostic precision. Complementing this, our Knowledge Graph Augmentation Module (KGAM) acts as an inference-time safeguard, dynamically verifying generated medical statements against authoritative knowledge bases to minimize hallucinations and ensure standardized terminology. Leveraging a comprehensive dataset of millions of paired CXR images and expert reports, our experiments demonstrate that CXR-PathFinder significantly outperforms existing state-of-the-art medical vision-language models across various quantitative metrics, including clinical accuracy (Macro F1 (14): 46.5, Micro F1 (14): 59.5). Furthermore, blinded human evaluation by board-certified radiologists confirms CXR-PathFinder's superior clinical utility, completeness, and accuracy, establishing its potential as a reliable and efficient aid for radiological practice. The developed method effectively balances high diagnostic fidelity with computational efficiency, providing a robust solution for automated medical report generation.

[Arxiv](https://arxiv.org/abs/2506.01118)