# MLLM4PUE: 借助多模态大语言模型，迈向计算病理学中的通用嵌入

发布时间：2025年02月10日

`LLM应用` `人工智能`

> MLLM4PUE: Toward Universal Embeddings in Computational Pathology through Multimodal LLMs

# 摘要

> 病理学在疾病诊断中发挥着关键作用，但现有方法依赖于基于大量标注数据的任务特定模型，面临多样性和数据收集成本的可持续性挑战。我们提出，通用多模态嵌入是解决这一问题的关键，它能够支持多种下游任务。然而，传统的基于CLIP的模型独立处理图像和文本，难以捕捉复杂的多模态关系，且缺乏统一的评估基准。为此，我们推出了MLLM4PUE框架，利用多模态大型语言模型生成病理学通用嵌入。该框架不仅实现了图像与文本的深度整合，还显著提升了跨任务的理解与融合能力。同时，我们构建了病理学多模态嵌入基准（PMEB），包含来自14个数据集的15个任务，涵盖检索、分类和组合检索三大元任务。实验结果表明，MLLM4PUE表现卓越，基于MLLM的模型不仅能够高效支持多种下游任务，还为病理学基础模型的研究指明了统一方向。

> Pathology plays a critical role in diagnosing a wide range of diseases, yet existing approaches often rely heavily on task-specific models trained on extensive, well-labeled datasets. These methods face sustainability challenges due to the diversity of pathologies and the labor-intensive nature of data collection. To address these limitations, we highlight the need for universal multimodal embeddings that can support multiple downstream tasks. Previous approaches often involve fine-tuning CLIP-based models, which handle images and text separately, limiting their ability to capture complex multimodal relationships. Additionally, these models are evaluated across diverse datasets without a unified benchmark for assessing multimodal embeddings in pathology. To address these challenges, we propose MLLM4PUE, a novel framework that leverages Multimodal Large Language Models (MLLMs) to generate Pathology Universal Embeddings. The MLLM4PUE framework not only facilitates robust integration of images and text but also enhances understanding and fusion capabilities across various tasks. We further introduce the Pathology Multimodal Embedding Benchmark (PMEB), a comprehensive benchmark designed to assess the quality of pathology multimodal embeddings. PMEB comprises 15 original tasks drawn from 14 datasets, organized into three meta-tasks: retrieval, classification, and composed retrieval. Experimental results demonstrate the superiority of MLLM4PUE, illustrating MLLM-based models can effectively support a wide range of downstream tasks and unify the research direction for foundation models in pathology.

[Arxiv](https://arxiv.org/abs/2502.07221)