# SA-OOSC：一种多模态LLM蒸馏语义通信框架，通过场景理解提升编码效率

发布时间：2025年09月09日

`LLM应用` `基础理论`

> SA-OOSC: A Multimodal LLM-Distilled Semantic Communication Framework for Enhanced Coding Efficiency with Scenario Understanding

# 摘要

> 本文提出SA-OOSC——一种基于多模态大型语言模型（MLLM）蒸馏的语义通信框架，可通过场景感知的重要性分配实现高效语义编码。该方法破解了现有面向对象语义通信（OOSC）系统的一大痛点：为特定类别对象分配静态重要性值，却忽略其上下文相关性。我们的框架借助MLLMs识别图像中各对象的场景增强（SA）语义重要性，再通过MLLM标注数据进行知识蒸馏，让向量化/反向量化网络与JSCC编码器/解码器学会根据上下文重要性动态分配编码资源——也就是依据任务的SA场景信息区分高、低重要性对象。该框架包含三项核心创新：MLLM引导的知识蒸馏管道、重要性加权的变长JSCC框架，以及可促进JSCC框架内知识蒸馏的新颖损失函数设计。实验验证显示，我们的框架相较于传统语义通信系统编码效率更优，同时开源的MLLM标注与人工验证数据集也成为了语义通信领域未来研究的新基准。

> This paper introduces SA-OOSC, a multimodal large language models (MLLM)-distilled semantic communication framework that achieves efficient semantic coding with scenario-aware importance allocations. This approach addresses a critical limitation of existing object-oriented semantic communication (OOSC) systems - assigning static importance values to specific classes of objects regardless of their contextual relevance. Our framework utilizes MLLMs to identify the scenario-augmented (SA) semantic importance for objects within the image. Through knowledge distillation with the MLLM-annotated data, our vectorization/de-vectorization networks and JSCC encoder/decoder learn to dynamically allocate coding resources based on contextual significance, i.e., distinguishing between high-importance objects and low-importance according to the SA scenario information of the task. The framework features three core innovations: a MLLM-guided knowledge distillation pipeline, an importance-weighted variable-length JSCC framework, and novel loss function designs that facilitate the knowledge distillation within the JSCC framework. Experimental validation demonstrates our framework's superior coding efficiency over conventional semantic communication systems, with open-sourced MLLM-annotated and human-verified datasets established as new benchmarks for future research in semantic communications.

[Arxiv](https://arxiv.org/abs/2509.07436)