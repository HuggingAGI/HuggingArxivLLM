# SQL-o1：一种基于自我奖励的启发式动态搜索方法，用于文本到SQL转换

发布时间：2025年02月17日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于Text-to-SQL任务，并提出了一种新的方法SQL-o1来提升模型的推理能力和生成效果。虽然论文中提到了模型扩展性、生成空间有限及连贯性问题，但这些都是在应用层面的改进和优化，属于LLM的应用研究。因此，这篇论文被归类为LLM应用。` `数据库` `数据库管理`

> SQL-o1: A Self-Reward Heuristic Dynamic Search Method for Text-to-SQL

# 摘要

> Text-to-SQL任务旨在将自然语言查询转化为可执行的SQL查询。得益于大型语言模型（LLMs）的应用，该领域取得了显著进展。然而，模型扩展性、生成空间有限及SQL生成中的连贯性问题依然存在。为解决这些问题，我们提出了SQL-o1——一种基于自我奖励的启发式搜索方法，旨在提升LLMs在SQL查询生成中的推理能力。SQL-o1结合蒙特卡洛树搜索（MCTS）进行启发式过程级搜索，并构建了一个Schema-Aware数据集，帮助模型更好地理解数据库模式。在Bird和Spider数据集上的广泛实验表明，SQL-o1在复杂的Bird数据集上将执行准确率提升了10.8%，超越了最新的基线方法，甚至优于基于GPT-4的方法。此外，SQL-o1在少样本学习场景中表现优异，且具有强大的跨模型迁移能力。我们的代码已公开发布：https://github.com/ShuaiLyu0110/SQL-o1。

> The Text-to-SQL(Text2SQL) task aims to convert natural language queries into executable SQL queries. Thanks to the application of large language models (LLMs), significant progress has been made in this field. However, challenges such as model scalability, limited generation space, and coherence issues in SQL generation still persist. To address these issues, we propose SQL-o1, a Self-Reward-based heuristic search method designed to enhance the reasoning ability of LLMs in SQL query generation. SQL-o1 combines Monte Carlo Tree Search (MCTS) for heuristic process-level search and constructs a Schema-Aware dataset to help the model better understand database schemas. Extensive experiments on the Bird and Spider datasets demonstrate that SQL-o1 improves execution accuracy by 10.8\% on the complex Bird dataset compared to the latest baseline methods, even outperforming GPT-4-based approaches. Additionally, SQL-o1 excels in few-shot learning scenarios and shows strong cross-model transferability. Our code is publicly available at:https://github.com/ShuaiLyu0110/SQL-o1.

[Arxiv](https://arxiv.org/abs/2502.11741)