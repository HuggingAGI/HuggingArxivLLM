# # 利用当代大语言模型实现安全策略自动化

发布时间：2025年06月05日

`RAG` `网络安全` `知识图谱`

> On Automating Security Policies with Contemporary LLMs

# 摘要

> 面对日益复杂的计算环境和网络威胁，我们需要更强大、更具适应性和自动化的安全解决方案。本文提出了一种基于大型语言模型（LLMs）的创新框架，通过结合上下文学习与检索增强生成（RAG），实现攻击缓解策略的自动化合规。我们的系统能够高效收集和管理工具及API规范，并利用向量数据库进行快速检索。系统架构管道将高级缓解策略分解为具体任务，并将其转化为可执行的API调用。通过公开的STIXv2格式CTI策略和Windows API文档进行的实证评估表明，与传统方法相比，RAG方法在精确率、召回率和F1值方面均实现了显著提升。

> The complexity of modern computing environments and the growing sophistication of cyber threats necessitate a more robust, adaptive, and automated approach to security enforcement. In this paper, we present a framework leveraging large language models (LLMs) for automating attack mitigation policy compliance through an innovative combination of in-context learning and retrieval-augmented generation (RAG). We begin by describing how our system collects and manages both tool and API specifications, storing them in a vector database to enable efficient retrieval of relevant information. We then detail the architectural pipeline that first decomposes high-level mitigation policies into discrete tasks and subsequently translates each task into a set of actionable API calls. Our empirical evaluation, conducted using publicly available CTI policies in STIXv2 format and Windows API documentation, demonstrates significant improvements in precision, recall, and F1-score when employing RAG compared to a non-RAG baseline.

[Arxiv](https://arxiv.org/abs/2506.04838)