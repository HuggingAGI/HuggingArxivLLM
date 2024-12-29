# 评估并增强适用于具有多种问题类型的多轮文本到 SQL 的大型语言模型（LLMs）

发布时间：2024年12月21日

`LLM应用` `数据库` `会话查询`

> Evaluating and Enhancing LLMs for Multi-turn Text-to-SQL with Multiple Question Types

# 摘要

> 近期大型语言模型（LLMs）的进步显著推进了文本到 SQL 系统的发展。然而，多数基于 LLM 的方法通常只狭隘地关注 SQL 生成，忽视了现实世界会话查询的复杂性。这种疏漏可能致使响应不可靠，特别是对于那些无法直接用 SQL 处理的模糊问题。为了填补这一空缺，我们提出了 MMSQL，这是一个综合测试套件，旨在通过模拟包含不同问题类型和多轮问答交互的真实场景，来评估 LLM 的问题分类和 SQL 生成能力。利用 MMSQL，我们对流行的 LLM 性能进行了评估，涵盖了开源和闭源模型，并找出了在此类场景中影响其性能的关键因素。另外，我们引入了一个基于 LLM 的多智能体框架，它采用专门的智能体来辨别问题类型并确定合适的回答策略。我们的实验表明，这种方式显著提升了模型应对会话动态复杂性的能力，能够有效地处理用户查询的多样性和复杂性。

> Recent advancements in large language models (LLMs) have significantly advanced text-to-SQL systems. However, most LLM-based methods often narrowly focus on SQL generation, neglecting the complexities of real-world conversational queries. This oversight can lead to unreliable responses, particularly for ambiguous questions that cannot be directly addressed with SQL. To bridge this gap, we propose MMSQL, a comprehensive test suite designed to evaluate the question classification and SQL generation capabilities of LLMs by simulating real-world scenarios with diverse question types and multi-turn Q\&A interactions. Using MMSQL, we assessed the performance of popular LLMs, including both open-source and closed-source models, and identified key factors impacting their performance in such scenarios. Moreover, we introduce an LLM-based multi-agent framework that employs specialized agents to identify question types and determine appropriate answering strategies. Our experiments demonstrate that this approach significantly enhances the model's ability to navigate the complexities of conversational dynamics, effectively handling the diverse and complex nature of user queries.

[Arxiv](https://arxiv.org/abs/2412.17867)