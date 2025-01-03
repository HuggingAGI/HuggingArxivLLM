# 基于LLM的多智能体系统实现自动化加密货币投资组合管理

发布时间：2025年01月01日

`Agent

理由：这篇论文提出了一种可解释、多模态、多代理的加密货币投资框架，强调了多个代理在团队内及跨团队协作中的重要性。论文的核心在于利用多个专业代理来处理复杂的加密货币投资任务，并通过协作机制提升预测准确性。这符合“Agent”分类的定义，即涉及多个智能代理的协作与决策。` `加密货币`

> LLM-Powered Multi-Agent System for Automated Crypto Portfolio Management

# 摘要

> # 摘要
加密货币投资因其历史较短、需整合多模态数据及复杂推理而颇具挑战。尽管深度学习方法已用于应对这些难题，但其黑箱特性引发了信任与可解释性问题。近期，大型语言模型（LLMs）在金融应用中崭露头角，因其能理解多模态数据并生成可解释决策。然而，单个LLM在处理复杂任务（如资产投资）时存在局限，尤其在加密货币投资中，LLMs缺乏特定领域知识。
为此，我们提出了一种可解释、多模态、多代理的加密货币投资框架。该框架利用专业代理在团队内及跨团队协作，处理市值前30的加密货币的数据分析、文献整合及投资决策等任务。专家训练模块通过多模态历史数据和专业文献微调代理，而多代理投资模块则基于实时数据做出投资决策。独特的团队内及团队间协作机制通过调整代理团队的置信度及促进信息共享，提升了预测准确性。2023年11月至2024年9月的实证评估显示，该框架在分类、资产定价、投资组合及可解释性方面均优于单代理模型和市场基准。

> Cryptocurrency investment is inherently difficult due to its shorter history compared to traditional assets, the need to integrate vast amounts of data from various modalities, and the requirement for complex reasoning. While deep learning approaches have been applied to address these challenges, their black-box nature raises concerns about trust and explainability. Recently, large language models (LLMs) have shown promise in financial applications due to their ability to understand multi-modal data and generate explainable decisions. However, single LLM faces limitations in complex, comprehensive tasks such as asset investment. These limitations are even more pronounced in cryptocurrency investment, where LLMs have less domain-specific knowledge in their training corpora.
  To overcome these challenges, we propose an explainable, multi-modal, multi-agent framework for cryptocurrency investment. Our framework uses specialized agents that collaborate within and across teams to handle subtasks such as data analysis, literature integration, and investment decision-making for the top 30 cryptocurrencies by market capitalization. The expert training module fine-tunes agents using multi-modal historical data and professional investment literature, while the multi-agent investment module employs real-time data to make informed cryptocurrency investment decisions. Unique intrateam and interteam collaboration mechanisms enhance prediction accuracy by adjusting final predictions based on confidence levels within agent teams and facilitating information sharing between teams. Empirical evaluation using data from November 2023 to September 2024 demonstrates that our framework outperforms single-agent models and market benchmarks in classification, asset pricing, portfolio, and explainability performance.

[Arxiv](https://arxiv.org/abs/2501.00826)