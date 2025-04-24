# EMRModel：用于将医疗咨询对话转化为结构化医疗记录的大型语言模型

发布时间：2025年04月23日

`LLM应用` `电子病历`

> EMRModel: A Large Language Model for Extracting Medical Consultation Dialogues into Structured Medical Records

# 摘要

> 医疗咨询对话蕴含关键临床信息，但其非结构化的特性限制了在诊疗中的有效应用。传统基于规则或浅层机器学习的方法难以捕捉深层语义。我们提出了EMRModel，一种结合LoRA微调与代码式提示设计的创新方法，旨在高效转换医疗咨询对话为结构化电子病历。同时，我们构建了一个高质量、现实导向的医疗咨询对话数据集，并引入了细粒度的医疗信息提取评估基准。实验表明，EMRModel的F1分数达到88.1%，较标准模型提升49.5%，展现了其在医疗记录提取中的显著优势。


> Medical consultation dialogues contain critical clinical information, yet their unstructured nature hinders effective utilization in diagnosis and treatment. Traditional methods, relying on rule-based or shallow machine learning techniques, struggle to capture deep and implicit semantics. Recently, large pre-trained language models and Low-Rank Adaptation (LoRA), a lightweight fine-tuning method, have shown promise for structured information extraction. We propose EMRModel, a novel approach that integrates LoRA-based fine-tuning with code-style prompt design, aiming to efficiently convert medical consultation dialogues into structured electronic medical records (EMRs). Additionally, we construct a high-quality, realistically grounded dataset of medical consultation dialogues with detailed annotations. Furthermore, we introduce a fine-grained evaluation benchmark for medical consultation information extraction and provide a systematic evaluation methodology, advancing the optimization of medical natural language processing (NLP) models. Experimental results show EMRModel achieves an F1 score of 88.1%, improving by49.5% over standard pre-trained models. Compared to traditional LoRA fine-tuning methods, our model shows superior performance, highlighting its effectiveness in structured medical record extraction tasks.

[Arxiv](https://arxiv.org/abs/2504.16448)