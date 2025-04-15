# DataMosaic: 通过 Extract-Reason-Verify 方法实现可解释且可验证的多模态数据分析

发布时间：2025年04月14日

`LLM应用` `数据分析` `多模态数据`

> DataMosaic: Explainable and Verifiable Multi-Modal Data Analytics through Extract-Reason-Verify

# 摘要

> 大型语言模型（LLMs）正在重塑数据分析领域，但它们的广泛应用受到两大关键限制的制约：推理过程不透明且容易产生幻觉和错误。尽管检索增强生成（RAG）通过结合外部数据提高了准确性，但它未能解决可信数据分析的核心挑战，尤其是在处理噪声、不一致或多模态数据时。为此，我们提出DataMosaic框架，旨在使LLM驱动的数据分析既可解释又可验证。通过动态提取任务特定的结构（例如表格、图、树）从原始数据中，DataMosaic提供了透明的、逐步的推理轨迹，并支持对中间结果进行验证。DataMosaic基于多智能体框架构建，协调自适应智能体，使其与下游任务需求保持一致，从而提升一致性、完整性和隐私性。通过这种方法，DataMosaic不仅克服了现有LLM驱动数据分析系统中的局限性，还为基于真实数据、准确且可解释的多模态数据分析奠定了新范式。

> Large Language Models (LLMs) are transforming data analytics, but their widespread adoption is hindered by two critical limitations: they are not explainable (opaque reasoning processes) and not verifiable (prone to hallucinations and unchecked errors). While retrieval-augmented generation (RAG) improves accuracy by grounding LLMs in external data, it fails to address the core challenges of trustworthy analytics - especially when processing noisy, inconsistent, or multi-modal data (for example, text, tables, images). We propose DataMosaic, a framework designed to make LLM-powered analytics both explainable and verifiable. By dynamically extracting task-specific structures (for example, tables, graphs, trees) from raw data, DataMosaic provides transparent, step-by-step reasoning traces and enables validation of intermediate results. Built on a multi-agent framework, DataMosaic orchestrates self-adaptive agents that align with downstream task requirements, enhancing consistency, completeness, and privacy. Through this approach, DataMosaic not only tackles the limitations of current LLM-powered analytics systems but also lays the groundwork for a new paradigm of grounded, accurate, and explainable multi-modal data analytics.

[Arxiv](https://arxiv.org/abs/2504.10036)