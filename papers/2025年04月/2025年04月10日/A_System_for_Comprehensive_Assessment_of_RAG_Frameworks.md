# # RAG框架全面评估系统

发布时间：2025年04月10日

`RAG` `软件工程`

> A System for Comprehensive Assessment of RAG Frameworks

# 摘要

> 检索增强生成（RAG）作为通过整合检索机制提升大型语言模型事实准确性与上下文相关性的标准范式，然而现有评估框架在全面黑箱评估尤其是真实部署场景中存在不足。为填补这一空白，我们推出SCARF（RAG框架综合评估系统），这是一个模块化且灵活的评估框架，专为系统性基准测试已部署RAG应用而设计。SCARF提供端到端黑箱评估方法，支持跨不同RAG框架的低投入比较。它支持多种部署配置，可自动化测试向量数据库和LLM服务策略，并生成详尽性能报告。SCARF整合响应连贯性等实际考量，为研究人员和行业专家提供了可扩展且适应性强的RAG应用评估解决方案。通过REST APIs接口，我们展示了SCARF在真实场景中的应用，凸显其在评估不同RAG框架和配置时的灵活性。SCARF已在GitHub上开源。

> Retrieval Augmented Generation (RAG) has emerged as a standard paradigm for enhancing the factual accuracy and contextual relevance of Large Language Models (LLMs) by integrating retrieval mechanisms. However, existing evaluation frameworks fail to provide a holistic black-box approach to assessing RAG systems, especially in real-world deployment scenarios. To address this gap, we introduce SCARF (System for Comprehensive Assessment of RAG Frameworks), a modular and flexible evaluation framework designed to benchmark deployed RAG applications systematically. SCARF provides an end-to-end, black-box evaluation methodology, enabling a limited-effort comparison across diverse RAG frameworks. Our framework supports multiple deployment configurations and facilitates automated testing across vector databases and LLM serving strategies, producing a detailed performance report. Moreover, SCARF integrates practical considerations such as response coherence, providing a scalable and adaptable solution for researchers and industry professionals evaluating RAG applications. Using the REST APIs interface, we demonstrate how SCARF can be applied to real-world scenarios, showcasing its flexibility in assessing different RAG frameworks and configurations. SCARF is available at GitHub repository.

[Arxiv](https://arxiv.org/abs/2504.07803)