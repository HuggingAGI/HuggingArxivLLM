# HybGRAG：关于文本和关系知识库的混合检索增强式生成

发布时间：2024年12月20日

`RAG` `知识检索` `问答系统`

> HybGRAG: Hybrid Retrieval-Augmented Generation on Textual and Relational Knowledge Bases

# 摘要

> 给定一个半结构化知识库（SKB），其中文本文档通过关系相互连接，怎样才能有效地检索相关信息来回答用户的问题呢？检索增强生成（RAG）会检索文档来辅助大型语言模型（LLM）回答问题；而图 RAG（GRAG）则以结构化知识库作为知识源。然而，很多问题都需要 SKB 中的文本和关系信息，即所谓的“混合”问题，这让检索过程变得复杂，也凸显出需要一种能利用这两种信息的混合检索方法。在本文中，通过实证分析，我们得出了关键见解，说明了为何现有方法在处理 SKB 上的混合问答（HQA）时可能会遇到难题。基于这些见解，我们提出了用于 HQA 的 HybGRAG，它由检索器组和评论模块构成，具有以下优点：（1）具有智能性，能结合评论模块的反馈自动优化输出；（2）具有适应性，能通过检索器组解决需要文本和关系信息的混合问题；（3）具有可解释性，能通过直观的优化路径为决策提供依据；（4）具有有效性，在 HQA 基准测试中超越了所有基线。在 STaRK 基准测试的实验中，HybGRAG 取得了显著的性能提升，Hit@1 的平均相对提升率达到 51%。

> Given a semi-structured knowledge base (SKB), where text documents are interconnected by relations, how can we effectively retrieve relevant information to answer user questions? Retrieval-Augmented Generation (RAG) retrieves documents to assist large language models (LLMs) in question answering; while Graph RAG (GRAG) uses structured knowledge bases as its knowledge source. However, many questions require both textual and relational information from SKB - referred to as "hybrid" questions - which complicates the retrieval process and underscores the need for a hybrid retrieval method that leverages both information. In this paper, through our empirical analysis, we identify key insights that show why existing methods may struggle with hybrid question answering (HQA) over SKB. Based on these insights, we propose HybGRAG for HQA consisting of a retriever bank and a critic module, with the following advantages: (1) Agentic, it automatically refines the output by incorporating feedback from the critic module, (2) Adaptive, it solves hybrid questions requiring both textual and relational information with the retriever bank, (3) Interpretable, it justifies decision making with intuitive refinement path, and (4) Effective, it surpasses all baselines on HQA benchmarks. In experiments on the STaRK benchmark, HybGRAG achieves significant performance gains, with an average relative improvement in Hit@1 of 51%.

[Arxiv](https://arxiv.org/abs/2412.16311)