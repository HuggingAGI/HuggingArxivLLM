# QUITE: 一个超越规则的LLM智能体驱动的查询改写系统

发布时间：2025年06月09日

`LLM应用` `数据库` `查询优化`

> QUITE: A Query Rewrite System Beyond Rules with LLM Agents

# 摘要

> 查询改写将 SQL 查询转换为运行效率更高的语义等价形式。现有方法主要依赖预定义的重写规则，但存在三个关键问题：(1) 难以发现和验证新规则，(2) 固定规则无法推广到新查询模式，(3) 部分重写技术无法表达为固定规则。基于人类专家的强大改写能力与 LLMs 的语义推理能力，我们提出了一种全新的 LLMs 驱动的查询改写方法。然而，LLMs 的幻觉问题可能导致生成不等价或次优查询。为此，我们设计了 QUITE，一个无训练、反馈感知的 LLMs 智能体系统，能够生成性能更优、覆盖更广的查询改写。QUITE 通过 FSM 控制的多智能体框架，结合实时数据库反馈，提升改写能力；通过重写中间件增强优化改写生成；并通过提示注入技术优化改写查询的执行计划。实验表明，QUITE 在改写数量和性能上均超越现有方法，改写效率提升高达 35.8%，覆盖更多复杂查询场景。

> Query rewrite transforms SQL queries into semantically equivalent forms that run more efficiently. Existing approaches mainly rely on predefined rewrite rules, but they handle a limited subset of queries and can cause performance regressions. This limitation stems from three challenges of rule-based query rewrite: (1) it is hard to discover and verify new rules, (2) fixed rewrite rules do not generalize to new query patterns, and (3) some rewrite techniques cannot be expressed as fixed rules. Motivated by the fact that human experts exhibit significantly better rewrite ability but suffer from scalability, and Large Language Models (LLMs) have demonstrated nearly human-level semantic and reasoning abilities, we propose a new approach of using LLMs to rewrite SQL queries beyond rules. Due to the hallucination problems in LLMs, directly applying LLMs often leads to nonequivalent and suboptimal queries. To address this issue, we propose QUITE (query rewrite), a training-free and feedback-aware system based on LLM agents that rewrites SQL queries into semantically equivalent forms with significantly better performance, covering a broader range of query patterns and rewrite strategies compared to rule-based methods. Firstly, we design a multi-agent framework controlled by a finite state machine (FSM) to equip LLMs with the ability to use external tools and enhance the rewrite process with real-time database feedback. Secondly, we develop a rewrite middleware to enhance the ability of LLMs to generate optimized query equivalents. Finally, we employ a novel hint injection technique to improve execution plans for rewritten queries. Extensive experiments show that QUITE reduces query execution time by up to 35.8% over state-of-the-art approaches and produces 24.1% more rewrites than prior methods, covering query cases that earlier systems did not handle.

[Arxiv](https://arxiv.org/abs/2506.07675)