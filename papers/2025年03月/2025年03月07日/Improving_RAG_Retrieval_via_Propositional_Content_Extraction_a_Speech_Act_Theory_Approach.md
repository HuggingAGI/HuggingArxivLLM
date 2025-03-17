# 优化 RAG 检索：基于言语行为理论的命题内容提取方法

发布时间：2025年03月07日

`RAG` `信息检索` `文本检索`

> Improving RAG Retrieval via Propositional Content Extraction: a Speech Act Theory Approach

# 摘要

> 用户在构建查询时，通常不仅包含所需信息，还会加入疑问句式或礼貌请求等语用标记。这些言语行为标志虽然传达了用户的意图——无论是提问、提出请求还是陈述事实——但并不一定增加查询本身的核⼼信息内容。本研究探讨了从⽤户 utterances 中提取潜在的命题内容——去除意图的语⾔标志——是否可以提升检索增强生成 (RAG) 系统中的检索质量。基于言语⾏动理论的基⽯见解，我们提出了一种将查询⾃动转换为命题等价形式的实⽤⽅法，然后再进⾏嵌入。为了评估此⽅法的效⼒，我们开展了一项实验研究，涉及与巴西电信新闻语料库相关的 63 个⽤户查询，这些查询具有预计算的语义嵌入。结果表明，在前⼏名的查询嵌⼊和⽂档嵌⼊之间，语义相似度有明显的提⾼，证实了去除⾔语⾏动指标的查询更有效地检索相关内 容。

> When users formulate queries, they often include not only the information they seek, but also pragmatic markers such as interrogative phrasing or polite requests. Although these speech act indicators communicate the user\textquotesingle s intent -- whether it is asking a question, making a request, or stating a fact -- they do not necessarily add to the core informational content of the query itself. This paper investigates whether extracting the underlying propositional content from user utterances -- essentially stripping away the linguistic markers of intent -- can improve retrieval quality in Retrieval-Augmented Generation (RAG) systems. Drawing upon foundational insights from speech act theory, we propose a practical method for automatically transforming queries into their propositional equivalents before embedding. To assess the efficacy of this approach, we conducted an experimental study involving 63 user queries related to a Brazilian telecommunications news corpus with precomputed semantic embeddings. Results demonstrate clear improvements in semantic similarity between query embeddings and document embeddings at top ranks, confirming that queries stripped of speech act indicators more effectively retrieve relevant content.

[Arxiv](https://arxiv.org/abs/2503.10654)