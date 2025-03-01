# 智能体框架实现实时金融信息搜索，基于大型语言模型
发布时间：2024年12月14日

`智能金融`
> An Agent Framework for Real-Time Financial Information Searching with Large Language Models
>
> 金融决策需要处理海量实时信息，同时理解这些信息之间复杂的时间关系。传统搜索引擎在实时信息获取方面表现出色，但往往难以理解复杂的用户意图和上下文细微差别。相比之下，大型语言模型（LLMs）展现了强大的推理和交互能力，但在缺乏实时数据的情况下可能生成不可靠的结果。尽管近期已有尝试将LLMs与搜索功能结合，但它们仍面临以下挑战：（1）受限于专业金融数据的访问；（2）静态查询结构无法适应动态市场环境；（3）生成结果时缺乏足够的时间感知能力。

为了解决这些问题，我们提出了FinSearch——一个专为金融应用设计的基于智能体的搜索框架，能够接入包括市场、股票和新闻在内的多种金融数据源。创新性地，FinSearch由四个核心组件构成：（1）基于LLM的多步骤搜索预规划器，通过图表示将用户查询分解为结构化的子查询，并映射到特定数据源；（2）搜索执行器，配备基于LLM的自适应查询重写器，在执行每个子查询的同时，根据中间搜索结果动态优化后续节点的子查询；（3）时间加权机制，基于从用户查询中推断出的时间上下文，优先处理相关信息；（4）基于LLM的结果生成器，将搜索结果整合成连贯且上下文相关的输出。

为了评估FinSearch的表现，我们构建了FinSearchBench-24，一个涵盖股票市场、利率变动、货币政策和行业发展等领域的基准测试集，包含1500个四选一问题，时间范围从2024年6月至10月。
>
> https://arxiv.org/abs/2502.15684

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15684](https://arxiv.org/abs/2502.15684)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)