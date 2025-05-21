# RAR: 为增强型拒绝设定知识触发器

发布时间：2025年05月19日

`RAG` `内容安全`

> RAR: Setting Knowledge Tripwires for Retrieval Augmented Rejection

# 摘要

> 大型语言模型（LLMs）的内容审核依然是一个重大挑战，需要灵活且适应性强的解决方案，以快速应对新兴威胁。本文介绍了一种名为检索增强拒绝（RAR）的新方法，该方法利用检索增强生成（RAG）架构，在无需模型重新训练的情况下，动态拒绝不安全的用户查询。通过在向量数据库中战略性地插入并标记恶意文档，系统可以在检索到这些文档时识别并拒绝有害请求。我们的初步结果显示，RAR在性能上与Claude 3.5 Sonnet等LLMs的内置审核功能相当，同时提供了更高的灵活性和实时定制能力，这是及时应对关键漏洞的基本特征。这种方法无需对现有RAG系统进行架构更改，仅需添加专门设计的文档以及基于检索结果的简单拒绝机制。

> Content moderation for large language models (LLMs) remains a significant challenge, requiring flexible and adaptable solutions that can quickly respond to emerging threats. This paper introduces Retrieval Augmented Rejection (RAR), a novel approach that leverages a retrieval-augmented generation (RAG) architecture to dynamically reject unsafe user queries without model retraining. By strategically inserting and marking malicious documents into the vector database, the system can identify and reject harmful requests when these documents are retrieved. Our preliminary results show that RAR achieves comparable performance to embedded moderation in LLMs like Claude 3.5 Sonnet, while offering superior flexibility and real-time customization capabilities, a fundamental feature to timely address critical vulnerabilities. This approach introduces no architectural changes to existing RAG systems, requiring only the addition of specially crafted documents and a simple rejection mechanism based on retrieval results.

[Arxiv](https://arxiv.org/abs/2505.13581)