# 基于差分隐私的 RAG

发布时间：2024年12月26日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术在LLM中的应用，特别是如何通过差分隐私令牌生成来解决RAG中的隐私挑战。因此，它属于RAG分类。` `隐私保护`

> RAG with Differential Privacy

# 摘要

> 检索增强生成（RAG）已成为为LLM提供最新相关上下文的主流技术，有效降低幻觉风险，并在知识库快速变化的环境中提升响应质量。然而，将外部文档融入生成过程带来了显著的隐私挑战。一旦文档被加入提示，无法确保响应不会意外泄露敏感数据，进而引发隐私泄露和伦理问题。本文提出了一种适用于从个人数据中提取通用知识的实用解决方案，并证明差分隐私令牌生成是实现私有RAG的可行途径。

> Retrieval-Augmented Generation (RAG) has emerged as the dominant technique to provide *Large Language Models* (LLM) with fresh and relevant context, mitigating the risk of hallucinations and improving the overall quality of responses in environments with large and fast moving knowledge bases. However, the integration of external documents into the generation process raises significant privacy concerns. Indeed, when added to a prompt, it is not possible to guarantee a response will not inadvertently expose confidential data, leading to potential breaches of privacy and ethical dilemmas. This paper explores a practical solution to this problem suitable to general knowledge extraction from personal data. It shows *differentially private token generation* is a viable approach to private RAG.

[Arxiv](https://arxiv.org/abs/2412.19291)