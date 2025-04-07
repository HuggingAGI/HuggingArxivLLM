# 基于LLMs的AI招聘：一个上下文感知且可解释的多智能体框架用于简历筛选

发布时间：2025年04月01日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在招聘流程中的应用，特别是在简历筛选和评估方面的应用。虽然文中提到了多智能体框架和RAG技术，但整体研究的核心是LLMs的实际应用，因此归类为LLM应用。` `人力资源管理` `人工智能`

> AI Hiring with LLMs: A Context-Aware and Explainable Multi-Agent Framework for Resume Screening

# 摘要

> 简历筛选是人才获取中既关键又耗时的过程，招聘人员需在保持客观、准确和公平的同时分析大量求职申请。随着大型语言模型（LLMs）的进步，其推理能力和广泛的知识库为招聘工作流程的简化和自动化带来了新机遇。本研究提出了一种基于LLMs的多智能体框架，用于系统地处理和评估简历。该框架由四个核心智能体组成：简历提取器、评估器、总结器和评分格式化器。为了增强候选人评估的上下文相关性，我们在简历评估器中集成了检索增强生成（RAG），整合了行业特定专业知识、专业认证、大学排名和公司特定招聘标准等外部知识来源。这种动态适应使个性化招聘成为可能，弥合了AI自动化与人才获取之间的差距。我们通过在匿名在线简历数据集上将AI生成的评分与人力资源专业人士提供的评分进行比较，评估了我们的方法的有效性。研究结果突显了多智能体RAG-LLM系统在自动化简历筛选中的潜力，使招聘工作流程更加高效和可扩展。

> Resume screening is a critical yet time-intensive process in talent acquisition, requiring recruiters to analyze vast volume of job applications while remaining objective, accurate, and fair. With the advancements in Large Language Models (LLMs), their reasoning capabilities and extensive knowledge bases demonstrate new opportunities to streamline and automate recruitment workflows. In this work, we propose a multi-agent framework for resume screening using LLMs to systematically process and evaluate resumes. The framework consists of four core agents, including a resume extractor, an evaluator, a summarizer, and a score formatter. To enhance the contextual relevance of candidate assessments, we integrate Retrieval-Augmented Generation (RAG) within the resume evaluator, allowing incorporation of external knowledge sources, such as industry-specific expertise, professional certifications, university rankings, and company-specific hiring criteria. This dynamic adaptation enables personalized recruitment, bridging the gap between AI automation and talent acquisition. We assess the effectiveness of our approach by comparing AI-generated scores with ratings provided by HR professionals on a dataset of anonymized online resumes. The findings highlight the potential of multi-agent RAG-LLM systems in automating resume screening, enabling more efficient and scalable hiring workflows.

[Arxiv](https://arxiv.org/abs/2504.02870)