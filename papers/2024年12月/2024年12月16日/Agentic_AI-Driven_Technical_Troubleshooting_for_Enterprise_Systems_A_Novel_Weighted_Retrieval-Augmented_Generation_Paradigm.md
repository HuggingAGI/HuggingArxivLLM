# 企业系统中由 Agentic 人工智能驱动的技术故障排除：一种全新的加权检索增强生成范式

发布时间：2024年12月16日

`RAG` `故障排查`

> Agentic AI-Driven Technical Troubleshooting for Enterprise Systems: A Novel Weighted Retrieval-Augmented Generation Paradigm

# 摘要

> 在企业环境中，技术故障排查往往需要浏览多样且异构的数据源，从而有效解决复杂问题。本文呈现了一个基于加权检索增强生成（RAG）框架的全新智能 AI 解决方案，专为企业技术故障排查量身打造。该框架会依据查询上下文，对诸如产品手册、内部知识库、常见问题解答以及故障排查指南等检索源进行动态加权，从而优先获取最相关的数据。比如，针对特定 SKU 的查询，会优先参考产品手册，同时将一般性的常见问题解答用于更宽泛的问题。系统运用 FAISS 实现高效的密集向量搜索，并搭配动态聚合机制，无缝整合来自多个来源的结果。基于 Llama 的自我评估器会在给出生成的响应前，确保其上下文的准确性和可信度。这种检索与验证的迭代循环提升了响应生成的精度、多样性和可靠性。针对大型企业数据集的初步评估显示，该框架在提高故障排查的准确性、缩短解决时间以及适应各类技术难题方面成效显著。未来的研究致力于通过融入先进的对话式 AI 能力来强化此框架，达成更具交互性和直观性的故障排查体验。同时，还将着力通过强化学习优化动态加权机制，进一步提升检索信息的相关性和精准度。凭借这些改进，所提出的框架有望发展成为一个全面、自主的 AI 解决方案，重新塑造企业环境中的技术服务工作流程。

> Technical troubleshooting in enterprise environments often involves navigating diverse, heterogeneous data sources to resolve complex issues effectively. This paper presents a novel agentic AI solution built on a Weighted Retrieval-Augmented Generation (RAG) Framework tailored for enterprise technical troubleshooting. By dynamically weighting retrieval sources such as product manuals, internal knowledge bases, FAQs, and troubleshooting guides based on query context, the framework prioritizes the most relevant data. For instance, it gives precedence to product manuals for SKU-specific queries while incorporating general FAQs for broader issues. The system employs FAISS for efficient dense vector search, coupled with a dynamic aggregation mechanism to seamlessly integrate results from multiple sources. A Llama-based self-evaluator ensures the contextual accuracy and confidence of the generated responses before delivering them. This iterative cycle of retrieval and validation enhances precision, diversity, and reliability in response generation. Preliminary evaluations on large enterprise datasets demonstrate the framework's efficacy in improving troubleshooting accuracy, reducing resolution times, and adapting to varied technical challenges. Future research aims to enhance the framework by integrating advanced conversational AI capabilities, enabling more interactive and intuitive troubleshooting experiences. Efforts will also focus on refining the dynamic weighting mechanism through reinforcement learning to further optimize the relevance and precision of retrieved information. By incorporating these advancements, the proposed framework is poised to evolve into a comprehensive, autonomous AI solution, redefining technical service workflows across enterprise settings.

[Arxiv](https://arxiv.org/abs/2412.12006)