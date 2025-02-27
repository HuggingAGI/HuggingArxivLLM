# 高效联邦搜索在检索增强生成中的实现

发布时间：2025年02月26日

`RAG` `问答系统` `信息检索`

> Efficient Federated Search for Retrieval-Augmented Generation

# 摘要

> 大型语言模型 (LLMs) 在多个领域展现了卓越能力，但幻觉和不一致的问题仍限制了其可靠性。检索增强生成 (RAG) 通过将模型响应 grounding 在外部知识源上，有效缓解了这些问题。然而，现有的 RAG 工作流程通常依赖单一向量数据库，这在信息分散于多个存储库的常见场景下并不实际。

我们引入了 RAGRoute，一种全新的联邦 RAG 搜索机制。RAGRoute 在查询时使用轻量级神经网络分类器动态选择相关数据源。通过避免查询每个数据源，这种方法显著降低了查询开销，提升了检索效率，并减少了无关信息的检索。我们使用 MIRAGE 和 MMLU 基准测试了 RAGRoute，证明了其在减少查询数量的同时有效检索相关文档的能力。实验结果显示，RAGRoute 将总查询量减少了高达 77.5%，通信量减少了高达 76.2%。

> Large language models (LLMs) have demonstrated remarkable capabilities across various domains but remain susceptible to hallucinations and inconsistencies, limiting their reliability. Retrieval-augmented generation (RAG) mitigates these issues by grounding model responses in external knowledge sources. Existing RAG workflows often leverage a single vector database, which is impractical in the common setting where information is distributed across multiple repositories. We introduce RAGRoute, a novel mechanism for federated RAG search. RAGRoute dynamically selects relevant data sources at query time using a lightweight neural network classifier. By not querying every data source, this approach significantly reduces query overhead, improves retrieval efficiency, and minimizes the retrieval of irrelevant information. We evaluate RAGRoute using the MIRAGE and MMLU benchmarks and demonstrate its effectiveness in retrieving relevant documents while reducing the number of queries. RAGRoute reduces the total number of queries up to 77.5% and communication volume up to 76.2%.

[Arxiv](https://arxiv.org/abs/2502.19280)