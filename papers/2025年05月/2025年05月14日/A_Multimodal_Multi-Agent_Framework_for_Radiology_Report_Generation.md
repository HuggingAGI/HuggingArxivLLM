# 多模态多智能体框架在放射报告生成中的应用

发布时间：2025年05月14日

`LLM应用

摘要分析：这篇论文探讨了如何利用多模态大语言模型（MLLMs）和检索增强生成（RAG）技术来生成放射科报告。尽管提到了RAG，但论文的主要贡献在于提出了一种多智能体框架，以改进报告生成的准确性和结构化。因此，它属于LLM的应用领域。` `临床AI`

> A Multimodal Multi-Agent Framework for Radiology Report Generation

# 摘要

> # 放射科报告生成（RRG）

放射科报告生成（RRG）旨在从医学影像中自动生成诊断报告，有望提升临床工作流程，减轻放射科医生的工作负担。尽管基于多模态大语言模型（MLLMs）和检索增强生成（RAG）的近期方法取得了显著成果，但它们仍然面临事实不一致、幻觉生成以及跨模态对齐等问题。

我们提出了一种与分步临床推理工作流程相契合的多模态多智能体框架，其中任务特定的智能体分别负责检索、草稿生成、视觉分析、优化和综合。实验结果表明，我们的方法在自动评估指标和基于LLM的评估中均优于强大的基线模型，生成的报告更加准确、结构化且易于解释。

这项工作展示了与临床工作流程相契合的多智能体框架在支持可解释和可信的临床AI应用方面的潜力。

> Radiology report generation (RRG) aims to automatically produce diagnostic reports from medical images, with the potential to enhance clinical workflows and reduce radiologists' workload. While recent approaches leveraging multimodal large language models (MLLMs) and retrieval-augmented generation (RAG) have achieved strong results, they continue to face challenges such as factual inconsistency, hallucination, and cross-modal misalignment. We propose a multimodal multi-agent framework for RRG that aligns with the stepwise clinical reasoning workflow, where task-specific agents handle retrieval, draft generation, visual analysis, refinement, and synthesis. Experimental results demonstrate that our approach outperforms a strong baseline in both automatic metrics and LLM-based evaluations, producing more accurate, structured, and interpretable reports. This work highlights the potential of clinically aligned multi-agent frameworks to support explainable and trustworthy clinical AI applications.

[Arxiv](https://arxiv.org/abs/2505.09787)