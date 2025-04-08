# ELT-Bench: 首个端到端评测基准，专为评估AI代理在ELT流水线中的表现而设计

发布时间：2025年04月07日

`LLM应用` `数据工程` `数据仓库`

> ELT-Bench: An End-to-End Benchmark for Evaluating AI Agents on ELT Pipelines

# 摘要

> 随着云数据仓库的普及，越来越多的从业者开始采用抽取-加载-转换（ELT）管道。然而，这些管道的设计往往需要大量的手动工作来确保正确性。近年来，基于AI的方法在数据任务中表现出色，例如文本到SQL，为减少ELT管道开发中的手动工作提供了新机遇。遗憾的是，现有的数据工程基准仅针对孤立任务进行评估，如使用数据工具或编写数据转换查询，这在评估生成端到端ELT管道的AI代理方面存在明显不足。
为解决这一问题，我们推出了ELT-Bench，这是一个端到端基准测试，旨在全面评估AI代理构建ELT管道的能力。ELT-Bench包含100个管道，涉及835个源表和203个数据模型，覆盖多个领域。通过模拟整合多种数据源和使用流行数据工具的真实场景，ELT-Bench能够全面评估AI代理在处理复杂数据工程工作流方面的表现。AI代理需与数据库和数据工具交互、编写代码和SQL查询，并协调管道的每一步骤。我们采用六种主流大型语言模型（LLMs），在ELT-Bench上对Spider-Agent和SWE-Agent两种代表性代码代理框架进行了评估。其中表现最佳的Spider-Agent Claude-3.7-Sonnet在扩展思考模式下，仅能正确生成3.9%的数据模型，每条管道的平均成本为4.30美元，涉及89.3个步骤。实验结果不仅展示了ELT-Bench的挑战性，也凸显了开发更先进AI代理以减少ELT工作流中手动操作的迫切需求。我们的代码和数据已开源，可在https://github.com/uiuc-kang-lab/ETL.git获取。

> Practitioners are increasingly turning to Extract-Load-Transform (ELT) pipelines with the widespread adoption of cloud data warehouses. However, designing these pipelines often involves significant manual work to ensure correctness. Recent advances in AI-based methods, which have shown strong capabilities in data tasks, such as text-to-SQL, present an opportunity to alleviate manual efforts in developing ELT pipelines. Unfortunately, current benchmarks in data engineering only evaluate isolated tasks, such as using data tools and writing data transformation queries, leaving a significant gap in evaluating AI agents for generating end-to-end ELT pipelines.
  To fill this gap, we introduce ELT-Bench, an end-to-end benchmark designed to assess the capabilities of AI agents to build ELT pipelines. ELT-Bench consists of 100 pipelines, including 835 source tables and 203 data models across various domains. By simulating realistic scenarios involving the integration of diverse data sources and the use of popular data tools, ELT-Bench evaluates AI agents' abilities in handling complex data engineering workflows. AI agents must interact with databases and data tools, write code and SQL queries, and orchestrate every pipeline stage. We evaluate two representative code agent frameworks, Spider-Agent and SWE-Agent, using six popular Large Language Models (LLMs) on ELT-Bench. The highest-performing agent, Spider-Agent Claude-3.7-Sonnet with extended thinking, correctly generates only 3.9% of data models, with an average cost of $4.30 and 89.3 steps per pipeline. Our experimental results demonstrate the challenges of ELT-Bench and highlight the need for a more advanced AI agent to reduce manual effort in ELT workflows. Our code and data are available at https://github.com/uiuc-kang-lab/ETL.git.

[Arxiv](https://arxiv.org/abs/2504.04808)