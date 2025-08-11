# DKG-LLM：通过动态知识图谱与大语言模型的整合，实现医疗诊断与个性化治疗建议的框架方案

发布时间：2025年08月08日

`LLM应用`

> DKG-LLM : A Framework for Medical Diagnosis and Personalized Treatment Recommendations via Dynamic Knowledge Graph and Large Language Model Integration

# 摘要

> 大型语言模型（LLMs）自 ChatGPT 发布以来呈指数级增长。这些模型因其在语言处理等各项任务中的卓越表现而备受关注。通过训练数十亿参数，这些模型实现了对任务的理解和掌握。它们的发展是提升自然语言理解能力的变革性力量，并朝着通用人工智能（AGI）迈出了重要一步。

本研究介绍 DKG-LLM 框架，该框架通过将动态知识图谱（DKG）与 Grok 3 大型语言模型相结合，在医学诊断和个性化治疗建议方面开创了一种全新的方法。利用自适应语义融合算法（ASFA），异构医学数据（包括临床报告和 PubMed 文章）以及患者记录被用于动态生成一个知识图谱，包含 13 种不同类型的 15,964 个节点（如疾病、症状、治疗、患者概况）和 26 种关系类型的 127,392 条边（如因果、治疗、关联）。ASFA 利用先进的概率模型、贝叶斯推理和图优化提取语义信息，同时动态更新图谱，在每个数据类别中添加约 150 个新节点和边，同时保持可扩展性，最多可扩展至 987,654 条边。

本研究采用 MIMIC-III 和 PubMed 等真实世界数据集对提出的架构进行了评估。评估结果显示，DKG-LLM 的诊断准确率为 84.19%，治疗建议准确率为 89.63%，语义覆盖率为 93.48%。DKG-LLM 是一个可靠且变革性的工具，能够处理噪声数据和复杂多症状疾病，并能从医生输入中进行反馈式学习。

> Large Language Models (LLMs) have grown exponentially since the release of ChatGPT. These models have gained attention due to their robust performance on various tasks, including language processing tasks. These models achieve understanding and comprehension of tasks by training billions of parameters. The development of these models is a transformative force in enhancing natural language understanding and has taken a significant step towards artificial general intelligence (AGI). In this study, we aim to present the DKG-LLM framework. The DKG-LLM framework introduces a groundbreaking approach to medical diagnosis and personalized treatment recommendations by integrating a dynamic knowledge graph (DKG) with the Grok 3 large language model. Using the Adaptive Semantic Fusion Algorithm (ASFA), heterogeneous medical data (including clinical reports and PubMed articles) and patient records dynamically generate a knowledge graph consisting of 15,964 nodes in 13 distinct types (e.g., diseases, symptoms, treatments, patient profiles) and 127,392 edges in 26 relationship types (e.g., causal, therapeutic, association). ASFA utilizes advanced probabilistic models, Bayesian inference, and graph optimization to extract semantic information, dynamically updating the graph with approximately 150 new nodes and edges in each data category while maintaining scalability with up to 987,654 edges. Real-world datasets, including MIMIC-III and PubMed, were utilized to evaluate the proposed architecture. The evaluation results show that DKG-LLM achieves a diagnostic accuracy of 84.19%. The model also has a treatment recommendation accuracy of 89.63% and a semantic coverage of 93.48%. DKG-LLM is a reliable and transformative tool that handles noisy data and complex multi-symptom diseases, along with feedback-based learning from physician input.

[Arxiv](https://arxiv.org/abs/2508.06186)