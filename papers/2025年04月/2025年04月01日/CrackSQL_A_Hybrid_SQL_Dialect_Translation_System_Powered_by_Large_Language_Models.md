# CrackSQL: 基于大型语言模型的混合 SQL 方言翻译系统

发布时间：2025年04月01日

`LLM应用` `数据库` `数据集成`

> CrackSQL: A Hybrid SQL Dialect Translation System Powered by Large Language Models

# 摘要

> 方言翻译在实现异构数据库系统间的无缝交互中发挥着关键作用。然而，不同方言（如PostgreSQL到MySQL）之间的SQL查询翻译仍面临挑战，主要源于句法差异和语义微妙变化。现有方法，包括手动重写、基于规则的系统和基于大语言模型（LLM）的技术，往往存在高维护成本（如需编写自定义规则）或结果不可靠（如LLM生成不存在的函数）的问题，尤其在处理复杂查询时表现不佳。本次演示中，我们推出CrackSQL——首个结合规则与LLM方法的混合SQL方言翻译系统，旨在突破这些限制。CrackSQL借助LLMs的适应性，大幅减少人工干预，同时通过基于功能的查询处理，将长复杂SQL分割处理，从而提升翻译准确性。为增强系统鲁棒性，CrackSQL采用了新型跨方言语法嵌入模型，实现精准语法对齐，并引入自适应局部到全局翻译策略，有效解决相互依赖的查询操作。CrackSQL支持三种翻译模式，并提供多样化的部署和访问选项，包括Web控制台界面、PyPI软件包以及命令行工具，助力其在各类现实场景中的广泛应用。

> Dialect translation plays a key role in enabling seamless interaction across heterogeneous database systems. However, translating SQL queries between different dialects (e.g., from PostgreSQL to MySQL) remains a challenging task due to syntactic discrepancies and subtle semantic variations. Existing approaches including manual rewriting, rule-based systems, and large language model (LLM)-based techniques often involve high maintenance effort (e.g., crafting custom translation rules) or produce unreliable results (e.g., LLM generates non-existent functions), especially when handling complex queries. In this demonstration, we present CrackSQL, the first hybrid SQL dialect translation system that combines rule and LLM-based methods to overcome these limitations. CrackSQL leverages the adaptability of LLMs to minimize manual intervention, while enhancing translation accuracy by segmenting lengthy complex SQL via functionality-based query processing. To further improve robustness, it incorporates a novel cross-dialect syntax embedding model for precise syntax alignment, as well as an adaptive local-to-global translation strategy that effectively resolves interdependent query operations. CrackSQL supports three translation modes and offers multiple deployment and access options including a web console interface, a PyPI package, and a command-line prompt, facilitating adoption across a variety of real-world use cases

[Arxiv](https://arxiv.org/abs/2504.00882)