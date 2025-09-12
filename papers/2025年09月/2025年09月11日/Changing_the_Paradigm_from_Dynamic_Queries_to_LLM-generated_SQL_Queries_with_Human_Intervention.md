# 范式转变：从动态查询到人工干预下的LLM生成SQL查询

发布时间：2025年09月11日

`LLM应用` `医疗健康`

> Changing the Paradigm from Dynamic Queries to LLM-generated SQL Queries with Human Intervention

# 摘要

> 我们提议将大型语言模型（LLMs）用作医疗可视化系统的交互层。在医疗等领域，用户需处理高维、编码化且异构的数据集，而LLM生成的查询能让专业医疗用户用自然语言表达复杂的分析意图。这些意图随后会转化为可编辑、可执行的查询，取代传统可视化系统中基于滑块、复选框和下拉菜单的动态查询界面。这种交互模型能减少视觉杂乱，无需用户记忆字段名称或系统代码，支持流畅探索，不过其缺点是无法展示所有过滤条件。我们还会按需重新引入动态查询，从而更好地支持交互式探索。我们认为，医疗用户虽经培训了解可能的过滤选项，但难以记住属性名称和代码值的具体细节。我们在ParcoursVis中展示了这一范式——这是我们开发的可扩展患者护理路径可视化系统，灵感源自EventFlow，由法国国家健康数据系统（全球最大的健康数据存储库之一）提供支持。

> We propose leveraging Large Language Models (LLMs) as an interaction layer for medical visualization systems. In domains like healthcare, where users must navigate high-dimensional, coded, and heterogeneous datasets, LLM-generated queries enable expert medical users to express complex analytical intents in natural language. These intents are then translated into editable and executable queries, replacing the dynamic query interfaces used by traditional visualization systems built around sliders, check boxes, and drop-downs. This interaction model reduces visual clutter and eliminates the need for users to memorize field names or system codes, supporting fluid exploration, with the drawback of not exposing all the filtering criteria. We also reintroduce dynamic queries on demand to better support interactive exploration. We posit that medical users are trained to know the possible filtering options but challenged to remember the details of the attribute names and code values. We demonstrate this paradigm in ParcoursVis, our scalable EventFlow-inspired patient care pathway visualization system powered by the French National Health Data System, one of the largest health data repositories in the world.

[Arxiv](https://arxiv.org/abs/2509.09461)