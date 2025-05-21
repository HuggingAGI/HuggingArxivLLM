# 基于大型语言模型的多模态 RAG 驱动激光粉末床熔合异常检测与分类

发布时间：2025年05月19日

`RAG` `增材制造` `制造过程`

> Multimodal RAG-driven Anomaly Detection and Classification in Laser Powder Bed Fusion using Large Language Models

# 摘要

> 增材制造使复杂设计的制造成为可能，同时最大限度地减少材料浪费，但该技术仍面临与缺陷和工艺异常相关的挑战。本研究提出了一种新颖的多模态检索增强生成框架，该框架利用从文献中检索的信息（包括图像和描述性文本）而非训练数据集，实现了跨多种增材制造工艺的异常检测自动化。该框架整合了从科学文献中检索文本和图像的能力，并结合多模态生成模型，在激光粉末床融合环境下实现了零样本异常识别、分类和解释生成。本研究在橡树岭国家实验室提供的四个L-PBF制造数据集上评估了所提出的框架，涵盖了不同制造商、型号和材料。评估结果展示了该框架在无需额外训练的情况下，对多样化图像的适应性和泛化能力。通过将Qwen2-VL-2B和GPT-4o-mini作为多模态大语言模型集成到框架中进行对比分析，结果显示GPT-4o-mini在制造异常分类方面优于Qwen2-VL-2B和比例随机基线。此外，对RAG系统的评估证实，通过引入检索机制，平均准确率提升了12%，降低了幻觉风险并提供了额外信息。该框架可通过整合最新研究持续更新，从而无缝适应增材制造技术的不断演进。这种可扩展、自动化且具备零样本能力的框架简化了增材制造的异常分析流程，显著提升了效率和准确性。

> Additive manufacturing enables the fabrication of complex designs while minimizing waste, but faces challenges related to defects and process anomalies. This study presents a novel multimodal Retrieval-Augmented Generation-based framework that automates anomaly detection across various Additive Manufacturing processes leveraging retrieved information from literature, including images and descriptive text, rather than training datasets. This framework integrates text and image retrieval from scientific literature and multimodal generation models to perform zero-shot anomaly identification, classification, and explanation generation in a Laser Powder Bed Fusion setting. The proposed framework is evaluated on four L-PBF manufacturing datasets from Oak Ridge National Laboratory, featuring various printer makes, models, and materials. This evaluation demonstrates the framework's adaptability and generalizability across diverse images without requiring additional training. Comparative analysis using Qwen2-VL-2B and GPT-4o-mini as MLLM within the proposed framework highlights that GPT-4o-mini outperforms Qwen2-VL-2B and proportional random baseline in manufacturing anomalies classification. Additionally, the evaluation of the RAG system confirms that incorporating retrieval mechanisms improves average accuracy by 12% by reducing the risk of hallucination and providing additional information. The proposed framework can be continuously updated by integrating emerging research, allowing seamless adaptation to the evolving landscape of AM technologies. This scalable, automated, and zero-shot-capable framework streamlines AM anomaly analysis, enhancing efficiency and accuracy.

[Arxiv](https://arxiv.org/abs/2505.13828)