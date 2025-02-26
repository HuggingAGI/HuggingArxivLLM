# FACT-AUDIT：一种自适应多智能体框架，用于大型语言模型的动态事实核查评估

发布时间：2025年02月25日

`LLM应用` `信息科学` `人工智能`

> FACT-AUDIT: An Adaptive Multi-Agent Framework for Dynamic Fact-Checking Evaluation of Large Language Models

# 摘要

> 大型语言模型（LLMs）推动了事实核查研究的显著进步。然而，现有自动化事实核查评估方法存在局限：它们依赖静态数据集和分类指标，无法自动评估论据生成，也未能揭示LLMs在事实核查中的细微局限。为解决这一问题，我们提出FACT-AUDIT——一个基于智能体的自适应动态框架，用于全面评估LLMs的事实核查能力。通过重要性采样原则和多智能体协作，FACT-AUDIT能够生成自适应且可扩展的数据集，执行迭代模型评估，并根据模型特定响应动态更新评估结果。该框架的独特之处在于结合了论据生成和判决预测，从而对LLMs的事实推理能力进行全面且动态的审计，深入探究其可信度。通过大量实验验证，FACT-AUDIT不仅能够有效区分不同先进LLMs的表现，还为模型中心事实核查分析提供了宝贵见解，清晰揭示了各类模型在事实核查任务中的优势与局限。

> Large Language Models (LLMs) have significantly advanced the fact-checking studies. However, existing automated fact-checking evaluation methods rely on static datasets and classification metrics, which fail to automatically evaluate the justification production and uncover the nuanced limitations of LLMs in fact-checking. In this work, we introduce FACT-AUDIT, an agent-driven framework that adaptively and dynamically assesses LLMs' fact-checking capabilities. Leveraging importance sampling principles and multi-agent collaboration, FACT-AUDIT generates adaptive and scalable datasets, performs iterative model-centric evaluations, and updates assessments based on model-specific responses. By incorporating justification production alongside verdict prediction, this framework provides a comprehensive and evolving audit of LLMs' factual reasoning capabilities, to investigate their trustworthiness. Extensive experiments demonstrate that FACT-AUDIT effectively differentiates among state-of-the-art LLMs, providing valuable insights into model strengths and limitations in model-centric fact-checking analysis.

[Arxiv](https://arxiv.org/abs/2502.17924)