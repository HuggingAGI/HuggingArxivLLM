# 1-800-SHARED-TASKS 在 RegNLP 中的应用：用于监管问答的语义检索的词汇重排序（LeSeR）

发布时间：2024年12月08日

`RAG` `信息检索`

> 1-800-SHARED-TASKS at RegNLP: Lexical Reranking of Semantic Retrieval (LeSeR) for Regulatory Question Answering

# 摘要

> 这篇论文展示了我们参与 COLING 2025 RegNLP RIRAG（监管信息检索与答案生成）挑战的系统描述，着重于在监管领域运用先进的信息检索和答案生成技术。我们对包括 Stella、BGE、CDE 以及 Mpnet 在内的嵌入模型进行组合试验，并通过微调与重排序来获取排名靠前的相关文档。我们采用了新颖的 LeSeR 方法，在检索方面取得了出色成果，召回率@10 达 0.8201，map@10 达 0.6655。此工作凸显了自然语言处理技术在监管应用中的变革潜能，为实现检索增强生成系统提供了思路，同时也明确了在鲁棒性和领域适应性方面有待未来改进的地方。

> This paper presents the system description of our entry for the COLING 2025 RegNLP RIRAG (Regulatory Information Retrieval and Answer Generation) challenge, focusing on leveraging advanced information retrieval and answer generation techniques in regulatory domains. We experimented with a combination of embedding models, including Stella, BGE, CDE, and Mpnet, and leveraged fine-tuning and reranking for retrieving relevant documents in top ranks. We utilized a novel approach, LeSeR, which achieved competitive results with a recall@10 of 0.8201 and map@10 of 0.6655 for retrievals. This work highlights the transformative potential of natural language processing techniques in regulatory applications, offering insights into their capabilities for implementing a retrieval augmented generation system while identifying areas for future improvement in robustness and domain adaptation.

[Arxiv](https://arxiv.org/abs/2412.06009)