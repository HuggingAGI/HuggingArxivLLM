# # DynamicBench：评测大型语言模型的实时报告生成能力

发布时间：2025年06月26日

`LLM应用

摘要中提到的DynamicBench是一个用于评估大型语言模型处理最新数据能力的基准测试，属于模型的应用和评估，因此归类为LLM应用。` `实时信息处理` `领域评估`

> DynamicBench: Evaluating Real-Time Report Generation in Large Language Models

# 摘要

> 传统大型语言模型 (LLMs) 的基准测试主要依赖于静态评估，通过叙述或观点表达进行，这些方法无法捕捉到当代应用中实时信息处理的动态需求。为了解决这一局限性，我们提出了 DynamicBench，这是一个专门用于评估 LLMs 存储和处理最新数据能力的基准测试。DynamicBench 采用双路径检索管道，结合网络搜索与本地报告数据库，确保在特定领域内生成准确的报告。通过在提供或不提供外部文档的场景中评估模型，DynamicBench 有效衡量了它们独立处理近期信息或利用上下文增强的能力。此外，我们还引入了一个先进的报告生成系统，能够高效管理动态信息综合。实验结果证实了我们的方法具有显著优势，在无文档和有文档辅助的场景下，分别比 GPT4o 高出 7.0% 和 5.8%，达到了最先进的性能。我们的代码和数据将公开发布。

> Traditional benchmarks for large language models (LLMs) typically rely on static evaluations through storytelling or opinion expression, which fail to capture the dynamic requirements of real-time information processing in contemporary applications. To address this limitation, we present DynamicBench, a benchmark designed to evaluate the proficiency of LLMs in storing and processing up-to-the-minute data. DynamicBench utilizes a dual-path retrieval pipeline, integrating web searches with local report databases. It necessitates domain-specific knowledge, ensuring accurate responses report generation within specialized fields. By evaluating models in scenarios that either provide or withhold external documents, DynamicBench effectively measures their capability to independently process recent information or leverage contextual enhancements. Additionally, we introduce an advanced report generation system adept at managing dynamic information synthesis. Our experimental results confirm the efficacy of our approach, with our method achieving state-of-the-art performance, surpassing GPT4o in document-free and document-assisted scenarios by 7.0% and 5.8%, respectively. The code and data will be made publicly available.

[Arxiv](https://arxiv.org/abs/2506.21343)