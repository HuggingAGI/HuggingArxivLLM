# 基于规则与模型的验证器的潜在问题 —— 以数学推理为例

发布时间：2025年05月28日

`Agent` `数学推理` `人工智能`

> Pitfalls of Rule- and Model-based Verifiers -- A Case Study on Mathematical Reasoning

# 摘要

> 可信验证器是可验证奖励强化学习（RLVR）成功的关键，RLVR是DeepSeek-R1等大型推理模型的核心方法。在数学推理等复杂领域，基于规则的验证器已被广泛用于训练强大的推理模型。然而，这些验证器的可靠性和对强化学习训练的影响仍不明确。本研究以数学推理为案例，全面分析了多种验证器在静态评估和强化学习训练中的表现。首先，我们发现现有开源的基于规则验证器常无法识别不同格式的等效答案，导致显著误判率。这一问题严重影响强化学习训练效果，且随着策略模型增强而加剧。随后，我们探讨了基于模型验证器作为解决方案。尽管静态评估显示其验证准确性显著提升，但进一步分析表明其易受“欺骗”，将错误模式误判为正确。这一漏洞在策略模型优化中被利用，导致奖励虚高。我们的研究揭示了两类验证器的独特风险，为开发更强大的强化学习奖励系统提供了重要见解。

> Trustworthy verifiers are essential for the success of reinforcement learning with verifiable reward (RLVR), which is the core methodology behind various large reasoning models such as DeepSeek-R1. In complex domains like mathematical reasoning, rule-based verifiers have been widely adopted in previous works to train strong reasoning models. However, the reliability of these verifiers and their impact on the RL training process remain poorly understood. In this work, we take mathematical reasoning as a case study and conduct a comprehensive analysis of various verifiers in both static evaluation and RL training scenarios. First, we find that current open-source rule-based verifiers often fail to recognize equivalent answers presented in different formats across multiple commonly used mathematical datasets, resulting in non-negligible false negative rates. This limitation adversely affects RL training performance and becomes more pronounced as the policy model gets stronger. Subsequently, we investigate model-based verifiers as a potential solution to address these limitations. While the static evaluation shows that model-based verifiers achieve significantly higher verification accuracy, further analysis and RL training results imply that they are highly susceptible to hacking, where they misclassify certain patterns in responses as correct (i.e., false positives). This vulnerability is exploited during policy model optimization, leading to artificially inflated rewards. Our findings underscore the unique risks inherent to both rule-based and model-based verifiers, aiming to offer valuable insights to develop more robust reward systems in reinforcement learning.

[Arxiv](https://arxiv.org/abs/2505.22203)