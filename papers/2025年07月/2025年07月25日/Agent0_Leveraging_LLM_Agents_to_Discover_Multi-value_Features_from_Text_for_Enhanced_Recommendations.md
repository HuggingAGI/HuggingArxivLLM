# Agent0: 基于 LLM 代理发现文本中的多值特征，提升推荐效果

发布时间：2025年07月25日

`LLM应用` `推荐系统` `特征工程`

> Agent0: Leveraging LLM Agents to Discover Multi-value Features from Text for Enhanced Recommendations

# 摘要

> 大型语言模型（LLMs）及其代理框架显著推动了自动化信息提取技术的发展，这是现代推荐系统中的关键组成部分。尽管这些多任务框架在代码生成领域得到了广泛应用，但在数据-centric研究中的应用潜力尚未被充分挖掘。本文介绍的Agent0是一个基于LLMs的代理系统，旨在从原始、非结构化的文本中自动化提取信息和构建特征。类别特征对于大规模推荐系统至关重要，但获取成本往往很高。Agent0通过协调一组相互作用的LLM代理，自动识别对后续任务（如模型或AutoML管道）最有价值的文本方面。除了其特征工程能力外，Agent0还提供了一种自动提示工程调优方法，该方法利用来自oracle的动态反馈循环。我们的研究结果表明，这种闭环方法在自动化特征发现方面既实用又有效，而这一过程被认为是当前推荐系统开发中最具挑战性的阶段之一。

> Large language models (LLMs) and their associated agent-based frameworks have significantly advanced automated information extraction, a critical component of modern recommender systems. While these multitask frameworks are widely used in code generation, their application in data-centric research is still largely untapped. This paper presents Agent0, an LLM-driven, agent-based system designed to automate information extraction and feature construction from raw, unstructured text. Categorical features are crucial for large-scale recommender systems but are often expensive to acquire. Agent0 coordinates a group of interacting LLM agents to automatically identify the most valuable text aspects for subsequent tasks (such as models or AutoML pipelines). Beyond its feature engineering capabilities, Agent0 also offers an automated prompt-engineering tuning method that utilizes dynamic feedback loops from an oracle. Our findings demonstrate that this closed-loop methodology is both practical and effective for automated feature discovery, which is recognized as one of the most challenging phases in current recommender system development.

[Arxiv](https://arxiv.org/abs/2507.18993)