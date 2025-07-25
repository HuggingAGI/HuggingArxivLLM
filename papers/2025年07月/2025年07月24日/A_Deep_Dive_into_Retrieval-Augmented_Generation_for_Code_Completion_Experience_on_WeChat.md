# 深入探索增强生成式代码补全：基于微信的经验分享

发布时间：2025年07月24日

`RAG` `软件工程`

> A Deep Dive into Retrieval-Augmented Generation for Code Completion: Experience on WeChat

# 摘要

> 代码补全任务在大型语言模型（LLMs）的快速发展中取得了显著改进，作为软件工程中的关键任务，它能够有效提升开发者的生产力。近年来，检索增强生成（RAG）作为一种有前景的方法，能够提升LLMs的代码补全能力，它能够在不重新训练模型的情况下，利用代码库中的相关上下文。尽管现有研究已经证明了RAG在公共代码仓库和基准测试中的有效性，但开源与闭源代码库之间的潜在分布差异仍存在尚未探索的独特挑战。为缩小这一差距，我们进行了一项实证研究，旨在探究广泛使用的RAG方法在微信大规模专有代码库中的代码补全性能。具体而言，我们深入探索了两种主要类型的RAG方法，即基于标识符的RAG和基于相似度的RAG，涵盖了从0.5B到671B参数的26个开源LLMs。为了进行更全面的分析，我们针对基于相似度的RAG采用了不同的检索技术，包括词汇检索和语义检索。基于1,669个内部代码仓库，我们得出了几个关键发现：（1）两种RAG方法在闭源代码仓库中均表现出有效性，其中基于相似度的RAG表现更优；（2）基于相似度的RAG的有效性随着检索技术的提升而增强，其中BM25（词汇检索）和GTE-Qwen（语义检索）表现尤为突出；（3）结合词汇和语义检索技术能够取得最优结果，充分体现了各自的优势。此外，我们还开展了一项开发者调查，以验证RAG方法在真实开发环境中的实用价值。

> Code completion, a crucial task in software engineering that enhances developer productivity, has seen substantial improvements with the rapid advancement of large language models (LLMs). In recent years, retrieval-augmented generation (RAG) has emerged as a promising method to enhance the code completion capabilities of LLMs, which leverages relevant context from codebases without requiring model retraining. While existing studies have demonstrated the effectiveness of RAG on public repositories and benchmarks, the potential distribution shift between open-source and closed-source codebases presents unique challenges that remain unexplored. To mitigate the gap, we conduct an empirical study to investigate the performance of widely-used RAG methods for code completion in the industrial-scale codebase of WeChat, one of the largest proprietary software systems. Specifically, we extensively explore two main types of RAG methods, namely identifier-based RAG and similarity-based RAG, across 26 open-source LLMs ranging from 0.5B to 671B parameters. For a more comprehensive analysis, we employ different retrieval techniques for similarity-based RAG, including lexical and semantic retrieval. Based on 1,669 internal repositories, we achieve several key findings: (1) both RAG methods demonstrate effectiveness in closed-source repositories, with similarity-based RAG showing superior performance, (2) the effectiveness of similarity-based RAG improves with more advanced retrieval techniques, where BM25 (lexical retrieval) and GTE-Qwen (semantic retrieval) achieve superior performance, and (3) the combination of lexical and semantic retrieval techniques yields optimal results, demonstrating complementary strengths. Furthermore, we conduct a developer survey to validate the practical utility of RAG methods in real-world development environments.

[Arxiv](https://arxiv.org/abs/2507.18515)