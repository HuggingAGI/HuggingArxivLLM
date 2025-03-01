# SQL-o1：一种基于自我奖励的启发式动态搜索方法，用于文本到SQL转换
发布时间：2025年02月17日

`代码编写`
> SQL-o1: A Self-Reward Heuristic Dynamic Search Method for Text-to-SQL
>
> Text-to-SQL任务旨在将自然语言查询转化为可执行的SQL查询。得益于大型语言模型（LLMs）的应用，该领域取得了显著进展。然而，模型扩展性、生成空间有限及SQL生成中的连贯性问题依然存在。为解决这些问题，我们提出了SQL-o1——一种基于自我奖励的启发式搜索方法，旨在提升LLMs在SQL查询生成中的推理能力。SQL-o1结合蒙特卡洛树搜索（MCTS）进行启发式过程级搜索，并构建了一个Schema-Aware数据集，帮助模型更好地理解数据库模式。在Bird和Spider数据集上的广泛实验表明，SQL-o1在复杂的Bird数据集上将执行准确率提升了10.8%，超越了最新的基线方法，甚至优于基于GPT-4的方法。此外，SQL-o1在少样本学习场景中表现优异，且具有强大的跨模型迁移能力。我们的代码已公开发布：https://github.com/ShuaiLyu0110/SQL-o1。
>
> https://arxiv.org/abs/2502.11741

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.11741](https://arxiv.org/abs/2502.11741)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)