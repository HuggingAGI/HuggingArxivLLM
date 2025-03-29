# 通过合成模拟实现在线内容监管策略的可扩展性评估
发布时间：2025年03月13日


> Scalable Evaluation of Online Moderation Strategies via Synthetic Simulations
>
> 尽管在线内容 moderation 的重要性日益凸显，但目前还没有大规模研究对各种 moderation 策略的有效性进行评估。这主要是因为缺乏合适的测试数据集，以及难以让人类讨论者、 moderator 和评估人员参与多次实验。本文中，我们提出了一种通过仅使用大型语言模型 (LLMs) 进行合成实验的方法，以初步绕过在涉及在线 moderation 的实验中需要人类参与的需求。我们评估了六种 LLM moderation 配置，包括两种目前在实际中使用的 moderation 策略（为人类 moderator 制定的在线 moderation 指南，以及实际中的促进策略），两种基线策略（从 LLM 对齐工作中提取的指南，以及带有最少提示的 LLM moderation），一种完全没有 moderator 的基线，以及我们自己提出的一种基于强化学习 (RL) 方法的 moderation 策略。我们发现，我们自己的 moderation 策略在性能上显著优于现有的 moderation 指南，同时也优于开箱即用的 LLM moderation。我们还发现，经过较少指令微调的小型 LLM 可以生成比大型模型更加多样化的讨论。为了运行这些实验，我们创建并开源了一个高效、专为模拟数百次讨论设计的 Python 框架，名为 "SynDisco"，它使用 LLM 用户代理和 moderator 进行模拟。此外，我们还发布了虚拟 moderation 数据集 (VMD)，这是一个由三种开源 LLM 生成并标注的大规模讨论数据集，并附带了对数据集的探索性分析。
>
> https://arxiv.org/abs/2503.16505

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.16505](https://arxiv.org/abs/2503.16505)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)