# 基于Python的着色Petri网建模与分析工具CPN-Py

发布时间：2025年03月27日

`其他` `流程挖掘` `数据分析`

> CPN-Py: A Python-Based Tool for Modeling and Analyzing Colored Petri Nets

# 摘要

> 着色Petri网（CPN）是一种成熟的建模方法，适用于令牌携带数据的网络建模。尽管CPN Tools和CPN IDE等工具在CPN仿真方面表现出色，但它们通常与现代数据科学生态脱节。与此同时，Python已成为流程挖掘、机器学习和数据分析领域的主流语言。本文介绍的CPN-Py是一个Python库，它不仅忠实保留了CPN的核心概念（如颜色集、定时令牌、守护逻辑和层级结构），还实现了与Python环境的无缝集成。本文将探讨CPN-Py的设计理念，展示其与PM4Py工具包（包括随机重放、过程发现和决策挖掘功能）的协同作用，并通过实例说明该工具如何支持状态空间分析和层级CPN建模。此外，我们还将介绍CPN-Py如何与大语言模型结合，使其能够通过特定的JSON格式生成或优化CPN模型。

> Colored Petri Nets (CPNs) are an established formalism for modeling processes where tokens carry data. Although tools like CPN Tools and CPN IDE excel at CPN-based simulation, they are often separate from modern data science ecosystems. Meanwhile, Python has become the de facto language for process mining, machine learning, and data analytics. In this paper, we introduce CPN-Py, a Python library that faithfully preserves the core concepts of Colored Petri Nets -- including color sets, timed tokens, guard logic, and hierarchical structures -- while providing seamless integration with the Python environment. We discuss its design, highlight its synergy with PM4Py (including stochastic replay, process discovery, and decision mining functionalities), and illustrate how the tool supports state space analysis and hierarchical CPNs. We also outline how CPN-Py accommodates large language models, which can generate or refine CPN models through a dedicated JSON-based format.

[Arxiv](https://arxiv.org/abs/2506.12238)