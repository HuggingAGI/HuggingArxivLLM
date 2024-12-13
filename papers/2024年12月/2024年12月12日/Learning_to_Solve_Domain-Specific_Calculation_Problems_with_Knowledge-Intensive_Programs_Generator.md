# 学会运用知识密集型程序生成器来解决特定领域的计算难题

发布时间：2024年12月12日

`LLM应用` `计算问题`

> Learning to Solve Domain-Specific Calculation Problems with Knowledge-Intensive Programs Generator

# 摘要

> 领域大型语言模型（LLMs）基于通用LLMs为特定领域任务而开发。但某些特定领域任务仍需专业知识来提升专业能力。本文中，我们对知识密集型计算问题展开了研究。我们发现，当涉及复杂的特定领域规则和知识文档时，数学问题对于LLMs颇具挑战，而非简单的术语表述。为此，我们提出了一个更有效地利用知识密集型程序生成器（名为KIPG）来解决特定领域计算问题的流程。它依据特定领域文档生成知识密集型程序。对于每个查询，先提取关键变量，再用程序计算依赖于领域知识的结果。通过迭代偏好对齐，代码生成器学会增强与领域知识的逻辑一致性。以法律领域为例，我们进行了实验以证明该流程的有效性，并对模块进行了广泛分析。我们还发现，代码生成器无需针对新知识进行训练，就能适用于其他领域。

> Domain Large Language Models (LLMs) are developed for domain-specific tasks based on general LLMs. But it still requires professional knowledge to facilitate the expertise for some domain-specific tasks. In this paper, we investigate into knowledge-intensive calculation problems. We find that the math problems to be challenging for LLMs, when involving complex domain-specific rules and knowledge documents, rather than simple formulations of terminologies. Therefore, we propose a pipeline to solve the domain-specific calculation problems with Knowledge-Intensive Programs Generator more effectively, named as KIPG. It generates knowledge-intensive programs according to the domain-specific documents. For each query, key variables are extracted, then outcomes which are dependent on domain knowledge are calculated with the programs. By iterative preference alignment, the code generator learns to improve the logic consistency with the domain knowledge. Taking legal domain as an example, we have conducted experiments to prove the effectiveness of our pipeline, and extensive analysis on the modules. We also find that the code generator is also adaptable to other domains, without training on the new knowledge.

[Arxiv](https://arxiv.org/abs/2412.09280)