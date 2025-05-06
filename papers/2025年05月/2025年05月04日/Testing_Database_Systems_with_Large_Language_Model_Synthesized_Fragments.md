# 借助大型语言模型合成的片段测试数据库系统

发布时间：2025年05月04日

`LLM应用` `数据库`

> Testing Database Systems with Large Language Model Synthesized Fragments

# 摘要

> 针对数据库管理系统（DBMSs），研究者们提出了多种自动化测试方法。其中许多方法通过生成等价查询对来识别漏洞，并在成熟且广泛应用的DBMS中发现了数百个漏洞。然而，这些方法大多基于手动编写的SQL生成器，其漏洞检测能力受限于生成器支持的SQL特性范围。为此，我们提出了ShQveL，一种通过利用大型语言模型（LLMs）合成SQL片段来增强现有SQL测试用例生成器的方法。我们的核心思路是系统地将通过与LLMs交互获取的SQL特性整合到生成器中，从而扩大覆盖范围并高效生成测试用例。具体而言，ShQveL采用SQL草稿——包含不完整代码段的SQL语句，由LLMs填充——将生成内容整合到生成器中。我们在5个DBMS上评估了ShQveL，发现了55个独特且先前未知的漏洞，其中50个漏洞在报告后迅速得到修复。


> Various automated testing approaches have been proposed for Database Management Systems (DBMSs). Many such approaches generate pairs of equivalent queries to identify bugs that cause DBMSs to compute incorrect results, and have found hundreds of bugs in mature, widely used DBMSs. Most of these approaches are based on manually written SQL generators; however, their bug-finding capabilities remain constrained by the limited set of SQL features supported by the generators. In this work, we propose ShQveL, an approach that augments existing SQL test-case generators by leveraging Large Language Models (LLMs) to synthesize SQL fragments. Our key idea is to systematically incorporate SQL features gained through automated interactions with LLMs into the SQL generators, increasing the features covered while efficiently generating test cases. Specifically, ShQveL uses SQL sketches -- SQL statements with incomplete code segments that LLMs fill -- to integrate LLM-generated content into the generator. We evaluated ShQveL on 5 DBMSs and discovered 55 unique and previously unknown bugs, 50 of which were promptly fixed after our reports.

[Arxiv](https://arxiv.org/abs/2505.02012)