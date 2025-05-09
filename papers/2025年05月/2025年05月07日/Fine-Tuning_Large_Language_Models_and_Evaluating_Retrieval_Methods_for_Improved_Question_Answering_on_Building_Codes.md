# 改进建筑规范问答的大型语言模型微调与检索方法评估

发布时间：2025年05月07日

`RAG` `建筑法规` `问答系统`

> Fine-Tuning Large Language Models and Evaluating Retrieval Methods for Improved Question Answering on Building Codes

# 摘要

> 建筑法规是确保建筑物结构安全、防火和无障碍性的设计与施工标准。这些法规内容繁杂、更新频繁，人工查询耗时费力。主要挑战包括处理海量文本、解析专业术语以及跨章节识别相关条款。为解决这一问题，我们提出构建一个基于建筑法规的问答（QA）系统。在众多QA构建方法中，检索增强生成（RAG）表现尤为突出。RAG由检索器和语言模型两部分组成。本研究旨在为建筑法规领域寻找合适的检索器，并通过微调技术优化语言模型的生成能力。我们基于加拿大国家建筑法规（NBCC）对多种检索方法进行了全面评估，并利用NBCC数据集研究了领域特定微调对语言模型的影响。通过对比不同检索器的性能，以及分析预训练与微调模型的表现，我们验证了微调技术在提升语言模型领域适应性方面的有效性。实验结果显示，Elasticsearch在检索器中表现最为 robust。研究还表明，通过对NBCC特定数据集进行微调，语言模型能够更好地生成上下文相关的回答。当结合Elasticsearch等强大检索器提供的上下文信息时，这种性能提升可显著优化RAG系统，使其更高效地应对NBCC的复杂性。

> Building codes are regulations that establish standards for the design, construction, and safety of buildings to ensure structural integrity, fire protection, and accessibility. They are often extensive, complex, and subject to frequent updates, making manual querying challenging and time-consuming. Key difficulties include navigating large volumes of text, interpreting technical language, and identifying relevant clauses across different sections. A potential solution is to build a Question-Answering (QA) system that answers user queries based on building codes. Among the various methods for building a QA system, Retrieval-Augmented Generation (RAG) stands out in performance. RAG consists of two components: a retriever and a language model. This study focuses on identifying a suitable retriever method for building codes and optimizing the generational capability of the language model using fine-tuning techniques. We conducted a detailed evaluation of various retrieval methods by performing the retrieval on the National Building Code of Canada (NBCC) and explored the impact of domain-specific fine-tuning on several language models using the dataset derived from NBCC. Our analysis included a comparative assessment of different retrievers and the performance of both pre-trained and fine-tuned models to determine the efficacy and domain-specific adaptation of language models using fine-tuning on the NBCC dataset. Experimental results showed that Elasticsearch proved to be the most robust retriever among all. The findings also indicate that fine-tuning language models on an NBCC-specific dataset can enhance their ability to generate contextually relevant responses. When combined with context retrieved by a powerful retriever like Elasticsearch, this improvement in LLM performance can optimize the RAG system, enabling it to better navigate the complexities of the NBCC.

[Arxiv](https://arxiv.org/abs/2505.04666)