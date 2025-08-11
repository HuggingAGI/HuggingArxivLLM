# Chain-of-Alpha：释放大语言模型在量化交易中的Alpha挖掘强大潜力

发布时间：2025年08月08日

`LLM应用` `量化交易`

> Chain-of-Alpha: Unleashing the Power of Large Language Models for Alpha Mining in Quantitative Trading

# 摘要

> Alpha因子挖掘是量化交易中的核心任务，旨在发现超越系统性风险的可解释信号。传统方法依赖手动设计或启发式搜索，而近期研究借助大型语言模型（LLMs）实现自动化因子发现。然而，现有基于LLM的方法在自动化、通用性和效率上仍有提升空间。本文提出Chain-of-Alpha，一个新颖、简单、高效且有效的LLM框架，用于全自动公式化Alpha因子挖掘。该方法采用双链架构：因子生成链和因子优化链，仅利用市场数据迭代生成、评估和优化候选因子，同时结合回测反馈和优化知识。双链协同工作，无需人工干预即可高效发现高质量Alpha因子，并具备良好扩展性。在真实A股基准数据上的实验表明，Chain-of-Alpha在多维度表现优于现有方法，为LLM驱动的量化研究提供了有前景的方向。


> Alpha factor mining is a fundamental task in quantitative trading, aimed at discovering interpretable signals that can predict asset returns beyond systematic market risk. While traditional methods rely on manual formula design or heuristic search with machine learning, recent advances have leveraged Large Language Models (LLMs) for automated factor discovery. However, existing LLM-based alpha mining approaches remain limited in terms of automation, generality, and efficiency. In this paper, we propose Chain-of-Alpha, a novel, simple, yet effective and efficient LLM-based framework for fully automated formulaic alpha mining. Our method features a dual-chain architecture, consisting of a Factor Generation Chain and a Factor Optimization Chain, which iteratively generate, evaluate, and refine candidate alpha factors using only market data, while leveraging backtest feedback and prior optimization knowledge. The two chains work synergistically to enable high-quality alpha discovery without human intervention and offer strong scalability. Extensive experiments on real-world A-share benchmarks demonstrate that Chain-of-Alpha outperforms existing baselines across multiple metrics, presenting a promising direction for LLM-driven quantitative research.

[Arxiv](https://arxiv.org/abs/2508.06312)