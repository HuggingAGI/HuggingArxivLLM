# 安全多维度RAG企业方案：融合安全过滤的混合知识检索

发布时间：2025年04月17日

`RAG` `报告生成`

> Secure Multifaceted-RAG for Enterprise: Hybrid Knowledge Retrieval with Security Filtering

# 摘要

> 现有的 RAG 系统在企业环境中面临检索范围有限和数据安全风险的挑战。当内部文档不可用时，系统难以生成准确且完整的响应。此外，使用闭源 LLM 可能导致专有信息泄露。为了解决这些问题，我们提出了 Secure Multifaceted-RAG（SecMulti-RAG）框架，该框架不仅从内部文档中检索，还从两个补充来源中检索：针对预期查询预先生成的专家知识和按需外部 LLM 生成的知识。为了降低安全风险，我们采用本地开源生成器，并仅在过滤机制认为提示安全时选择性地使用外部 LLM。这种方法提高了完整性，防止了数据泄露，并降低了成本。在我们对汽车行业的报告生成任务的评估中，SecMulti-RAG 显著优于传统 RAG - 在基于 LLM 的评估中，正确性、丰富性和有用性方面实现了 79.3% 到 91.9% 的胜率，在人工评估中为 56.3% 到 70.4%。这凸显了 SecMulti-RAG 作为企业 RAG 实用且安全的解决方案。


> Existing Retrieval-Augmented Generation (RAG) systems face challenges in enterprise settings due to limited retrieval scope and data security risks. When relevant internal documents are unavailable, the system struggles to generate accurate and complete responses. Additionally, using closed-source Large Language Models (LLMs) raises concerns about exposing proprietary information. To address these issues, we propose the Secure Multifaceted-RAG (SecMulti-RAG) framework, which retrieves not only from internal documents but also from two supplementary sources: pre-generated expert knowledge for anticipated queries and on-demand external LLM-generated knowledge. To mitigate security risks, we adopt a local open-source generator and selectively utilize external LLMs only when prompts are deemed safe by a filtering mechanism. This approach enhances completeness, prevents data leakage, and reduces costs. In our evaluation on a report generation task in the automotive industry, SecMulti-RAG significantly outperforms traditional RAG - achieving 79.3 to 91.9 percent win rates across correctness, richness, and helpfulness in LLM-based evaluation, and 56.3 to 70.4 percent in human evaluation. This highlights SecMulti-RAG as a practical and secure solution for enterprise RAG.

[Arxiv](https://arxiv.org/abs/2504.13425)