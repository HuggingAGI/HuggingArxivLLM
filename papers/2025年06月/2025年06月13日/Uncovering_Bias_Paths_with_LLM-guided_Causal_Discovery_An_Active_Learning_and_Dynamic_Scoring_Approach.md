# 揭示偏见路径：LLM引导的因果发现新方法——基于主动学习与动态评分

发布时间：2025年06月13日

`LLM应用` `因果推理` `机器学习`

> Uncovering Bias Paths with LLM-guided Causal Discovery: An Active Learning and Dynamic Scoring Approach

# 摘要

> 因果发现 (CD) 在解析复杂系统内在机制中扮演关键角色。尽管当前算法能识别虚假关联和潜在混杂因素，但在现实噪声场景下恢复公平性相关路径仍具挑战。大型语言模型 (LLMs) 凭借其丰富的语义知识，为统计因果发现提供了有力补充，特别是在元数据能提供有意义关系提示的领域。

要在机器学习中实现公平性，需理解敏感属性如何因果影响结果，但现有因果发现方法常引入虚假或有偏路径。为此，我们提出一种基于 LLM 的混合因果发现框架，通过主动学习和动态评分扩展广度优先搜索 (BFS) 策略。该框架利用互信息、偏相关和 LLM 置信度的综合评分，对变量对进行优先级排序以进行 LLM 基础的查询，从而显著提升发现效率和鲁棒性。

为评估公平性敏感度，我们基于 UCI 成人数据集构建了一个半合成基准，嵌入领域知识驱动的因果图，并加入噪声、标签损坏和潜在混杂因素。我们重点评估因果发现方法在恢复全局结构和公平性关键路径方面的效能。

实验结果显示，在噪声条件下，包括我们提出的方法在内的 LLM 引导方法在恢复此类路径方面表现优异。我们特别指出动态评分和主动查询最有益的场景，并深入探讨了对现实世界数据集偏差审计的重要启示。


> Causal discovery (CD) plays a pivotal role in understanding the mechanisms underlying complex systems. While recent algorithms can detect spurious associations and latent confounding, many struggle to recover fairness-relevant pathways in realistic, noisy settings. Large Language Models (LLMs), with their access to broad semantic knowledge, offer a promising complement to statistical CD approaches, particularly in domains where metadata provides meaningful relational cues. Ensuring fairness in machine learning requires understanding how sensitive attributes causally influence outcomes, yet CD methods often introduce spurious or biased pathways. We propose a hybrid LLM-based framework for CD that extends a breadth-first search (BFS) strategy with active learning and dynamic scoring. Variable pairs are prioritized for LLM-based querying using a composite score based on mutual information, partial correlation, and LLM confidence, improving discovery efficiency and robustness.
  To evaluate fairness sensitivity, we construct a semi-synthetic benchmark from the UCI Adult dataset, embedding a domain-informed causal graph with injected noise, label corruption, and latent confounding. We assess how well CD methods recover both global structure and fairness-critical paths.
  Our results show that LLM-guided methods, including the proposed method, demonstrate competitive or superior performance in recovering such pathways under noisy conditions. We highlight when dynamic scoring and active querying are most beneficial and discuss implications for bias auditing in real-world datasets.

[Arxiv](https://arxiv.org/abs/2506.12227)