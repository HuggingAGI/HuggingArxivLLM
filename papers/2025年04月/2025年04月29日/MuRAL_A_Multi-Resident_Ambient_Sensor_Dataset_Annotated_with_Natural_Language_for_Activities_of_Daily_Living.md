# MuRAL：基于自然语言标注的多住户环境传感器数据集，用于日常活动识别

发布时间：2025年04月29日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在人类活动识别（HAR）中的应用，特别是在环境传感器数据上的应用。它介绍了新的数据集MuRAL，并评估了LLMs在多用户环境中的性能，属于LLM的应用研究。` `智能环境` `环境监测`

> MuRAL: A Multi-Resident Ambient Sensor Dataset Annotated with Natural Language for Activities of Daily Living

# 摘要

> 大型语言模型（LLMs）在环境传感器驱动的人类活动识别（HAR）领域展现出巨大潜力，尤其是在自然语言推理和零样本学习方面。然而，现有的CASAS、ARAS和MARBLE等数据集并非专为LLMs设计，因此在上下文丰富性、复杂性和标注精细度方面存在不足，限制了LLM能力的充分发挥。本文首次推出MuRAL——首个基于自然语言的多住户环境传感器数据集，包含从智能家庭环境中21个会话中收集的超过21小时的多用户传感器数据。MuRAL通过精细的自然语言描述、住户身份和高层活动标签进行了标注，所有这些都基于动态、现实的多住户场景。我们使用最先进的LLMs对MuRAL进行了基准测试，针对三个核心任务：主体分配、动作描述和活动分类。实验结果表明，尽管LLMs能够提供丰富的语义解释，但现有模型在处理多用户模糊性和未明确的传感器上下文方面仍面临挑战。我们公开发布MuRAL，以支持未来基于LLM的、可解释的、社会感知的智能环境活动理解研究。如需获取数据集，请通过提供的联系方式与我们联系。数据集的直接链接将在适当的时候在此处提供。

> Recent advances in Large Language Models (LLMs) have shown promising potential for human activity recognition (HAR) using ambient sensors, especially through natural language reasoning and zero-shot learning. However, existing datasets such as CASAS, ARAS, and MARBLE were not originally designed with LLMs in mind and therefore lack the contextual richness, complexity, and annotation granularity required to fully exploit LLM capabilities. In this paper, we introduce MuRAL, the first Multi-Resident Ambient sensor dataset with natural Language, comprising over 21 hours of multi-user sensor data collected from 21 sessions in a smart-home environment. MuRAL is annotated with fine-grained natural language descriptions, resident identities, and high-level activity labels, all situated in dynamic, realistic multi-resident settings. We benchmark MuRAL using state-of-the-art LLMs for three core tasks: subject assignment, action description, and activity classification. Our results demonstrate that while LLMs can provide rich semantic interpretations of ambient data, current models still face challenges in handling multi-user ambiguity and under-specified sensor contexts. We release MuRAL to support future research on LLM-powered, explainable, and socially aware activity understanding in smart environments. For access to the dataset, please reach out to us via the provided contact information. A direct link for dataset retrieval will be made available at this location in due course.

[Arxiv](https://arxiv.org/abs/2504.20505)