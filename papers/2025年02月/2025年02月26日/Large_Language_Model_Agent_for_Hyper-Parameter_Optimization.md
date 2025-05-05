# 用于超参数优化的大型语言模型 (LLM) 代理

发布时间：2025年02月26日

`LLM应用` `机器学习` `自动机器学习`

> Large Language Model Agent for Hyper-Parameter Optimization

# 摘要

> 超参数优化在现代机器学习中至关重要，它需要专业知识、多次试验以及大量计算和人力资源支持。尽管自动机器学习（AutoML）领域取得了进展，但在试验效率、设置复杂性和互操作性方面仍面临挑战。为了解决这些问题，我们引入了一种新范式，利用大型语言模型（LLMs）来实现跨多种机器学习任务的超参数优化自动化，该方法名为AgentHPO（即基于LLM代理的超参数优化）。具体而言，AgentHPO自主处理任务信息，进行特定超参数（HPs）的实验，并根据历史试验结果迭代优化。与传统AutoML方法相比，这种类似人类的优化过程显著减少了所需的试验次数，简化了设置流程，同时提高了可解释性和用户信任度。在12个代表性机器学习任务上进行的广泛实证实验表明，AgentHPO不仅在性能上与最佳人工试验相匹配，甚至在很多时候超越了它们，同时还能提供可解释的结果。进一步分析揭示了LLM在优化这些任务时所采用的策略，突显了其在各种场景中的有效性和适应性。

> Hyperparameter optimization is critical in modern machine learning, requiring expert knowledge, numerous trials, and high computational and human resources. Despite the advancements in Automated Machine Learning (AutoML), challenges in terms of trial efficiency, setup complexity, and interoperability still persist. To address these issues, we introduce a novel paradigm leveraging Large Language Models (LLMs) to automate hyperparameter optimization across diverse machine learning tasks, which is named AgentHPO (short for LLM Agent-based Hyperparameter Optimization). Specifically, AgentHPO processes the task information autonomously, conducts experiments with specific hyperparameters (HPs), and iteratively optimizes them based on historical trials. This human-like optimization process largely reduces the number of required trials, simplifies the setup process, and enhances interpretability and user trust, compared to traditional AutoML methods. Extensive empirical experiments conducted on 12 representative machine-learning tasks indicate that AgentHPO not only matches but also often surpasses the best human trials in terms of performance while simultaneously providing explainable results. Further analysis sheds light on the strategies employed by the LLM in optimizing these tasks, highlighting its effectiveness and adaptability in various scenarios.

[Arxiv](https://arxiv.org/abs/2402.01881)