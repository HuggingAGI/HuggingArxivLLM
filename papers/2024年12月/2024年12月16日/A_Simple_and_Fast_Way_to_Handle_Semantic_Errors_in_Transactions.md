# 交易语义错误的简单快速处理方案

发布时间：2024年12月16日

`LLM应用

理由：这篇论文主要讨论了如何将LLM生成的事务整合到数据库系统中，并提出了一个中间件框架来确保数据库的一致性。这涉及到LLM在实际系统中的应用，特别是如何处理LLM生成的事务并确保系统的可靠性和一致性。因此，这篇论文属于LLM应用类别。` `数据库` `系统设计`

> A Simple and Fast Way to Handle Semantic Errors in Transactions

# 摘要

> 许多计算机系统正在重新设计，以整合LLM驱动的智能体，实现自然语言输入和更灵活的操作。本文专注于处理由LLMs生成的数据库事务。由于LLMs生成的事务可能包含语义错误，系统需将其视为长期事务，允许人工审查并在必要时从数据库历史中删除。删除操作必须确保数据库的一致性（ACID原则中的“C”）始终得到维护。
我们提出了一种基于不变性满足（I-Confluence）的新型中间件框架，通过识别和协调长期事务与新事务之间的依赖关系来确保一致性。该中间件通过缓冲可疑或补偿事务来管理协调状态。利用TPC-C基准测试，我们评估了事务生成频率、用户审查和不变性完整性对系统性能的影响。对于系统研究人员，本研究建立了LLMs与数据库系统之间的交互范式，提供了一种“撤销”机制，既能处理错误操作，又能保证数据库一致性。对于系统工程师，本文提供了一种中间件设计，只需少量修改即可将可移除的LLM生成事务集成到现有系统中。

> Many computer systems are now being redesigned to incorporate LLM-powered agents, enabling natural language input and more flexible operations. This paper focuses on handling database transactions created by large language models (LLMs). Transactions generated by LLMs may include semantic errors, requiring systems to treat them as long-lived. This allows for human review and, if the transaction is incorrect, removal from the database history. Any removal action must ensure the database's consistency (the "C" in ACID principles) is maintained throughout the process.
  We propose a novel middleware framework based on Invariant Satisfaction (I-Confluence), which ensures consistency by identifying and coordinating dependencies between long-lived transactions and new transactions. This middleware buffers suspicious or compensating transactions to manage coordination states. Using the TPC-C benchmark, we evaluate how transaction generation frequency, user reviews, and invariant completeness impact system performance. For system researchers, this study establishes an interactive paradigm between LLMs and database systems, providing an "undoing" mechanism for handling incorrect operations while guaranteeing database consistency. For system engineers, this paper offers a middleware design that integrates removable LLM-generated transactions into existing systems with minimal modifications.

[Arxiv](https://arxiv.org/abs/2412.12493)