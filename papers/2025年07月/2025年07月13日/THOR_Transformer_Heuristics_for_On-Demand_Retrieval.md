# THOR：基于Transformer的启发式按需检索

发布时间：2025年07月13日

`LLM应用` `企业应用`

> THOR: Transformer Heuristics for On-Demand Retrieval

# 摘要

> 我们推出由eSapiens精心设计并实现的THOR（按需检索的Transformer启发式方法）模块——一款安全且可扩展的智能引擎，它能将自然语言问题转化为经过验证的只读SQL分析，服务于企业级数据库。Text-to-SQL模块采用创新的解耦式编排/执行架构：监督代理负责智能路由查询，Schema Retrieval动态注入表和列的元数据，SQL生成代理则负责生成受只读护栏保护的单语句SELECT查询。

系统内置的自修正与评分循环能够敏锐捕捉空结果、执行错误或低质量输出，并自动触发多达五次由LLM驱动的智能重生成尝试。最后，结果解释代理会将分析结果转化为简洁易懂的洞察，并将原始数据行传递给洞察与智能引擎进行可视化或预测分析。

经过在财务、销售和运营等多个场景下的严格测试，THOR模块展现了卓越的即席查询能力和自动化周期性报告功能。通过内置模式感知、容错执行和合规护栏，THOR模块让非技术人员也能以零SQL复杂度和企业级安全性轻松访问实时数据。


> We introduce the THOR (Transformer Heuristics for On-Demand Retrieval) Module, designed and implemented by eSapiens, a secure, scalable engine that transforms natural-language questions into verified, read-only SQL analytics for enterprise databases. The Text-to-SQL module follows a decoupled orchestration/execution architecture: a Supervisor Agent routes queries, Schema Retrieval dynamically injects table and column metadata, and a SQL Generation Agent emits single-statement SELECT queries protected by a read-only guardrail. An integrated Self-Correction & Rating loop captures empty results, execution errors, or low-quality outputs and triggers up to five LLM-driven regeneration attempts. Finally, a Result Interpretation Agent produces concise, human-readable insights and hands raw rows to the Insight & Intelligence engine for visualization or forecasting.
  Smoke tests across finance, sales, and operations scenarios demonstrate reliable ad-hoc querying and automated periodic reporting. By embedding schema awareness, fault-tolerant execution, and compliance guardrails, the THOR Module empowers non-technical users to access live data with zero-SQL simplicity and enterprise-grade safety.

[Arxiv](https://arxiv.org/abs/2507.09592)