# RAG无时差：检索增强生成流水线的交互调试

发布时间：2025年04月18日

`RAG` `人工智能` `工具开发`

> RAG Without the Lag: Interactive Debugging for Retrieval-Augmented Generation Pipelines

# 摘要

> 检索增强生成（RAG）管道已成为构建能够访问外部领域特定知识的人工智能助手的事实上的标准方法。在处理用户查询时，RAG 管道通常首先从外部来源检索相关信息，然后调用增强过这些信息的大型语言模型（LLM）以生成响应。现代 RAG 管道经常按任意顺序链式连接多个检索和生成组件。然而，开发有效的 RAG 管道颇具挑战性，因为检索和生成组件相互交织，使得难以识别导致最终输出错误的组件。对输出质量影响最大的参数通常需要在每次更改后进行数小时的预处理，导致反馈循环过于缓慢。为了解决这些挑战，我们提出了 RAGGY，这是一个结合了可组合 RAG 原语的 Python 库以及用于实时调试的交互式界面的开发工具。我们贡献了 RAGGY 的设计与实现，通过与 12 名工程师的定性研究获得的专家调试模式的见解，以及对未来 RAG 工具设计的启示，使其更符合开发者的自然工作流程。

> Retrieval-augmented generation (RAG) pipelines have become the de-facto approach for building AI assistants with access to external, domain-specific knowledge. Given a user query, RAG pipelines typically first retrieve (R) relevant information from external sources, before invoking a Large Language Model (LLM), augmented (A) with this information, to generate (G) responses. Modern RAG pipelines frequently chain multiple retrieval and generation components, in any order. However, developing effective RAG pipelines is challenging because retrieval and generation components are intertwined, making it hard to identify which component(s) cause errors in the eventual output. The parameters with the greatest impact on output quality often require hours of pre-processing after each change, creating prohibitively slow feedback cycles. To address these challenges, we present RAGGY, a developer tool that combines a Python library of composable RAG primitives with an interactive interface for real-time debugging. We contribute the design and implementation of RAGGY, insights into expert debugging patterns through a qualitative study with 12 engineers, and design implications for future RAG tools that better align with developers' natural workflows.

[Arxiv](https://arxiv.org/abs/2504.13587)