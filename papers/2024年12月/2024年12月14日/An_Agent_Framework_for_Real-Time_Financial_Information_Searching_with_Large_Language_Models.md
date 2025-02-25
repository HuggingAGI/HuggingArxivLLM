# 智能体框架实现实时金融信息搜索，基于大型语言模型

发布时间：2024年12月14日

`Agent` `金融决策支持`

> An Agent Framework for Real-Time Financial Information Searching with Large Language Models

# 摘要

> 金融决策需要处理海量实时信息，同时理解这些信息之间复杂的时间关系。传统搜索引擎在实时信息获取方面表现出色，但往往难以理解复杂的用户意图和上下文细微差别。相比之下，大型语言模型（LLMs）展现了强大的推理和交互能力，但在缺乏实时数据的情况下可能生成不可靠的结果。尽管近期已有尝试将LLMs与搜索功能结合，但它们仍面临以下挑战：（1）受限于专业金融数据的访问；（2）静态查询结构无法适应动态市场环境；（3）生成结果时缺乏足够的时间感知能力。

为了解决这些问题，我们提出了FinSearch——一个专为金融应用设计的基于智能体的搜索框架，能够接入包括市场、股票和新闻在内的多种金融数据源。创新性地，FinSearch由四个核心组件构成：（1）基于LLM的多步骤搜索预规划器，通过图表示将用户查询分解为结构化的子查询，并映射到特定数据源；（2）搜索执行器，配备基于LLM的自适应查询重写器，在执行每个子查询的同时，根据中间搜索结果动态优化后续节点的子查询；（3）时间加权机制，基于从用户查询中推断出的时间上下文，优先处理相关信息；（4）基于LLM的结果生成器，将搜索结果整合成连贯且上下文相关的输出。

为了评估FinSearch的表现，我们构建了FinSearchBench-24，一个涵盖股票市场、利率变动、货币政策和行业发展等领域的基准测试集，包含1500个四选一问题，时间范围从2024年6月至10月。


> Financial decision-making requires processing vast amounts of real-time information while understanding their complex temporal relationships. While traditional search engines excel at providing real-time information access, they often struggle to comprehend sophisticated user intentions and contextual nuances. Conversely, Large Language Models (LLMs) demonstrate reasoning and interaction capabilities but may generate unreliable outputs without access to current data. While recent attempts have been made to combine LLMs with search capabilities, they suffer from (1) restricted access to specialized financial data, (2) static query structures that cannot adapt to dynamic market conditions, and (3) insufficient temporal awareness in result generation. To address these challenges, we present FinSearch, a novel agent-based search framework specifically designed for financial applications that interface with diverse financial data sources including market, stock, and news data. Innovatively, FinSearch comprises four components: (1) an LLM-based multi-step search pre-planner that decomposes user queries into structured sub-queries mapped to specific data sources through a graph representation; (2) a search executor with an LLM-based adaptive query rewriter that executes the searching of each sub-query while dynamically refining the sub-queries in its subsequent node based on intermediate search results; (3) a temporal weighting mechanism that prioritizes information relevance based on the deduced time context from the user's query; (4) an LLM-based response generator that synthesizes results into coherent, contextually appropriate outputs. To evaluate FinSearch, we construct FinSearchBench-24, a benchmark of 1,500 four-choice questions across the stock market, rate changes, monetary policy, and industry developments spanning from June to October 2024.

[Arxiv](https://arxiv.org/abs/2502.15684)