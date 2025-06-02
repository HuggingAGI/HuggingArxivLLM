# 自动化结构化放射报告生成

发布时间：2025年05月30日

`LLM应用` `医学影像分析`

> Automated Structured Radiology Report Generation

# 摘要

> 从胸部X光片（CXR图像）自动生成放射科报告，能够显著提升临床效率并有效减轻放射科医生的工作负担。然而，目前包括MIMIC-CXR和CheXpert Plus在内的大多数数据集，均由自由形式的报告组成，这些报告具有高度变异性且缺乏结构化，这给报告生成和评估带来了双重挑战：现有模型难以生成一致且具有临床意义的报告，标准评估指标也难以捕捉放射学解读的细微差别。为解决这一问题，我们提出了结构化放射科报告生成（SRRG）这一新任务，旨在将自由文本放射科报告重新格式化为标准化结构，以确保报告的清晰性、一致性和结构化临床表述。我们通过大型语言模型（LLMs）遵循严格的结构化报告标准，重新构建了报告，创建了一个全新的数据集。此外，我们引入了SRR-BERT，这是一个基于55个标签的细粒度疾病分类模型，能够实现更精确且具有临床依据的结构化报告评估。为了评估报告质量，我们提出了F1-SRR-BERT这一指标，该指标借助SRR-BERT的层级疾病分类法，有效弥合了自由文本变异性与结构化临床报告之间的差距。我们通过五名认证放射科医生进行的读者研究和广泛的基准测试实验，对我们的数据集进行了全面验证。

> Automated radiology report generation from chest X-ray (CXR) images has the potential to improve clinical efficiency and reduce radiologists' workload. However, most datasets, including the publicly available MIMIC-CXR and CheXpert Plus, consist entirely of free-form reports, which are inherently variable and unstructured. This variability poses challenges for both generation and evaluation: existing models struggle to produce consistent, clinically meaningful reports, and standard evaluation metrics fail to capture the nuances of radiological interpretation. To address this, we introduce Structured Radiology Report Generation (SRRG), a new task that reformulates free-text radiology reports into a standardized format, ensuring clarity, consistency, and structured clinical reporting. We create a novel dataset by restructuring reports using large language models (LLMs) following strict structured reporting desiderata. Additionally, we introduce SRR-BERT, a fine-grained disease classification model trained on 55 labels, enabling more precise and clinically informed evaluation of structured reports. To assess report quality, we propose F1-SRR-BERT, a metric that leverages SRR-BERT's hierarchical disease taxonomy to bridge the gap between free-text variability and structured clinical reporting. We validate our dataset through a reader study conducted by five board-certified radiologists and extensive benchmarking experiments.

[Arxiv](https://arxiv.org/abs/2505.24223)