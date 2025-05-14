# 基于检索增强生成的高效可复现生物医学问答系统

发布时间：2025年05月12日

`RAG` `生物医学` `问答系统`

> Efficient and Reproducible Biomedical Question Answering using Retrieval Augmented Generation

# 摘要

> 生物医学问答系统需要高效的检索与生成组件，以确保准确性、效率和可扩展性。本研究系统性地考察了生物医学问答中的检索增强生成（RAG）系统，评估了检索策略和响应时间的权衡。我们首先评估了BM25、BioBERT、MedCPT以及混合方法等先进的检索方法，以及Elasticsearch、MongoDB和FAISS等常用数据存储，使用PubMed约10%的子集（240万份文档）来衡量索引效率、检索延迟和检索器在端到端RAG系统中的性能。基于这些见解，我们将在完整的2400万PubMed语料库上部署最终的RAG系统，比较不同检索器对整体性能的影响。检索深度的评估表明，先用BM25检索50份文档，再通过MedCPT进行重排序，可以在准确率（0.90）、召回率（0.90）和响应时间（1.91秒）之间取得最佳平衡。BM25检索时间保持稳定（82毫秒），而MedCPT则承担了主要的计算成本。这些结果突显了生物医学问答中检索深度、效率和可扩展性之间鲜为人知的权衡。通过开源代码，该系统完全可复现并易于扩展。

> Biomedical question-answering (QA) systems require effective retrieval and generation components to ensure accuracy, efficiency, and scalability. This study systematically examines a Retrieval-Augmented Generation (RAG) system for biomedical QA, evaluating retrieval strategies and response time trade-offs. We first assess state-of-the-art retrieval methods, including BM25, BioBERT, MedCPT, and a hybrid approach, alongside common data stores such as Elasticsearch, MongoDB, and FAISS, on a ~10% subset of PubMed (2.4M documents) to measure indexing efficiency, retrieval latency, and retriever performance in the end-to-end RAG system. Based on these insights, we deploy the final RAG system on the full 24M PubMed corpus, comparing different retrievers' impact on overall performance. Evaluations of the retrieval depth show that retrieving 50 documents with BM25 before reranking with MedCPT optimally balances accuracy (0.90), recall (0.90), and response time (1.91s). BM25 retrieval time remains stable (82ms), while MedCPT incurs the main computational cost. These results highlight previously not well-known trade-offs in retrieval depth, efficiency, and scalability for biomedical QA. With open-source code, the system is fully reproducible and extensible.

[Arxiv](https://arxiv.org/abs/2505.07917)