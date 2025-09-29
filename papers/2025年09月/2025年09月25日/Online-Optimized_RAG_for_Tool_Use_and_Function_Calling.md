# 在线优化RAG：面向工具使用与函数调用

发布时间：2025年09月25日

`RAG` `基础理论`

> Online-Optimized RAG for Tool Use and Function Calling

# 摘要

> 在众多应用中，检索增强生成（RAG）通过对用户查询进行嵌入，并将其与预先定义的工具/函数描述匹配，从而驱动工具使用与函数调用。本文针对实际应用中因嵌入模型不完善或描述存在噪声而常出现的嵌入错位问题——这种错位可能导致检索错误和任务失败。我们提出Online-Optimized RAG，这是一种部署时框架，能利用最少反馈（如任务成功与否），通过实时交互持续调整检索嵌入。该框架采用轻量级在线梯度更新，单查询延迟可忽略不计，且无需修改底层大型语言模型（LLM）。其即插即用特性支持单跳与多跳工具使用、动态工具库及【数学公式】检索与重排序。我们还提供了依赖于问题的理论分析，量化了该方法性能与嵌入初始化质量及其他相关量的关系。在各类工具使用和文档检索场景中，Online-Optimized RAG均能持续提升工具选择准确率与最终任务成功率，为构建稳健、自改进的RAG系统提供了简单实用的方案。

> In many applications, retrieval-augmented generation (RAG) drives tool use and function calling by embedding the (user) queries and matching them to pre-specified tool/function descriptions. In this paper, we address an embedding misalignment issue that often arises in practical applications due to imperfect embedding models or noisy descriptions; such misalignment may lead to incorrect retrieval and task failure. We introduce Online-Optimized RAG, a deployment-time framework that continually adapts retrieval embeddings from live interactions using minimal feedback (e.g., task success). Online-Optimized RAG applies lightweight online gradient updates with negligible per-query latency and requires no changes to the underlying LLM. The method is plug-and-play: it supports both single- and multi-hop tool use, dynamic tool inventories, and $K$-retrieval with re-ranking. We provide a problem-dependent theoretical analysis that quantifies how the method's performance depends on the initialization quality of the embeddings and other related quantities. Across diverse tool-use and document-retrieval scenarios, our Online-Optimized RAG consistently improves tool selection accuracy and end-task success, thus providing a simple, practical path to robust, self-improving RAG systems.

[Arxiv](https://arxiv.org/abs/2509.20415)