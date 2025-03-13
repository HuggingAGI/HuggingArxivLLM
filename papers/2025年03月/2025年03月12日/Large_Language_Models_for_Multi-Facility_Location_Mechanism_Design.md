# # 大型语言模型在多设施选址机制设计中的应用探索

发布时间：2025年03月12日

`LLM应用` `运筹学`

> Large Language Models for Multi-Facility Location Mechanism Design

# 摘要

> 设计策略鲁棒的多设施选址机制，以根据代理人的偏好优化社会成本，由于需要大量专业知识和较差的最坏情况保证，一直是极具挑战性的。最近，提出了深度学习模型作为替代方案。然而，这些模型仍然需要一些领域知识和大量超参数调整，同时缺乏可解释性，在实践中，当学习机制的透明度是强制性要求时，这一点至关重要。在本文中，我们提出了一种新颖的方法，名为LLMMech，通过将大型语言模型（LLMs）整合到一个进化框架中，来解决这些限制，从而生成可解释的、无超参数的、经验上策略鲁棒的和接近最优的机制。我们的实验结果，在各种问题设置下进行了评估，其中社会成本在代理之间是任意加权的，且代理人的偏好可能不是均匀分布的，表明LLM生成的机制通常优于现有的手工制作的基线和深度学习模型。此外，这些机制在面对分布外的代理人偏好以及具有更多代理人的更大实例时，表现出令人印象深刻的泛化能力。

> Designing strategyproof mechanisms for multi-facility location that optimize social costs based on agent preferences had been challenging due to the extensive domain knowledge required and poor worst-case guarantees. Recently, deep learning models have been proposed as alternatives. However, these models require some domain knowledge and extensive hyperparameter tuning as well as lacking interpretability, which is crucial in practice when transparency of the learned mechanisms is mandatory. In this paper, we introduce a novel approach, named LLMMech, that addresses these limitations by incorporating large language models (LLMs) into an evolutionary framework for generating interpretable, hyperparameter-free, empirically strategyproof, and nearly optimal mechanisms. Our experimental results, evaluated on various problem settings where the social cost is arbitrarily weighted across agents and the agent preferences may not be uniformly distributed, demonstrate that the LLM-generated mechanisms generally outperform existing handcrafted baselines and deep learning models. Furthermore, the mechanisms exhibit impressive generalizability to out-of-distribution agent preferences and to larger instances with more agents.

[Arxiv](https://arxiv.org/abs/2503.09533)