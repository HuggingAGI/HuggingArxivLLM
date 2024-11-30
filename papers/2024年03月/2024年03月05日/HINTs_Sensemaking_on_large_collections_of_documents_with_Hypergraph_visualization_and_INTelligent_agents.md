# HINTs 技术利用超图可视化和智能代理，在大规模文档集合中实现高效的意义挖掘和理解。

发布时间：2024年03月05日

`LLM应用`

> HINTs: Sensemaking on large collections of documents with Hypergraph visualization and INTelligent agents

# 摘要

> 面对大量文档的意义构建，是市场研究、法律研究等多个领域的一大挑战。过去的研究通常基于主题或实体角度来探索，然而因模型契合度欠佳，其解释性和可靠性不尽人意。本文提出了名为 HINTs 的可视化分析方案，它创新融合了主题与实体分析法，并将大型语言模型（LLMs）融入其中，不仅用作通用NLP工具，还充当智能助手角色。在数据预处理阶段，我们充分利用LLMs的信息提取能力，将语料库模拟为超图结构，与用户解析语料库时的认知模型相呼应。此超图通过聚合聚类算法按语义关联性和连接相似性进行层级划分。此外，系统界面内置了基于LLM的智能聊天机器人，以助力意义构建过程。为了验证HINTs系统的普适性和高效性，我们展开了跨领域的两个案例研究及对比用户实验，并分享了智能助手在协助意义构建过程中出现的行为模式和挑战的相关见解。尽管智能助手能有效应对意义构建中的诸多难点，但我们发现，由可视化呈现的直观线索对于化解智能助手引入的新问题是不可或缺的。最后，我们探讨了如何深化交互式可视化与LLMs的结合，以更好地服务于语料库分析，同时展望了未来的改进方向。

> Sensemaking on a large collection of documents (corpus) is a challenging task often found in fields such as market research, legal studies, intelligence analysis, political science, computational linguistics, etc. Previous works approach this problem either from a topic- or entity-based perspective, but they lack interpretability and trust due to poor model alignment. In this paper, we present HINTs, a visual analytics approach that combines topic- and entity-based techniques seamlessly and integrates Large Language Models (LLMs) as both a general NLP task solver and an intelligent agent. By leveraging the extraction capability of LLMs in the data preparation stage, we model the corpus as a hypergraph that matches the user's mental model when making sense of the corpus. The constructed hypergraph is hierarchically organized with an agglomerative clustering algorithm by combining semantic and connectivity similarity. The system further integrates an LLM-based intelligent chatbot agent in the interface to facilitate sensemaking. To demonstrate the generalizability and effectiveness of the HINTs system, we present two case studies on different domains and a comparative user study. We report our insights on the behavior patterns and challenges when intelligent agents are used to facilitate sensemaking. We find that while intelligent agents can address many challenges in sensemaking, the visual hints that visualizations provide are necessary to address the new problems brought by intelligent agents. We discuss limitations and future work for combining interactive visualization and LLMs more profoundly to better support corpus analysis.

[Arxiv](https://arxiv.org/abs/2403.02752)