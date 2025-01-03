# ENWAR: 基于RAG的多模态LLM框架，助力无线环境感知

发布时间：2024年10月08日

`RAG

理由：这篇论文提出了一个名为ENWAR的框架，该框架结合了检索增强生成（Retrieval-Augmented Generation, RAG）技术，用于处理多模态数据并提供实时态势感知。RAG技术通过结合检索和生成模型来增强语言模型的能力，使其能够更好地理解和处理复杂的多模态数据。因此，这篇论文应被归类为RAG。` `自动驾驶`

> ENWAR: A RAG-empowered Multi-Modal LLM Framework for Wireless Environment Perception

# 摘要

> # 摘要
大型语言模型（LLMs）在6G及未来网络的网络管理和编排中展现出巨大潜力。然而，现有LLMs在领域知识和多模态数据处理能力上存在局限，这对动态无线环境中的实时态势感知至关重要。本文提出ENWAR，一个环境感知的检索增强生成多模态LLM框架，填补了这一空白。ENWAR无缝整合多模态感知数据，感知、解释并认知处理复杂无线环境，提供人类可理解的态势感知。ENWAR在DeepSense6G数据集的GPS、LiDAR和摄像头模态组合上进行了评估，并与Mistral-7b/8x7b和LLaMa3.1-8/70/405b等顶尖LLMs进行了对比。相较于普通LLMs的表面化描述，ENWAR提供了更丰富的空间分析，精准定位、分析障碍物并评估车辆间视线。结果显示，ENWAR在相关性、上下文召回、正确性和忠实度等关键指标上分别达到70%、55%、80%和86%，充分证明了其在多模态感知和解释方面的卓越性能。

> Large language models (LLMs) hold significant promise in advancing network management and orchestration in 6G and beyond networks. However, existing LLMs are limited in domain-specific knowledge and their ability to handle multi-modal sensory data, which is critical for real-time situational awareness in dynamic wireless environments. This paper addresses this gap by introducing ENWAR, an ENvironment-aWARe retrieval augmented generation-empowered multi-modal LLM framework. ENWAR seamlessly integrates multi-modal sensory inputs to perceive, interpret, and cognitively process complex wireless environments to provide human-interpretable situational awareness. ENWAR is evaluated on the GPS, LiDAR, and camera modality combinations of DeepSense6G dataset with state-of-the-art LLMs such as Mistral-7b/8x7b and LLaMa3.1-8/70/405b. Compared to general and often superficial environmental descriptions of these vanilla LLMs, ENWAR delivers richer spatial analysis, accurately identifies positions, analyzes obstacles, and assesses line-of-sight between vehicles. Results show that ENWAR achieves key performance indicators of up to 70% relevancy, 55% context recall, 80% correctness, and 86% faithfulness, demonstrating its efficacy in multi-modal perception and interpretation.

[Arxiv](https://arxiv.org/abs/2410.18104)