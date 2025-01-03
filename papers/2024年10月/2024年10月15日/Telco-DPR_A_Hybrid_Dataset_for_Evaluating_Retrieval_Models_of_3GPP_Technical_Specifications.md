# Telco-DPR: 评估3GPP技术规范检索模型的混合数据集

发布时间：2024年10月15日

`RAG

理由：这篇论文主要讨论了基于3GPP技术文档的电信领域问答系统（QA），并介绍了使用RAG（Retrieval-Augmented Generation）技术的优势。RAG技术结合了检索和生成模型，用于提高问答系统的性能。论文还提到使用GPT-4作为生成模型，进一步验证了RAG技术的有效性。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。` `问答系统`

> Telco-DPR: A Hybrid Dataset for Evaluating Retrieval Models of 3GPP Technical Specifications

# 摘要

> 本文提出了一种基于3GPP技术文档的电信领域问答系统（QA），并介绍了一个混合数据集Telco-DPR，该数据集包含文本和表格结合的3GPP语料库。数据集还包括一组合成的问答对，用于评估QA系统在此类数据上的检索性能。我们评估并比较了稀疏模型BM25和密集模型DPR、DHR的Top-K准确率和MRR。结果显示，DHR通过在文档和段落级别进行微调的分层段落选择，在检索技术信息方面优于传统方法，Top-10准确率达到86.2%。此外，我们评估了QA系统中使用的RAG技术，展示了混合数据集和DHR的优势。提出的QA系统结合RAG模型和GPT-4，答案准确率比之前基准提高了14%。

> This paper proposes a Question-Answering (QA) system for the telecom domain using 3rd Generation Partnership Project (3GPP) technical documents. Alongside, a hybrid dataset, Telco-DPR, which consists of a curated 3GPP corpus in a hybrid format, combining text and tables, is presented. Additionally, the dataset includes a set of synthetic question/answer pairs designed to evaluate the retrieval performance of QA systems on this type of data. The retrieval models, including the sparse model, Best Matching 25 (BM25), as well as dense models, such as Dense Passage Retriever (DPR) and Dense Hierarchical Retrieval (DHR), are evaluated and compared using top-K accuracy and Mean Reciprocal Rank (MRR). The results show that DHR, a retriever model utilising hierarchical passage selection through fine-tuning at both the document and passage levels, outperforms traditional methods in retrieving relevant technical information, achieving a Top-10 accuracy of 86.2%. Additionally, the Retriever-Augmented Generation (RAG) technique, used in the proposed QA system, is evaluated to demonstrate the benefits of using the hybrid dataset and the DHR. The proposed QA system, using the developed RAG model and the Generative Pretrained Transformer (GPT)-4, achieves a 14% improvement in answer accuracy, when compared to a previous benchmark on the same dataset.

[Arxiv](https://arxiv.org/abs/2410.19790)