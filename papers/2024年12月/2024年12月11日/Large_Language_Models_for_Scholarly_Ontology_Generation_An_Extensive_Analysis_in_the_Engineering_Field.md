# 关于大型语言模型用于学术本体生成：在工程领域的全面分析

发布时间：2024年12月11日

`LLM应用` `科学研究` `智能系统`

> Large Language Models for Scholarly Ontology Generation: An Extensive Analysis in the Engineering Field

# 摘要

> 研究主题的本体论对于构建科学知识意义重大，能助科学家在海量研究中畅行，也是搜索引擎和推荐系统等智能系统的基石。然而，手动创建这些本体论成本高、速度慢，还常导致过时且过于笼统的表述。为此，研究人员一直在探寻让生成这些本体论的过程实现自动化或半自动化的办法。本文对大型语言模型（LLMs）识别不同研究主题间语义关系的能力进行了全面分析，这是开发此类本体论的关键一步。为此，我们基于 IEEE 词库制定了一个黄金标准，用于评估识别成对主题间四种关系（更广泛、更狭窄、相同和其他）的任务。我们的研究评估了十七种大型语言模型的性能，它们在规模、可访问性（开放与专有）和模型类型（完整与量化）方面各异，同时还评估了四种零样本推理策略。有几个模型表现出色，如 Mixtral-8x7B、Dolphin-Mistral-7B 和 Claude 3 Sonnet，F1 分数分别为 0.847、0.920 和 0.967。此外，我们的研究发现，经提示工程优化的较小量化模型，能实现与规模大得多的专有模型相当的性能，且所需计算资源大幅减少。

> Ontologies of research topics are crucial for structuring scientific knowledge, enabling scientists to navigate vast amounts of research, and forming the backbone of intelligent systems such as search engines and recommendation systems. However, manual creation of these ontologies is expensive, slow, and often results in outdated and overly general representations. As a solution, researchers have been investigating ways to automate or semi-automate the process of generating these ontologies. This paper offers a comprehensive analysis of the ability of large language models (LLMs) to identify semantic relationships between different research topics, which is a critical step in the development of such ontologies. To this end, we developed a gold standard based on the IEEE Thesaurus to evaluate the task of identifying four types of relationships between pairs of topics: broader, narrower, same-as, and other. Our study evaluates the performance of seventeen LLMs, which differ in scale, accessibility (open vs. proprietary), and model type (full vs. quantised), while also assessing four zero-shot reasoning strategies. Several models have achieved outstanding results, including Mixtral-8x7B, Dolphin-Mistral-7B, and Claude 3 Sonnet, with F1-scores of 0.847, 0.920, and 0.967, respectively. Furthermore, our findings demonstrate that smaller, quantised models, when optimised through prompt engineering, can deliver performance comparable to much larger proprietary models, while requiring significantly fewer computational resources.

[Arxiv](https://arxiv.org/abs/2412.08258)