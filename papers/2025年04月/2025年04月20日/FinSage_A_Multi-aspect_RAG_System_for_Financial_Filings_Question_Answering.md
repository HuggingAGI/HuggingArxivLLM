# # FinSage: 专为财务文件问答设计的多维度RAG系统

发布时间：2025年04月20日

`RAG` `问答系统`

> FinSage: A Multi-aspect RAG System for Financial Filings Question Answering

# 摘要

> 在实际应用中，大型语言模型的使用往往需要结合领域特定的数据和工具，以确保符合复杂的合规要求。在金融领域，现代企业越来越多地依赖检索增强生成（RAG）系统来应对金融文档工作流程中的复杂合规需求。然而，现有解决方案在处理金融文件中数据的异质性（如文本、表格、图表）以及监管标准的动态变化时，常常难以兼顾，导致关键信息提取的准确性受到影响。为此，我们提出了FinSage框架，这是一个专为多模态金融文档合规性分析设计的多维度RAG框架。FinSage带来了三个创新组件：（1）一个多模态预处理管道，统一了各种数据格式并生成基于块级别的元数据摘要；（2）一个多路径稀疏-稠密检索系统，结合了查询扩展（HyDE）和基于元数据的语义搜索；（3）一个针对特定领域优化的重排序模块，通过直接偏好优化（DPO）微调，优先考虑合规性关键内容。实验结果表明，FinSage在75个专家精选的问题上实现了高达92.51%的召回率，并在FinanceBench问答数据集上，准确率比最佳基线方法高出24.06%。此外，FinSage已成功部署为在线会议中的金融问答代理，迄今已服务超过1,200人。


> Leveraging large language models in real-world settings often entails a need to utilize domain-specific data and tools in order to follow the complex regulations that need to be followed for acceptable use. Within financial sectors, modern enterprises increasingly rely on Retrieval-Augmented Generation (RAG) systems to address complex compliance requirements in financial document workflows. However, existing solutions struggle to account for the inherent heterogeneity of data (e.g., text, tables, diagrams) and evolving nature of regulatory standards used in financial filings, leading to compromised accuracy in critical information extraction. We propose the FinSage framework as a solution, utilizing a multi-aspect RAG framework tailored for regulatory compliance analysis in multi-modal financial documents. FinSage introduces three innovative components: (1) a multi-modal pre-processing pipeline that unifies diverse data formats and generates chunk-level metadata summaries, (2) a multi-path sparse-dense retrieval system augmented with query expansion (HyDE) and metadata-aware semantic search, and (3) a domain-specialized re-ranking module fine-tuned via Direct Preference Optimization (DPO) to prioritize compliance-critical content. Extensive experiments demonstrate that FinSage achieves an impressive recall of 92.51% on 75 expert-curated questions derived from surpasses the best baseline method on the FinanceBench question answering datasets by 24.06% in accuracy. Moreover, FinSage has been successfully deployed as financial question-answering agent in online meetings, where it has already served more than 1,200 people.

[Arxiv](https://arxiv.org/abs/2504.14493)