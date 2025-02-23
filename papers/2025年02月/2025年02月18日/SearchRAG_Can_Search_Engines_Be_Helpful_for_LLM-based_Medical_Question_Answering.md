# SearchRAG：搜索引擎能否助力基于大语言模型的医学问答？

发布时间：2025年02月18日

`RAG` `问答系统`

> SearchRAG: Can Search Engines Be Helpful for LLM-based Medical Question Answering?

# 摘要

> 大型语言模型（LLMs）在通用领域表现出色，但在需要专业知识的任务上仍有不足。传统检索增强生成（RAG）技术受限于静态知识库，信息往往过时或缺失关键临床细节，难以满足精准医疗问答需求。本研究提出SearchRAG框架，借助实时搜索引擎突破这些限制。通过合成查询生成，我们将复杂医疗问题转化为搜索引擎友好格式，并运用基于不确定性的知识筛选机制，整合最相关、最有价值的医疗知识到模型输入中。实验表明，SearchRAG显著提升了医疗问答的准确性，尤其在需要详实最新知识的复杂问题上表现优异。

> Large Language Models (LLMs) have shown remarkable capabilities in general domains but often struggle with tasks requiring specialized knowledge. Conventional Retrieval-Augmented Generation (RAG) techniques typically retrieve external information from static knowledge bases, which can be outdated or incomplete, missing fine-grained clinical details essential for accurate medical question answering. In this work, we propose SearchRAG, a novel framework that overcomes these limitations by leveraging real-time search engines. Our method employs synthetic query generation to convert complex medical questions into search-engine-friendly queries and utilizes uncertainty-based knowledge selection to filter and incorporate the most relevant and informative medical knowledge into the LLM's input. Experimental results demonstrate that our method significantly improves response accuracy in medical question answering tasks, particularly for complex questions requiring detailed and up-to-date knowledge.

[Arxiv](https://arxiv.org/abs/2502.13233)