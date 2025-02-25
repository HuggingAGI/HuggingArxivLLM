# Alpha-SQL：通过蒙特卡洛树搜索实现零样本文本到SQL转换
发布时间：2025年02月24日


> Alpha-SQL: Zero-Shot Text-to-SQL using Monte Carlo Tree Search
>
> 文本到SQL技术让自然语言与数据库交互成为现实，在各行各业中发挥着关键作用。随着更强大的大型语言模型（LLMs）每隔几个月就涌现，微调成本高昂且耗时费力。于是，我们转向零样本文本到SQL，利用LLMs内置的知识和推理能力，无需额外微调，这不仅充满潜力，更具挑战性。为应对这一挑战，我们推出了Alpha-SQL，它采用蒙特卡洛树搜索（MCTS）框架，根据部分SQL状态逐步构建查询。通过将LLM作为动作模型，Alpha-SQL在搜索过程中动态生成构建动作，精准导向更优的SQL查询。同时，它还借助自我监督的奖励函数评估候选查询质量，确保生成的查询既准确又高效。实验数据显示，Alpha-SQL在BIRD开发集上表现卓越，使用未经微调的开源32B LLM，执行准确率达到69.7%。相比基于GPT-4o的最佳零样本方法，Alpha-SQL在BIRD开发集上高出2.5%。
>
> https://arxiv.org/abs/2502.17248

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.17248](https://arxiv.org/abs/2502.17248)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)