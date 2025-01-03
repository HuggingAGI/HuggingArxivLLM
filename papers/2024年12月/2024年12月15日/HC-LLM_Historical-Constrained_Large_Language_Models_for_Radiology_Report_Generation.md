# HC-LLM: 历史约束下的放射学报告生成大型语言模型

发布时间：2024年12月15日

`LLM应用` `放射学`

> HC-LLM: Historical-Constrained Large Language Models for Radiology Report Generation

# 摘要

> # 放射学报告生成（RRG）模型通常聚焦于单次检查，往往忽视了历史视觉或文本数据的整合，而这对于患者随访至关重要。传统方法在处理历史信息时，常受限于长序列依赖问题，但大型语言模型（LLMs）凭借其出色的上下文学习能力，特别适合分析纵向医学数据。为此，我们提出了一种创新的历史约束大型语言模型（HC-LLM）框架，通过约束纵向图像与报告之间的一致性和差异，赋予LLMs生成纵向报告的能力。具体而言，我们从纵向胸部X光和诊断报告中提取时间共享和时间特定的特征，以捕捉疾病进展。随后，通过模态内相似性约束和多模态对比与结构约束，确保特征表示的一致性。这些约束共同引导LLMs生成准确反映疾病进展的诊断报告，在Longitudinal-MIMIC数据集上取得了领先成果。值得一提的是，我们的方法在测试时即使缺乏历史数据也能表现出色，并且能够轻松适配其他多模态大型模型，展现出强大的通用性。

> Radiology report generation (RRG) models typically focus on individual exams, often overlooking the integration of historical visual or textual data, which is crucial for patient follow-ups. Traditional methods usually struggle with long sequence dependencies when incorporating historical information, but large language models (LLMs) excel at in-context learning, making them well-suited for analyzing longitudinal medical data. In light of this, we propose a novel Historical-Constrained Large Language Models (HC-LLM) framework for RRG, empowering LLMs with longitudinal report generation capabilities by constraining the consistency and differences between longitudinal images and their corresponding reports. Specifically, our approach extracts both time-shared and time-specific features from longitudinal chest X-rays and diagnostic reports to capture disease progression. Then, we ensure consistent representation by applying intra-modality similarity constraints and aligning various features across modalities with multimodal contrastive and structural constraints. These combined constraints effectively guide the LLMs in generating diagnostic reports that accurately reflect the progression of the disease, achieving state-of-the-art results on the Longitudinal-MIMIC dataset. Notably, our approach performs well even without historical data during testing and can be easily adapted to other multimodal large models, enhancing its versatility.

[Arxiv](https://arxiv.org/abs/2412.11070)