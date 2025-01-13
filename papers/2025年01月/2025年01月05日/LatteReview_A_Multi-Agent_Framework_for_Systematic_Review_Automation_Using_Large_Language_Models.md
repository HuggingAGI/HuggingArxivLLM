# LatteReview: 基于大型语言模型的多智能体系统综述自动化框架

发布时间：2025年01月05日

`Agent

理由：这篇论文介绍了一个名为LatteReview的框架，该框架利用LLMs和多智能体系统来自动化系统文献综述的关键步骤。论文中提到的“多智能体系统”和“模块化智能体”表明该研究主要关注智能体（Agent）的设计和应用，而不是单纯的LLM应用或理论。因此，将其分类为Agent更为合适。` `文献综述` `自动化`

> LatteReview: A Multi-Agent Framework for Systematic Review Automation Using Large Language Models

# 摘要

> # 摘要
系统文献综述和元分析是整合研究见解的关键，但其筛选、评估和数据提取的迭代过程耗时且繁琐。本文介绍了LatteReview，一个基于Python的框架，利用LLMs和多智能体系统自动化系统综述的关键步骤。LatteReview通过模块化智能体简化工作流程，执行标题和摘要筛选、相关性评分及结构化数据提取等任务。这些智能体在编排的工作流程中运行，支持顺序和并行评审、动态决策及基于用户反馈的迭代优化。LatteReview的架构兼容云和本地LLM模型，支持RAG整合外部上下文、多模态评审、Pydantic验证和异步编程处理大规模数据。该框架已在GitHub开源，提供详细文档和安装包。

> Systematic literature reviews and meta-analyses are essential for synthesizing research insights, but they remain time-intensive and labor-intensive due to the iterative processes of screening, evaluation, and data extraction. This paper introduces and evaluates LatteReview, a Python-based framework that leverages large language models (LLMs) and multi-agent systems to automate key elements of the systematic review process. Designed to streamline workflows while maintaining rigor, LatteReview utilizes modular agents for tasks such as title and abstract screening, relevance scoring, and structured data extraction. These agents operate within orchestrated workflows, supporting sequential and parallel review rounds, dynamic decision-making, and iterative refinement based on user feedback. LatteReview's architecture integrates LLM providers, enabling compatibility with both cloud-based and locally hosted models. The framework supports features such as Retrieval-Augmented Generation (RAG) for incorporating external context, multimodal reviews, Pydantic-based validation for structured inputs and outputs, and asynchronous programming for handling large-scale datasets. The framework is available on the GitHub repository, with detailed documentation and an installable package.

[Arxiv](https://arxiv.org/abs/2501.05468)