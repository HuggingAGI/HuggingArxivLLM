# 利用检索增强语言模型进行自动数据库配置调试

发布时间：2024年12月10日

`RAG` `数据库管理`

> Automatic Database Configuration Debugging using Retrieval-Augmented Language Models

# 摘要

> 数据库管理系统（DBMS）的配置调试，比如诊断配置不佳的 DBMS 旋钮并给出故障排除建议，对优化 DBMS 性能极为关键。但配置调试过程繁杂，有时甚至颇具难度，即便对于在 DBMS 配置方面经验丰富、对 DBMS 内部（如 MySQL 或 Oracle）有深入了解的资深数据库管理员（DBA）来说也是如此。为应对这一难题，我们提出了 Andromeda 框架，它借助大型语言模型（LLMs）实现 DBMS 配置的自动调试。Andromeda 可替代 DBA，回答有关 DBMS 配置的各类自然语言（NL）问题，并生成诊断建议以解决这些问题。然而，直接用这些专业问题提示 LLMs 可能会得到过于笼统且往往不能令人满意的答案。为此，我们提出了一种检索增强生成（RAG）策略，能有效地从多个来源为问题提供匹配的特定领域上下文，这些来源包括相关历史问题、故障排除手册和 DBMS 遥测数据，显著提升了配置调试的性能。为支持 RAG 策略，我们开发了处理异构文档的文档检索机制，并设计了有效的遥测分析方法。在真实世界的 DBMS 配置调试数据集上开展的大量实验表明，Andromeda 明显优于现有解决方案。

> Database management system (DBMS) configuration debugging, e.g., diagnosing poorly configured DBMS knobs and generating troubleshooting recommendations, is crucial in optimizing DBMS performance. However, the configuration debugging process is tedious and, sometimes challenging, even for seasoned database administrators (DBAs) with sufficient experience in DBMS configurations and good understandings of the DBMS internals (e.g., MySQL or Oracle). To address this difficulty, we propose Andromeda, a framework that utilizes large language models (LLMs) to enable automatic DBMS configuration debugging. Andromeda serves as a natural surrogate of DBAs to answer a wide range of natural language (NL) questions on DBMS configuration issues, and to generate diagnostic suggestions to fix these issues. Nevertheless, directly prompting LLMs with these professional questions may result in overly generic and often unsatisfying answers. To this end, we propose a retrieval-augmented generation (RAG) strategy that effectively provides matched domain-specific contexts for the question from multiple sources. They come from related historical questions, troubleshooting manuals and DBMS telemetries, which significantly improve the performance of configuration debugging. To support the RAG strategy, we develop a document retrieval mechanism addressing heterogeneous documents and design an effective method for telemetry analysis. Extensive experiments on real-world DBMS configuration debugging datasets show that Andromeda significantly outperforms existing solutions.

[Arxiv](https://arxiv.org/abs/2412.07548)