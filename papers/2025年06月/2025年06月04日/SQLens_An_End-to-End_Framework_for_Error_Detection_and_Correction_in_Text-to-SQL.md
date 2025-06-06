# SQLens：全流程文本到SQL纠错框架

发布时间：2025年06月04日

`LLM应用` `数据库`

> SQLens: An End-to-End Framework for Error Detection and Correction in Text-to-SQL

# 摘要

> Text-to-SQL系统通过将自然语言问题转化为SQL查询，让非技术人员能够轻松处理结构化数据。尽管大型语言模型（LLMs）在Text-to-SQL任务中表现优异，但它们生成的SQL查询虽语法正确，却常存在语义错误，且其可靠性难以捉摸。为此，我们提出了SQLens，一个端到端的框架，专注于检测并修正LLM生成SQL中的语义错误。SQLens巧妙地整合了来自数据库和LLM的错误信号，精准识别SQL子句中的潜在语义问题，并以此为依据指导查询的修正。在两个公开基准测试中的实证结果表明，SQLens在错误检测的F1分数上超越了最佳的LLM自评估方法25.78%，同时将现成Text-to-SQL系统的执行准确率提升了20%。

> Text-to-SQL systems translate natural language (NL) questions into SQL queries, enabling non-technical users to interact with structured data. While large language models (LLMs) have shown promising results on the text-to-SQL task, they often produce semantically incorrect yet syntactically valid queries, with limited insight into their reliability. We propose SQLens, an end-to-end framework for fine-grained detection and correction of semantic errors in LLM-generated SQL. SQLens integrates error signals from both the underlying database and the LLM to identify potential semantic errors within SQL clauses. It further leverages these signals to guide query correction. Empirical results on two public benchmarks show that SQLens outperforms the best LLM-based self-evaluation method by 25.78% in F1 for error detection, and improves execution accuracy of out-of-the-box text-to-SQL systems by up to 20%.

[Arxiv](https://arxiv.org/abs/2506.04494)