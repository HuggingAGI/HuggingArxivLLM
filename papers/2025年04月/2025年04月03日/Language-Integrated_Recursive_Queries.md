# 语言与递归查询的结合方法

发布时间：2025年04月03日

`其他` `数据库`

> Language-Integrated Recursive Queries

# 摘要

> 在对性能要求严格的工业应用中，包括大规模程序、网络和分布式系统分析，定点计算发挥着关键作用。SQL:1999引入的递归公共表表达式（CTEs）通过WITH RECURSIVE关键词，显著增强了关系型数据库处理定点计算的能力，将计算靠近数据，带来性能提升。然而，递归使得SQL具备图灵完备性，同时也引入了安全性和正确性风险。SQL语义模糊，不同数据库供应商处理方式各异，导致推理递归SQL程序的正确性需依赖孤立的数学属性，而非统一的形式化模型。为应对这些挑战，我们提出了一种演算，从嵌入式递归查询中自动推导数学属性，并根据数据库后端，拒绝可能导致三类错误的查询：数据库错误、不正确结果和非终止。我们开发了TyQL，一个用Scala实现的安全递归语言集成查询工具。通过命名元组和类型级模式匹配，TyQL确保查询的可移植性和安全性，性能与原始SQL相当，且比非递归查询快三个数量级。

> Performance-critical industrial applications, including large-scale program, network, and distributed system analyses, rely on fixed-point computations. The introduction of recursive common table expressions (CTEs) using the WITH RECURSIVE keyword in SQL:1999 extended the ability of relational database systems to handle fixed-point computations, unlocking significant performance advantages by allowing computation to move closer to the data. Yet with recursion, SQL becomes a Turing-complete programming language and, with that, unrecoverable safety and correctness risks. SQL itself lacks a fixed semantics, as the SQL specification is written in natural language, full of ambiguities that database vendors resolve in divergent ways. As a result, reasoning about the correctness of recursive SQL programs must rely on isolated mathematical properties of queries rather than wrestling a unified formal model out of a language with notoriously inconsistent semantics. To address these challenges, we propose a calculus that automatically derives mathematical properties from embedded recursive queries and, depending on the database backend, rejects queries that may lead to the three classes of recursive query errors - database errors, incorrect results, and non-termination. We introduce TyQL, a practical implementation in Scala for safe, recursive language-integrated query. Using Named-Tuples and type-level pattern matching, TyQL ensures query portability and safety, showing no performance penalty compared to raw SQL strings while unlocking a three-orders-of-magnitude speedup over non-recursive SQL queries.

[Arxiv](https://arxiv.org/abs/2504.02443)