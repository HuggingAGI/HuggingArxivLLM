# 非随机模态缺失下多模态临床记录的因果表征学习

发布时间：2025年09月21日

`LLM应用` `医疗健康`

> Causal Representation Learning from Multimodal Clinical Records under Non-Random Modality Missingness

# 摘要

> 临床笔记蕴含丰富的患者信息（如诊断结果、用药情况等），因此在患者表征学习中极具价值。近年来大型语言模型的突破性进展进一步增强了从临床文本中提取有效表征的能力。但临床笔记往往存在缺失问题：例如，我们对MIMIC-IV数据集的分析显示，24.5%的患者没有可用的出院小结。这种情况下，可从结构化数据、胸部X光片、放射学报告等其他模态中学习表征。但这些模态的获取受临床决策影响，且因患者而异，从而形成模态非随机缺失（MMNAR）模式。为此，我们提出一种因果表征学习框架，该框架能充分利用多模态临床记录中的观测数据及信息性缺失。该框架包含三个核心组件：（1）MMNAR感知模态融合组件——整合结构化数据、影像与文本，并以缺失模式为条件，捕捉患者健康状态及临床决策导向的模态分配；（2）对比学习增强的模态重建组件——通过对比学习确保表征学习的语义完备性；（3）整流器辅助的多任务结果预测模型——通过整流器校正特定模态观测模式带来的残余偏差。在MIMIC-IV和eICU数据集上的综合评估表明，该框架相比现有最优基线模型性能持续提升，其中再入院预测AUC提高13.8%，ICU入院预测AUC提高13.1%。

> Clinical notes contain rich patient information, such as diagnoses or medications, making them valuable for patient representation learning. Recent advances in large language models have further improved the ability to extract meaningful representations from clinical texts. However, clinical notes are often missing. For example, in our analysis of the MIMIC-IV dataset, 24.5% of patients have no available discharge summaries. In such cases, representations can be learned from other modalities such as structured data, chest X-rays, or radiology reports. Yet the availability of these modalities is influenced by clinical decision-making and varies across patients, resulting in modality missing-not-at-random (MMNAR) patterns. We propose a causal representation learning framework that leverages observed data and informative missingness in multimodal clinical records. It consists of: (1) an MMNAR-aware modality fusion component that integrates structured data, imaging, and text while conditioning on missingness patterns to capture patient health and clinician-driven assignment; (2) a modality reconstruction component with contrastive learning to ensure semantic sufficiency in representation learning; and (3) a multitask outcome prediction model with a rectifier that corrects for residual bias from specific modality observation patterns. Comprehensive evaluations across MIMIC-IV and eICU show consistent gains over the strongest baselines, achieving up to 13.8% AUC improvement for hospital readmission and 13.1% for ICU admission.

[Arxiv](https://arxiv.org/abs/2509.17228)