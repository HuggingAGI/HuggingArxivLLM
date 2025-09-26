# Decipher-MR：面向3D MRI表征的视觉-语言基础模型

发布时间：2025年09月25日

`其他` `医疗健康`

> Decipher-MR: A Vision-Language Foundation Model for 3D MRI Representations

# 摘要

> 磁共振成像（MRI）是临床诊断与研究的核心医学影像模态，然而其复杂性与异质性给自动化分析带来了难题，尤其在需要可扩展、可泛化的机器学习应用中。尽管基础模型已彻底变革自然语言与视觉任务，但其在MRI领域的应用仍受限于数据稀缺和解剖学关注点狭窄。本研究提出Decipher-MR——一种特定于3D MRI的视觉-语言基础模型，其训练数据来自大规模数据集，涵盖22,000余项研究中的200,000个MRI序列，涉及多样的解剖区域、序列类型及病理情况。Decipher-MR融合自监督视觉学习与报告引导的文本监督，构建稳健且可泛化的表征，从而实现跨广泛应用场景的高效适配。为在最小计算开销下支持稳健多样的临床任务，Decipher-MR采用模块化设计，可对附加于冻结预训练编码器的轻量级特定任务解码器进行调优。基于此设置，我们在疾病分类、人口统计学预测、解剖定位及跨模态检索等多个基准任务上评估Decipher-MR，结果显示其性能持续优于现有基础模型与特定任务方法。研究结果表明，Decipher-MR是基于MRI的AI领域可扩展、多功能的基础模型，为临床与研究领域的高效发展提供了有力支持。

> Magnetic Resonance Imaging (MRI) is a critical medical imaging modality in clinical diagnosis and research, yet its complexity and heterogeneity pose challenges for automated analysis, particularly in scalable and generalizable machine learning applications. While foundation models have revolutionized natural language and vision tasks, their application to MRI remains limited due to data scarcity and narrow anatomical focus. In this work, we present Decipher-MR, a 3D MRI-specific vision-language foundation model trained on a large-scale dataset comprising 200,000 MRI series from over 22,000 studies spanning diverse anatomical regions, sequences, and pathologies. Decipher-MR integrates self-supervised vision learning with report-guided text supervision to build robust, generalizable representations, enabling effective adaptation across broad applications. To enable robust and diverse clinical tasks with minimal computational overhead, Decipher-MR supports a modular design that enables tuning of lightweight, task-specific decoders attached to a frozen pretrained encoder. Following this setting, we evaluate Decipher-MR across diverse benchmarks including disease classification, demographic prediction, anatomical localization, and cross-modal retrieval, demonstrating consistent performance gains over existing foundation models and task-specific approaches. Our results establish Decipher-MR as a scalable and versatile foundation for MRI-based AI, facilitating efficient development across clinical and research domains.

[Arxiv](https://arxiv.org/abs/2509.21249)