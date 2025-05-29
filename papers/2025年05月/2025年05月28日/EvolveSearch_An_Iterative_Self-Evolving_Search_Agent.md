# EvolveSearch: 迭代自我进化搜索代理

发布时间：2025年05月28日

`Agent` `问答系统`

> EvolveSearch: An Iterative Self-Evolving Search Agent

# 摘要

> 大型语言模型 (LLMs) 的飞速发展通过整合搜索引擎和网络浏览器等工具，彻底改变了智能体信息检索能力的格局。然而，目前主流的提升 LLM 网络搜索能力的方法面临重大挑战：监督微调在开放搜索领域难以生成数据，而强化学习 (RL) 收敛速度过快，限制了数据利用效率。为了解决这些问题，我们提出了 EvolveSearch，这是一个结合监督微调 (SFT) 和强化学习 (RL) 的新型迭代自我进化框架，旨在无需任何外部人工标注推理数据的情况下增强智能体网络搜索能力。在七个跨领域多跳问答 (MHQA) 基准测试上的广泛实验表明，EvolveSearch 能够持续提升迭代性能，最终在七个基准测试中平均超越当前最优方法 4.7%的表现，为开放网络搜索领域的自我进化智能体能力开辟了新的可能性。

> The rapid advancement of large language models (LLMs) has transformed the landscape of agentic information seeking capabilities through the integration of tools such as search engines and web browsers. However, current mainstream approaches for enabling LLM web search proficiency face significant challenges: supervised fine-tuning struggles with data production in open-search domains, while RL converges quickly, limiting their data utilization efficiency. To address these issues, we propose EvolveSearch, a novel iterative self-evolution framework that combines SFT and RL to enhance agentic web search capabilities without any external human-annotated reasoning data. Extensive experiments on seven multi-hop question-answering (MHQA) benchmarks demonstrate that EvolveSearch consistently improves performance across iterations, ultimately achieving an average improvement of 4.7\% over the current state-of-the-art across seven benchmarks, opening the door to self-evolution agentic capabilities in open web search domains.

[Arxiv](https://arxiv.org/abs/2505.22501)