# DeepShop: 深度研究购物代理的基准测试

发布时间：2025年06月03日

`Agent` `电子商务`

> DeepShop: A Benchmark for Deep Research Shopping Agents

# 摘要

> 网络购物代理在跨平台购物自动化方面潜力巨大。然而，现有评估基准往往过于简单，无法反映真实购物场景的复杂性，例如“查找 iPhone 15”这样的简单查询。真实购物场景涉及多维产品属性、搜索过滤器和用户偏好，远比简单查询复杂。为解决这一问题，我们推出了 DeepShop，一个专为评估网络代理在复杂且现实的在线购物环境中表现而设计的基准。DeepShop包含三大核心组件：首先，通过从真实用户查询出发，生成覆盖五大热门购物领域的多样化查询；其次，将这些查询复杂化，考虑产品属性、搜索过滤器和排序偏好，并根据复杂度分为简单、中等和困难三个级别；最后，采用细粒度与整体评估框架，从产品属性、搜索过滤器和排序偏好等多维度评估代理性能，并通过整体评估报告成功率。我们对检索增强生成（RAG）方法、网络代理和深度研究系统进行了全面评估，发现RAG在复杂查询上表现不佳，因其缺乏网络交互能力，而其他方法则在过滤器和排序偏好上面临挑战，导致整体成功率偏低。通过跨类别和基于复杂度的评估以及错误分析，我们为深度研究购物代理的发展提供了有力支持。

> Web agents for online shopping have shown great promise in automating user interactions across e-commerce platforms. Benchmarks for assessing such agents do not reflect the complexity of real-world shopping scenarios, as they often consist of overly simple queries with deterministic paths, such as "Find iPhone 15." Real shopping scenarios are inherently more layered, involving multi-dimensional product attributes, search filters, and user-specific sorting preferences. To address this gap, we introduce DeepShop, a benchmark designed to evaluate web agents in complex and realistic online shopping environments. DeepShop comprises three key components. (1) Query diversity evolution: Starting from real user queries, we generate diverse queries across five popular online shopping domains. (2) Query complexity evolution: We further evolve these queries to increase complexity, considering product attributes, search filters, and sorting preferences, and classify them into three levels: easy, medium, and hard, based on the number of evolutions. (3) Fine-grained and holistic evaluation: We propose an automated evaluation framework that assesses agent performance in terms of fine-grained aspects (product attributes, search filters, and sorting preferences) and reports the overall success rate through holistic evaluation. We conduct a systematic evaluation of retrieval-augmented generation (RAG) methods, web agents, and deep research systems. Results show that RAG struggles with complex queries due to its lack of web interaction, while other methods face significant challenges with filters and sorting preferences, leading to low overall success rates. We also perform cross-category, complexity-based evaluations and error analyses to support the advancement of deep research shopping agents.

[Arxiv](https://arxiv.org/abs/2506.02839)