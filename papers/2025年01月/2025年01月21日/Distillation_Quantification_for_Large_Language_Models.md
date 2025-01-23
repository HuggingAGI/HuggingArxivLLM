# # 大型语言模型的蒸馏量化

发布时间：2025年01月21日

`LLM理论

理由：这篇论文主要探讨了模型蒸馏技术对大型语言模型（LLMs）的影响，并提出了一套评估与量化模型蒸馏的框架。研究内容涉及模型蒸馏的理论分析、量化方法以及对模型多样性和性能的影响，属于对LLM的理论研究和分析，因此归类为“LLM理论”。` `模型优化`

> Distillation Quantification for Large Language Models

# 摘要

> # 摘要
模型蒸馏技术旨在将大型语言模型（LLMs）的知识迁移至更小的模型，以打造资源高效且性能卓越的模型。然而，过度蒸馏可能引发同质化，削弱模型多样性，降低其应对复杂或新颖任务的能力。这些挑战凸显了系统量化蒸馏过程及其影响的迫切需求。本研究提出了一套评估与量化模型蒸馏的框架，聚焦两大核心：（1）通过识别身份认知矛盾，评估模型在身份信息处理上的差异；（2）通过分析模型间多粒度响应相似性，衡量同质化程度。实验揭示了两大关键发现：（1）除Claude、Doubao和Gemini外，知名闭源与开源LLMs普遍呈现高蒸馏度；（2）基础LLMs相较于对齐LLMs，蒸馏度更高。我们倡导开发更独立、技术报告更透明的LLMs，以增强其鲁棒性与安全性，相关代码与数据已开源于https://github.com/Aegis1863/LLMs-Distillation-Quantification。

> Model distillation is a technique for transferring knowledge from large language models (LLMs) to smaller ones, aiming to create resource-efficient yet high-performing models. However, excessive distillation can lead to homogenization, reducing diversity among models and impairing their ability to robustly handle complex or novel tasks. These limitations underscore the need to systematically quantify the distillation process and its impact. In this work, we propose a framework to evaluate and quantify model distillation. Our method addresses two key aspects: (1) Identifying identity cognition contradictions to assess discrepancies in how models perceive and represent identity-related information, and (2) Analyzing multi-granularity response similarities across models to measure the extent of homogenization. Experimental results demonstrate two key insights: (1) Well-known closed-source and open-source LLMs usually exhibit high distillation degrees, except for Claude, Doubao, and Gemini. (2) Base LLMs show higher distillation degrees compared to aligned LLMs. By offering a systematic approach to improve the transparency of LLM data distillation, we call for LLMs with more independent development and more transparent technical reports to improve LLMs' robustness and safety. The code and data are available under https://github.com/Aegis1863/LLMs-Distillation-Quantification.

[Arxiv](https://arxiv.org/abs/2501.12619)