# Chat3GPP: 开源3GPP文档检索增强生成框架

发布时间：2025年01月20日

`RAG

理由：这篇论文提出了一个名为Chat3GPP的框架，该框架结合了检索增强生成（RAG）技术，专门用于处理3GPP规范。RAG是一种结合了信息检索和生成模型的技术，旨在通过检索相关信息来增强生成模型的输出。论文中提到的分块策略、混合检索和高效索引方法都是RAG框架的关键组成部分。因此，这篇论文应被分类为RAG。`

> Chat3GPP: An Open-Source Retrieval-Augmented Generation Framework for 3GPP Documents

# 摘要

> 3GPP文档是全球电信领域的关键标准，但其内容庞大、复杂且更新频繁，给电信领域的工程师和研究人员带来了巨大挑战。尽管大型语言模型（LLMs）在自然语言处理任务中表现出色，但其通用性限制了它们在电信等特定领域的应用。为此，我们提出了Chat3GPP，一个专为3GPP规范设计的开源检索增强生成（RAG）框架。通过结合分块策略、混合检索和高效索引方法，Chat3GPP能够高效检索相关信息并生成准确的用户查询响应，无需领域特定微调，既灵活又可扩展，具有适应3GPP以外其他技术标准的潜力。我们在两个电信数据集上评估了Chat3GPP，展示了其相比现有方法的优越性能，并验证了其在协议生成和代码自动化等下游任务中的潜力。

> The 3rd Generation Partnership Project (3GPP) documents is key standards in global telecommunications, while posing significant challenges for engineers and researchers in the telecommunications field due to the large volume and complexity of their contents as well as the frequent updates. Large language models (LLMs) have shown promise in natural language processing tasks, but their general-purpose nature limits their effectiveness in specific domains like telecommunications. To address this, we propose Chat3GPP, an open-source retrieval-augmented generation (RAG) framework tailored for 3GPP specifications. By combining chunking strategies, hybrid retrieval and efficient indexing methods, Chat3GPP can efficiently retrieve relevant information and generate accurate responses to user queries without requiring domain-specific fine-tuning, which is both flexible and scalable, offering significant potential for adapting to other technical standards beyond 3GPP. We evaluate Chat3GPP on two telecom-specific datasets and demonstrate its superior performance compared to existing methods, showcasing its potential for downstream tasks like protocol generation and code automation.

[Arxiv](https://arxiv.org/abs/2501.13954)