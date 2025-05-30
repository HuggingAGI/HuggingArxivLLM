# 设计与测试一个支持公共交通数据辅助决策的代理聊天机器人

发布时间：2025年05月28日

`LLM应用` `公共交通` `聊天机器人`

> Design and testing of an agent chatbot supporting decision making with public transport data

# 摘要

> 评估公共交通服务质量需要分析大量关于计划和实际行程的数据，以及列出每项服务需满足的质量约束的文件。通过SQL查询对这些数据集进行分析，组织和可视化数据对大多数用户来说可能相当复杂。本文介绍了一款聊天机器人，它提供了一个用户友好的工具，用于与这些数据集交互并支持决策制定。该聊天机器人基于代理架构，通过允许核心大型语言模型（LLM）与一系列工具交互来扩展其功能，这些工具可以执行多种任务，如执行SQL查询、绘制数据图表以及根据行程及其停靠点的坐标生成地图。本文还探讨了此类生成式AI项目的主要开放问题之一：收集数据以衡量系统的性能。我们的聊天机器人经过了广泛测试，采用了一个工作流程，该流程针对多个问题，记录了生成的查询、检索到的数据以及自然语言响应。这些问题是从一组基础示例中提取的，然后用数据库中的实际数据进行补充。这一流程生成了一个用于评估聊天机器人性能的数据集，特别是其答案的一致性和生成查询的准确性。

> Assessing the quality of public transportation services requires the analysis of large quantities of data on the scheduled and actual trips and documents listing the quality constraints each service needs to meet. Interrogating such datasets with SQL queries, organizing and visualizing the data can be quite complex for most users. This paper presents a chatbot offering a user-friendly tool to interact with these datasets and support decision making. It is based on an agent architecture, which expands the capabilities of the core Large Language Model (LLM) by allowing it to interact with a series of tools that can execute several tasks, like performing SQL queries, plotting data and creating maps from the coordinates of a trip and its stops. This paper also tackles one of the main open problems of such Generative AI projects: collecting data to measure the system's performance. Our chatbot has been extensively tested with a workflow that asks several questions and stores the generated query, the retrieved data and the natural language response for each of them. Such questions are drawn from a set of base examples which are then completed with actual data from the database. This procedure yields a dataset for the evaluation of the chatbot's performance, especially the consistency of its answers and the correctness of the generated queries.

[Arxiv](https://arxiv.org/abs/2505.22698)