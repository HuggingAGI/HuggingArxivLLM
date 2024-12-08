# MaintAGT：基于 Sim2Real 引导的用于智能维护且具备思维链推理的多模态大型模型

发布时间：2024年11月30日

`LLM应用` `智能运维`

> MaintAGT:Sim2Real-Guided Multimodal Large Model for Intelligent Maintenance with Chain-of-Thought Reasoning

# 摘要

> 近年来，大型语言模型在自然语言处理领域成就斐然，然而在特定领域知识及应用方面仍存短板。本文提出了 MaintAGT，这一用于智能运维的专业大型模型，意在攻克此难题。该系统涵盖三个关键部分：信号到文本模型、纯文本模型以及多模态模型。其一，信号到文本模型旨在将原始信号数据转化为文本描述，填补了信号数据与基于文本的分析之间的鸿沟。其二，运用具备专业知识的 GLM4 模型对纯文本模型进行微调，以强化其对特定领域文本的理解。最后，将这两个模型整合构建了一个综合的多模态模型，能够高效处理和分析信号与文本数据。用于训练和评估的数据集源自学术论文、教科书、国际标准以及振动分析师培训资料，历经精细预处理以保障数据的高质量。正因如此，该模型在多项智能运维任务中表现出众，为构建大规模监测信号 - 文本描述 - 故障模式数据集提供了一种低成本、高质量的途径。实验结果显示，该模型在状态监测、信号处理和故障诊断等方面优势显著。在构建的通用测试集中，MaintAGT 的准确率达 70%，超越了所有现有的通用大型语言模型，达到了 ISO 三级人类振动分析师的水准。这一进展意味着从传统维护实践朝着智能和人工智能驱动的维护解决方案迈出了关键的一步。

> In recent years, large language models have made significant advancements in the field of natural language processing, yet there are still inadequacies in specific domain knowledge and applications. This paper Proposes MaintAGT, a professional large model for intelligent operations and maintenance, aimed at addressing this issue. The system comprises three key components: a signal-to-text model, a pure text model, and a multimodal model. Firstly, the signal-to-text model was designed to convert raw signal data into textual descriptions, bridging the gap between signal data and text-based analysis. Secondly, the pure text model was fine-tuned using the GLM4 model with specialized knowledge to enhance its understanding of domain-specific texts. Finally, these two models were integrated to develop a comprehensive multimodal model that effectively processes and analyzes both signal and textual data.The dataset used for training and evaluation was sourced from academic papers, textbooks, international standards, and vibration analyst training materials, undergoing meticulous preprocessing to ensure high-quality data. As a result, the model has demonstrated outstanding performance across multiple intelligent operations and maintenance tasks, providing a low-cost, high-quality method for constructing large-scale monitoring signal-text description-fault pattern datasets. Experimental results indicate that the model holds significant advantages in condition monitoring, signal processing, and fault diagnosis.In the constructed general test set, MaintAGT achieved an accuracy of 70%, surpassing all existing general large language models and reaching the level of an ISO Level III human vibration analyst.This advancement signifies a crucial step forward from traditional maintenance practices toward intelligent and AI-driven maintenance solutions.

[Arxiv](https://arxiv.org/abs/2412.00481)