# SQLBarber：借助大型语言模型打造定制化且真实的SQL工作负载系统

发布时间：2025年07月08日

`LLM应用` `数据库` `数据管理`

> SQLBarber: A System Leveraging Large Language Models to Generate Customized and Realistic SQL Workloads

# 摘要

> 数据库研究与开发中，生成大量SQL查询用于基准测试是常见需求。然而，获取真实SQL查询因隐私问题充满挑战，现有生成方法在定制化和满足现实约束上也存在局限。我们提出了SQLBarber——一个基于大型语言模型（LLMs）的系统，专注于生成定制化且现实的SQL工作负载。

SQLBarber具有三大优势：(i) 用户无需手动编写SQL模板，只需通过自然语言规范即可灵活定义模板约束，(ii) 系统能高效扩展，生成大量与用户定义的成本分布（如基数和执行计划成本）相匹配的查询，(iii) 利用Amazon Redshift和Snowflake的执行统计信息，推导出反映真实世界查询特性的SQL模板规范和成本分布。

SQLBarber的核心功能包括：(i) 声明式接口，让生成定制化SQL模板变得轻松，(ii) LLM驱动的流水线，配备自我修正模块，可基于查询成本对SQL模板进行分析、优化和筛选，(iii) 贝叶斯优化器，用于高效探索不同谓词值，并识别满足目标成本分布的查询集合。

我们基于真实统计数据，构建并开源了十个难度和目标成本分布各不相同的基准测试。实验结果表明，SQLBarber是唯一能生成定制化SQL模板的系统。与现有方法相比，它将查询生成时间减少了1到3个数量级，同时显著提升了与目标成本分布的对齐度。

> Database research and development often require a large number of SQL queries for benchmarking purposes. However, acquiring real-world SQL queries is challenging due to privacy concerns, and existing SQL generation methods are limited in customization and in satisfying realistic constraints. To address this issue, we present SQLBarber, a system based on Large Language Models (LLMs) to generate customized and realistic SQL workloads. SQLBarber (i) eliminates the need for users to manually craft SQL templates in advance, while providing the flexibility to accept natural language specifications to constrain SQL templates, (ii) scales efficiently to generate large volumes of queries matching any user-defined cost distribution (e.g., cardinality and execution plan cost), and (iii) uses execution statistics from Amazon Redshift and Snowflake to derive SQL template specifications and query cost distributions that reflect real-world query characteristics. SQLBarber introduces (i) a declarative interface for users to effortlessly generate customized SQL templates, (ii) an LLM-powered pipeline augmented with a self-correction module that profiles, refines, and prunes SQL templates based on query costs, and (iii) a Bayesian Optimizer to efficiently explore different predicate values and identify a set of queries that satisfy the target cost distribution. We construct and open-source ten benchmarks of varying difficulty levels and target query cost distributions based on real-world statistics from Snowflake and Amazon Redshift. Extensive experiments on these benchmarks show that SQLBarber is the only system that can generate customized SQL templates. It reduces query generation time by one to three orders of magnitude, and significantly improves alignment with the target cost distribution, compared with existing methods.

[Arxiv](https://arxiv.org/abs/2507.06192)