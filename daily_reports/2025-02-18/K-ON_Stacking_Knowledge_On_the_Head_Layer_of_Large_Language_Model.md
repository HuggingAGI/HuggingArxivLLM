# K-ON：在大型语言模型顶层实现知识叠加
发布时间：2025年02月10日


> K-ON: Stacking Knowledge On the Head Layer of Large Language Model
>
> 近期，大型语言模型（LLMs）的突破显著提升了多种自然语言处理（NLP）任务的表现。通常，LLMs通过预测下一个词元进行训练，这与许多NLP任务高度契合。然而，在知识图谱（KG）场景中，实体是基本单位，识别一个实体至少需要几个词元。这导致了KG与自然语言之间的粒度不匹配。为了解决这一问题，我们提出了K-ON，它巧妙地将KG知识融入LLM，通过多头层预测下一步k步。K-ON不仅可以一步生成实体级别的结果，还支持基于实体的对比损失，这是KG表征学习中最强大的工具。实验结果表明，K-ON在性能上超越了现有的结合文本甚至其他模态的方法。
>
> https://arxiv.org/abs/2502.06257

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.06257](https://arxiv.org/abs/2502.06257)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)