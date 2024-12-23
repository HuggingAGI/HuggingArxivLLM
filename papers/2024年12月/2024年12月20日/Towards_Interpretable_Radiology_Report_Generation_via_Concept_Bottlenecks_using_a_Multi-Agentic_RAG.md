# 借助使用多智能体 RAG 的概念瓶颈来实现可解释的放射学报告生成

发布时间：2024年12月20日

`RAG` `医学图像`

> Towards Interpretable Radiology Report Generation via Concept Bottlenecks using a Multi-Agentic RAG

# 摘要

> 深度学习推动了医学图像分类的发展，然而其可解释性方面的难题阻碍了在临床上的应用。本研究借助概念瓶颈模型（CBMs）和多智能体检索增强生成（RAG）系统来生成报告，增强了胸部 X 光（CXR）分类的可解释性。通过构建视觉特征与临床概念的关系模型，我们创建出可解释的概念向量，引导多智能体 RAG 系统生成放射学报告，提升了临床相关性、可解释性和透明度。以 LLM 作为评判来评估生成的报告，证实了我们模型输出的可解释性和临床实用性。在 COVID-QU 数据集上，我们的模型分类准确率达 81%，报告生成性能强劲，五个关键指标在 84%至 90%之间。这种可解释的多智能体框架填补了高性能 AI 与临床中可靠的 AI 驱动的 CXR 分析所需的可解释性之间的空缺。

> Deep learning has advanced medical image classification, but interpretability challenges hinder its clinical adoption. This study enhances interpretability in Chest X-ray (CXR) classification by using concept bottleneck models (CBMs) and a multi-agent Retrieval-Augmented Generation (RAG) system for report generation. By modeling relationships between visual features and clinical concepts, we create interpretable concept vectors that guide a multi-agent RAG system to generate radiology reports, enhancing clinical relevance, explainability, and transparency. Evaluation of the generated reports using an LLM-as-a-judge confirmed the interpretability and clinical utility of our model's outputs. On the COVID-QU dataset, our model achieved 81% classification accuracy and demonstrated robust report generation performance, with five key metrics ranging between 84% and 90%. This interpretable multi-agent framework bridges the gap between high-performance AI and the explainability required for reliable AI-driven CXR analysis in clinical settings.

[Arxiv](https://arxiv.org/abs/2412.16086)