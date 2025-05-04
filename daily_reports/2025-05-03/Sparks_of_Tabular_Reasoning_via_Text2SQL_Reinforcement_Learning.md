# # 通过 Text2SQL 强化学习探索表格推理的火花
通过 Text2SQL 强化学习，我们发现了一些关于表格推理的初步火花。
发布时间：2025年04月23日

`图表问答`
> Sparks of Tabular Reasoning via Text2SQL Reinforcement Learning
>
> 我们重新定义了文本到SQL任务为一种教学路径，帮助大型语言模型（LLMs）更好地处理表格数据，而不仅仅是生成查询。为此，我们提出了一种两阶段框架，利用SQL监督来培养模型在表格推理方面的能力。首先，我们从真实的SQL查询中提取详细的思维链（CoT）轨迹，为模型提供逐步、逐句的指导，教会它如何遍历、筛选和聚合表格字段。其次，我们引入了一种名为组相对策略优化（GRPO）的强化学习目标，通过鼓励模型超越特定任务的语法并实现跨数据集迁移，将SQL执行准确性与可推广的推理能力联系起来。实验结果显示，我们的方法不仅在标准文本到SQL基准测试中表现出色，还在需要复杂推理的数据集（如BIRD和CRT-QA）上取得了显著提升，证明了其更强的泛化和可解释性。值得注意的是，经过文本到SQL任务训练的蒸馏量化LLaMA模型准确率提升了20%，而Qwen模型的准确率也提高了5%。这些结果表明，SQL不仅可以作为目标形式，还可以作为学习结构化数据上稳健、可迁移推理的有效工具。
>
> https://arxiv.org/abs/2505.00016

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2505.00016](https://arxiv.org/abs/2505.00016)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)