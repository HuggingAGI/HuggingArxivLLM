# 面向企业数据分析的文本转SQL

发布时间：2025年07月18日

`LLM应用` `知识图谱` `企业级应用`

> Text-to-SQL for Enterprise Data Analytics

# 摘要

> 大型语言模型的引入为Text-to-SQL领域带来了显著进步，但构建企业级解决方案仍具挑战。本文分享了我们构建内部聊天机器人的经验，该机器人帮助领英团队从大型动态数据湖中自助获取数据洞察。我们的方法包含三个核心组件：首先，构建知识图谱，通过索引数据库元数据、历史查询日志、维基百科和代码捕捉最新语义，并利用聚类识别相关表格；其次，开发Text-to-SQL代理，实现上下文检索、查询生成及错误修正；最后，打造交互式聊天机器人，支持数据发现、查询编写和调试，并通过丰富UI元素提升用户体验。目前，该机器人每周服务超过300名用户，专家评审显示其53%的响应在内部基准中正确或接近正确。通过消融实验，我们明确了知识图谱和建模的关键部分，为企业级Text-to-SQL解决方案提供了实用路径。

> The introduction of large language models has brought rapid progress on Text-to-SQL benchmarks, but it is not yet easy to build a working enterprise solution. In this paper, we present insights from building an internal chatbot that enables LinkedIn's product managers, engineers, and operations teams to self-serve data insights from a large, dynamic data lake. Our approach features three components. First, we construct a knowledge graph that captures up-to-date semantics by indexing database metadata, historical query logs, wikis, and code. We apply clustering to identify relevant tables for each team or product area. Second, we build a Text-to-SQL agent that retrieves and ranks context from the knowledge graph, writes a query, and automatically corrects hallucinations and syntax errors. Third, we build an interactive chatbot that supports various user intents, from data discovery to query writing to debugging, and displays responses in rich UI elements to encourage follow-up chats. Our chatbot has over 300 weekly users. Expert review shows that 53% of its responses are correct or close to correct on an internal benchmark set. Through ablation studies, we identify the most important knowledge graph and modeling components, offering a practical path for developing enterprise Text-to-SQL solutions.

[Arxiv](https://arxiv.org/abs/2507.14372)