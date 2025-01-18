# 借助大型语言模型作为知识驱动代理，实现可靠的逆合成规划

发布时间：2025年01月15日

`Agent

理由：这篇论文描述了一个集成大型语言模型（LLMs）和知识图谱（KGs）的代理系统，用于自动化材料化学中的合成路径识别和推荐。该系统具备文献检索、反应数据提取、数据库查询、逆合成路径树构建、文献扩展及最佳路径推荐等功能，符合“Agent”分类中关于智能代理系统的定义。` `材料化学` `高分子科学`

> Leveraging Large Language Models as Knowledge-Driven Agents for Reliable Retrosynthesis Planning

# 摘要

> # 摘要
在材料化学中，识别可靠的合成路径是一项复杂任务，尤其在高分子科学中，大分子的命名复杂且不唯一。为此，我们提出了一种集成大型语言模型（LLMs）和知识图谱（KGs）的代理系统。该系统利用LLMs强大的化学物质名称提取与识别能力，将数据存储在结构化知识图谱中，实现了文献检索、反应数据提取、数据库查询、逆合成路径树构建、文献扩展及最佳路径推荐的全自动化。我们开发的多分支反应路径搜索（MBRPS）算法，特别关注多分支路径，帮助LLMs克服多分支推理的不足。这是首次尝试开发基于LLMs的全自动大分子逆合成规划代理。应用于聚酰亚胺合成，该方法构建了包含数百条路径的逆合成路径树，并推荐了已知和新路径的优化方案，展示了其有效性和广泛应用潜力。

> Identifying reliable synthesis pathways in materials chemistry is a complex task, particularly in polymer science, due to the intricate and often non-unique nomenclature of macromolecules. To address this challenge, we propose an agent system that integrates large language models (LLMs) and knowledge graphs (KGs). By leveraging LLMs' powerful capabilities for extracting and recognizing chemical substance names, and storing the extracted data in a structured knowledge graph, our system fully automates the retrieval of relevant literatures, extraction of reaction data, database querying, construction of retrosynthetic pathway trees, further expansion through the retrieval of additional literature and recommendation of optimal reaction pathways. A novel Multi-branched Reaction Pathway Search (MBRPS) algorithm enables the exploration of all pathways, with a particular focus on multi-branched ones, helping LLMs overcome weak reasoning in multi-branched paths. This work represents the first attempt to develop a fully automated retrosynthesis planning agent tailored specially for macromolecules powered by LLMs. Applied to polyimide synthesis, our new approach constructs a retrosynthetic pathway tree with hundreds of pathways and recommends optimized routes, including both known and novel pathways, demonstrating its effectiveness and potential for broader applications.

[Arxiv](https://arxiv.org/abs/2501.08897)