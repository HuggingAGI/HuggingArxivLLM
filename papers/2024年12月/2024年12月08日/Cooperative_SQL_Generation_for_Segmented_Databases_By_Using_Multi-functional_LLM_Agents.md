# 利用多功能 LLM 代理为分段数据库实现协作式 SQL 生成

发布时间：2024年12月08日

`Agent` `数据库` `SQL 生成`

> Cooperative SQL Generation for Segmented Databases By Using Multi-functional LLM Agents

# 摘要

> Text-to-SQL 任务旨在依据用户的文本问题自动生成 SQL 查询。为解决此问题，我们借助基于大型语言模型（LLM）且分别拥有部分数据库模式的代理之间的信息交互，提出了基于多功能代理（CSMA）的协同 SQL 生成框架。受人类团队协作的启发，CSMA 涵盖三个阶段：1. 与问题相关的模式收集；2. 与问题对应的 SQL 查询生成；3. SQL 查询正确性检查。在第一阶段，代理分析各自的模式并相互交流，以收集与问题相关的模式信息。在第二阶段，代理尝试利用收集到的信息为问题生成相应的 SQL 查询。在第三阶段，代理依据其已知信息检查 SQL 查询是否正确创建。这种基于交互的方式让每个代理中与问题相关的数据库模式部分用于 SQL 生成和检查。在 Spider 和 Bird 基准上的实验表明，CSMA 实现了与最先进水平相当的高性能，同时在这些个体代理中保存私有数据。

> Text-to-SQL task aims to automatically yield SQL queries according to user text questions. To address this problem, we propose a Cooperative SQL Generation framework based on Multi-functional Agents (CSMA) through information interaction among large language model (LLM) based agents who own part of the database schema seperately. Inspired by the collaboration in human teamwork, CSMA consists of three stages: 1) Question-related schema collection, 2) Question-corresponding SQL query generation, and 3) SQL query correctness check. In the first stage, agents analyze their respective schema and communicate with each other to collect the schema information relevant to the question. In the second stage, agents try to generate the corresponding SQL query for the question using the collected information. In the third stage, agents check if the SQL query is created correctly according to their known information. This interaction-based method makes the question-relevant part of database schema from each agent to be used for SQL generation and check. Experiments on the Spider and Bird benckmark demonstrate that CSMA achieves a high performance level comparable to the state-of-the-arts, meanwhile holding the private data in these individual agents.

[Arxiv](https://arxiv.org/abs/2412.05850)