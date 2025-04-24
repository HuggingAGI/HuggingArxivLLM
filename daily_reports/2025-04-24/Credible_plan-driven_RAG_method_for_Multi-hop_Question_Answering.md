# 可信计划驱动的RAG方法在多跳问答中的应用
发布时间：2025年04月23日

`RAG`
> Credible plan-driven RAG method for Multi-hop Question Answering
>
> 多跳问答（QA）对检索增强生成（RAG）方法提出了重大挑战，需要将复杂查询结构化分解为逻辑推理路径，并生成可靠中间结果。然而，现有RAG方法中常见的推理路径偏差或中间结果错误，可能在整个推理过程中传播和积累，降低对复杂查询的回答准确性。为应对这一挑战，我们提出了计划-执行-复审（PAR RAG）框架，该框架分为规划、执行和复审三个关键阶段，旨在通过减少误差传播，提供一种可解释的增量推理范式，实现准确可靠的多跳问答。PAR RAG最初采用自顶向下的问题分解策略，从整体视角制定包含多个可执行步骤的全面计划。这种方法避免了传统RAG方法中常见的局部最优陷阱，确保整个推理路径的准确性。随后，PAR RAG引入了基于多粒度验证的计划执行机制。通过结合粗粒度相似信息和细粒度相关数据，该框架全面检查和调整中间结果，在有效控制误差传播和放大的同时，确保过程准确。在多跳问答数据集上的实验结果表明，PAR RAG框架在关键指标（包括准确匹配率和F1值）上显著优于现有最先进的方法。
>
> https://arxiv.org/abs/2504.16787

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.16787](https://arxiv.org/abs/2504.16787)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)