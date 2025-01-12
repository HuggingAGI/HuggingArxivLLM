# 基于生成式AI的知识检索

发布时间：2025年01月08日

`RAG

理由：该论文描述了一个基于检索增强生成（RAG）的问答系统，利用中文维基百科和法律库作为检索源，并通过BGE-M3和BGE-reranker进行检索和重新排序，以提升大型语言模型（LLM）的回答能力。该系统通过两阶段评估验证其有效性，并强调了其在增强LLM能力和改进数据隐私方面的贡献。因此，该论文属于RAG（Retrieval-Augmented Generation）类别。`

> Knowledge Retrieval Based on Generative AI

# 摘要

> 本研究开发了一个基于检索增强生成（RAG）的问答系统，利用中文维基百科和法律库作为检索源。系统采用TTQA和TMMLU+作为评估数据集，使用BGE-M3进行密集向量检索以获取高度相关的搜索结果，并通过BGE-reranker根据查询相关性重新排序。最相关的检索结果作为大型语言模型（LLM）的参考知识，提升其回答问题的能力，并构建了一个基于生成式AI的知识检索系统。
    系统的有效性通过两阶段评估进行验证：自动评估和辅助性能评估。自动评估通过比较模型生成的标签与真实答案来计算准确性，衡量在标准化条件下的性能。辅助性能评估则涉及20名无金融背景的参与者回答20个金融相关选择题。参与者首先独立作答，随后在系统提供的参考信息辅助下再次作答，以检验系统是否能在提供协助时提高准确性。
    本研究的主要贡献包括：（1）增强LLM能力：通过整合BGE-M3和BGE-reranker，系统能够检索并重新排序高度相关的结果，减少幻觉，并动态访问授权或公共知识源。（2）改进数据隐私：定制的RAG架构使LLM能够在本地运行，无需将私人数据发送到外部服务器，从而提升数据安全性，减少对商业服务的依赖，降低运营成本，并减轻隐私风险。

> This study develops a question-answering system based on Retrieval-Augmented Generation (RAG) using Chinese Wikipedia and Lawbank as retrieval sources. Using TTQA and TMMLU+ as evaluation datasets, the system employs BGE-M3 for dense vector retrieval to obtain highly relevant search results and BGE-reranker to reorder these results based on query relevance. The most pertinent retrieval outcomes serve as reference knowledge for a Large Language Model (LLM), enhancing its ability to answer questions and establishing a knowledge retrieval system grounded in generative AI.
  The system's effectiveness is assessed through a two-stage evaluation: automatic and assisted performance evaluations. The automatic evaluation calculates accuracy by comparing the model's auto-generated labels with ground truth answers, measuring performance under standardized conditions without human intervention. The assisted performance evaluation involves 20 finance-related multiple-choice questions answered by 20 participants without financial backgrounds. Initially, participants answer independently. Later, they receive system-generated reference information to assist in answering, examining whether the system improves accuracy when assistance is provided.
  The main contributions of this research are: (1) Enhanced LLM Capability: By integrating BGE-M3 and BGE-reranker, the system retrieves and reorders highly relevant results, reduces hallucinations, and dynamically accesses authorized or public knowledge sources. (2) Improved Data Privacy: A customized RAG architecture enables local operation of the LLM, eliminating the need to send private data to external servers. This approach enhances data security, reduces reliance on commercial services, lowers operational costs, and mitigates privacy risks.

[Arxiv](https://arxiv.org/abs/2501.04635)