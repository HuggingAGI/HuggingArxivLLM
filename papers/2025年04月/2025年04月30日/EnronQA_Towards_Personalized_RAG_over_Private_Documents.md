# # **EnronQA**: 迈向私人文档的个性化 RAG

发布时间：2025年04月30日

`RAG` `问答系统`

> EnronQA: Towards Personalized RAG over Private Documents

# 摘要

> 检索增强生成（RAG）凭借其在推理过程中引入局部上下文的能力，无需微调成本或数据泄露风险，成为了将知识密集型上下文引入大型语言模型（LLM）的热门方法。通过将私人信息与LLM训练明确分离，RAG成为了企业LLM工作负载的基础，使公司能够利用客户的私人文档来增强LLM的理解能力。尽管RAG在企业部署中处理私有文档时广受欢迎，但现有基准测试却依赖于维基百科或通用网页等公开数据，几乎不提供个人上下文。为了赋予RAG更多个性化和私密性，我们发布了EnronQA基准，这是一个包含103,638封邮件的数据集，跨越150个不同用户的邮箱，总计528,304对问答。EnronQA不仅使我们能够更好地在私有数据上对RAG流水线进行基准测试，还允许在真实数据上实验个性化检索设置。最后，我们利用EnronQA探索在处理私有文档时记忆与检索之间的权衡。

> Retrieval Augmented Generation (RAG) has become one of the most popular methods for bringing knowledge-intensive context to large language models (LLM) because of its ability to bring local context at inference time without the cost or data leakage risks associated with fine-tuning. A clear separation of private information from the LLM training has made RAG the basis for many enterprise LLM workloads as it allows the company to augment LLM's understanding using customers' private documents. Despite its popularity for private documents in enterprise deployments, current RAG benchmarks for validating and optimizing RAG pipelines draw their corpora from public data such as Wikipedia or generic web pages and offer little to no personal context. Seeking to empower more personal and private RAG we release the EnronQA benchmark, a dataset of 103,638 emails with 528,304 question-answer pairs across 150 different user inboxes. EnronQA enables better benchmarking of RAG pipelines over private data and allows for experimentation on the introduction of personalized retrieval settings over realistic data. Finally, we use EnronQA to explore the tradeoff in memorization and retrieval when reasoning over private documents.

[Arxiv](https://arxiv.org/abs/2505.00263)