# RemoteRAG：一项具备隐私保护功能的 LLM 云 RAG 服务

发布时间：2024年12月17日

`RAG` `云计算` `隐私保护`

> RemoteRAG: A Privacy-Preserving LLM Cloud RAG Service

# 摘要

> 检索增强生成（RAG）能从可靠文献中检索相关文档，并融入用户查询的语境，从而提升大型语言模型的服务质量。近来，云 RAG 服务兴起，方便了用户查询相关文档。但直接向云端发送查询，可能导致隐私泄露。本文中，我们率先正式定义了保护隐私的云 RAG 服务来守护用户查询，并提出 RemoteRAG 作为兼顾隐私、效率与准确性的解决方案。在隐私方面，我们引入$(n,ε)$-DistanceDP 来刻画用户查询的隐私泄露以及从相关文档推断出的泄露情况。在效率方面，我们把搜索范围从全部文档缩小到与由$(n,ε)$-DistanceDP 生成的扰动嵌入相关的少量选定文档，大幅降低了隐私保护所需的计算和通信成本。在准确性方面，我们通过详尽的理论分析，确保小范围涵盖与用户查询相关的目标文档。实验结果显示，RemoteRAG 能够抵御现有的嵌入反转攻击方法，且在各种设置下检索时毫无损失。此外，RemoteRAG 效率颇高，从总计 10^6 个文档中检索时，仅需 0.67 秒和 46.66KB 的数据传输（未优化的隐私保护方案则需 2.72 小时和 1.43GB）。

> Retrieval-augmented generation (RAG) improves the service quality of large language models by retrieving relevant documents from credible literature and integrating them into the context of the user query. Recently, the rise of the cloud RAG service has made it possible for users to query relevant documents conveniently. However, directly sending queries to the cloud brings potential privacy leakage. In this paper, we are the first to formally define the privacy-preserving cloud RAG service to protect the user query and propose RemoteRAG as a solution regarding privacy, efficiency, and accuracy. For privacy, we introduce $(n,ε)$-DistanceDP to characterize privacy leakage of the user query and the leakage inferred from relevant documents. For efficiency, we limit the search range from the total documents to a small number of selected documents related to a perturbed embedding generated from $(n,ε)$-DistanceDP, so that computation and communication costs required for privacy protection significantly decrease. For accuracy, we ensure that the small range includes target documents related to the user query with detailed theoretical analysis. Experimental results also demonstrate that RemoteRAG can resist existing embedding inversion attack methods while achieving no loss in retrieval under various settings. Moreover, RemoteRAG is efficient, incurring only $0.67$ seconds and $46.66$KB of data transmission ($2.72$ hours and $1.43$ GB with the non-optimized privacy-preserving scheme) when retrieving from a total of $10^6$ documents.

[Arxiv](https://arxiv.org/abs/2412.12775)