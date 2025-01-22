# 长上下文是否足够？探索LLM扩展上下文在NL2SQL中的应用

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要探讨了如何利用大型语言模型（LLMs）的扩展上下文窗口来提升NL2SQL（自然语言到SQL）任务的性能。研究聚焦于LLM在实际应用中的表现，特别是如何通过提供更多的上下文信息来提高SQL生成的准确性和降低延迟。因此，这篇论文属于LLM应用类别。` `数据库`

> Is Long Context All You Need? Leveraging LLM's Extended Context for NL2SQL

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，尤其是推理能力的提升和上下文窗口的扩展为这些模型的应用开辟了新天地。NL2SQL（自然语言到SQL）的挑战在于自然语言问题的模糊性，而SQL生成需要对复杂数据模式和语义的精确理解。解决这一问题的关键在于提供充分的上下文信息。
本研究探索了谷歌最新LLM（	extit{gemini-1.5-pro}）提供的扩展上下文窗口（即长上下文）在性能和延迟之间的权衡。我们分析了多种上下文信息的影响，包括列示例值、问题和SQL查询对、用户提示、SQL文档和模式。这是首次研究扩展上下文窗口和额外上下文信息如何提升NL2SQL生成的准确性和降低延迟成本。我们发现，长上下文LLMs在处理扩展信息时表现稳健，不会迷失方向。此外，基于谷歌	extit{gemini-pro-1.5}的长上下文NL2SQL管道在BIRD基准测试（开发集）上取得了67.41\%的优异成绩，且无需微调或昂贵的自一致性技术。

> Large Language Models (LLMs) have demonstrated impressive capabilities across a range of natural language processing tasks. In particular, improvements in reasoning abilities and the expansion of context windows have opened new avenues for leveraging these powerful models. NL2SQL is challenging in that the natural language question is inherently ambiguous, while the SQL generation requires a precise understanding of complex data schema and semantics. One approach to this semantic ambiguous problem is to provide more and sufficient contextual information.
  In this work, we explore the performance and the latency trade-offs of the extended context window (a.k.a., long context) offered by Google's state-of-the-art LLM (\textit{gemini-1.5-pro}). We study the impact of various contextual information, including column example values, question and SQL query pairs, user-provided hints, SQL documentation, and schema. To the best of our knowledge, this is the first work to study how the extended context window and extra contextual information can help NL2SQL generation with respect to both accuracy and latency cost. We show that long context LLMs are robust and do not get lost in the extended contextual information. Additionally, our long-context NL2SQL pipeline based on Google's \textit{gemini-pro-1.5} achieve a strong performance with 67.41\% on BIRD benchmark (dev) without finetuning and expensive self-consistency based techniques.

[Arxiv](https://arxiv.org/abs/2501.12372)