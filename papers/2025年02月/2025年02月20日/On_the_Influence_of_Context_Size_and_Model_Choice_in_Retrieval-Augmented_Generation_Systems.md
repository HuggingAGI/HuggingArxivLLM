# 检索增强生成系统中上下文大小与模型选择的影响研究

发布时间：2025年02月20日

`RAG` `生物医学` `知识图谱`

> On the Influence of Context Size and Model Choice in Retrieval-Augmented Generation Systems

# 摘要

> 检索增强生成（RAG）作为一种方法，通过减少大型语言模型（LLMs）对静态知识的依赖并提高答案的事实性，增强了LLMs的能力。RAG通过检索相关上下文片段并基于这些片段生成答案。尽管RAG在工业界的应用日益普及，但对其组成部分的系统性探索仍然不足，特别是在理想上下文大小、基础LLM选择以及检索方法选择方面。为了帮助开发更强大的RAG系统，我们评估了不同大小的上下文、BM25和语义搜索作为检索器，以及八种基础LLMs。与常见的基于简短答案的RAG评估不同，我们探索了更具挑战性的长篇问答任务，在两个领域中，优秀答案需要充分利用整个上下文。我们的研究发现，问答性能随着上下文片段数量增加到15个而稳步提升，但超过这个数量则趋于平稳或下降。最后，我们发现不同通用LLMs在生物医学领域表现优于百科全书式领域，并且在大规模语料库中进行开放领域证据检索具有挑战性。

> Retrieval-augmented generation (RAG) has emerged as an approach to augment large language models (LLMs) by reducing their reliance on static knowledge and improving answer factuality. RAG retrieves relevant context snippets and generates an answer based on them. Despite its increasing industrial adoption, systematic exploration of RAG components is lacking, particularly regarding the ideal size of provided context, and the choice of base LLM and retrieval method. To help guide development of robust RAG systems, we evaluate various context sizes, BM25 and semantic search as retrievers, and eight base LLMs. Moving away from the usual RAG evaluation with short answers, we explore the more challenging long-form question answering in two domains, where a good answer has to utilize the entire context. Our findings indicate that final QA performance improves steadily with up to 15 snippets but stagnates or declines beyond that. Finally, we show that different general-purpose LLMs excel in the biomedical domain than the encyclopedic one, and that open-domain evidence retrieval in large corpora is challenging.

[Arxiv](https://arxiv.org/abs/2502.14759)