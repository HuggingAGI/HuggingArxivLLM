# # 利用仓库感知知识图谱提升代码仓库修复效果

发布时间：2025年03月27日

`LLM应用` `软件工程`

> Enhancing Repository-Level Software Repair via Repository-Aware Knowledge Graphs

# 摘要

> 在仓库级别的软件修复中，弥合问题描述与代码补丁之间的语义鸿沟是一项重要挑战。当前基于大型语言模型（LLMs）的方法虽已取得一定进展，但仍面临语义模糊、结构上下文理解有限及推理能力不足等问题。为解决这些局限，我们提出了KGCompass，其中包含两大创新：（1）一种新型的仓库感知知识图谱（KG），能够精准关联仓库工件（问题和拉取请求）与代码实体（文件、类和函数），从而将搜索空间缩小到仅20个最相关函数，并提供准确的bug位置和上下文信息；（2）一种基于路径的修复机制，通过追踪知识图谱挖掘的实体路径，为LLMs补充相关上下文信息，从而生成精确的补丁及其解释。实验结果表明，在SWE-Bench-Lite基准测试中，KGCompass实现了开源方法中最高的修复性能（45.67%）和函数级别定位准确度（51.33%），每次修复仅需0.20美元。分析发现，在成功定位的bug中，有69.7%需要通过知识图谱进行多跳遍历，否则LLM-based方法难以准确定位bug。KGCompass构建的知识图谱具有语言无关性，并可进行增量更新，使其成为适用于真实开发环境的实用解决方案。

> Repository-level software repair faces challenges in bridging semantic gaps between issue descriptions and code patches. Existing approaches, which mostly depend on large language models (LLMs), suffer from semantic ambiguities, limited structural context understanding, and insufficient reasoning capability. To address these limitations, we propose KGCompass with two innovations: (1) a novel repository-aware knowledge graph (KG) that accurately links repository artifacts (issues and pull requests) and codebase entities (files, classes, and functions), allowing us to effectively narrow down the vast search space to only 20 most relevant functions with accurate candidate bug locations and contextual information, and (2) a path-guided repair mechanism that leverages KG-mined entity path, tracing through which allows us to augment LLMs with relevant contextual information to generate precise patches along with their explanations. Experimental results in the SWE-Bench-Lite demonstrate that KGCompass achieves state-of-the-art repair performance (45.67%) and function-level localization accuracy (51.33%) across open-source approaches, costing only $0.20 per repair. Our analysis reveals that among successfully localized bugs, 69.7% require multi-hop traversals through the knowledge graph, without which LLM-based approaches struggle to accurately locate bugs. The knowledge graph built in KGCompass is language agnostic and can be incrementally updated, making it a practical solution for real-world development environments.

[Arxiv](https://arxiv.org/abs/2503.21710)