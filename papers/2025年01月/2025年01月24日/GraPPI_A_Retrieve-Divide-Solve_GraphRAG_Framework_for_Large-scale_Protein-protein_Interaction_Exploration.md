# GraPPI: 大规模蛋白质-蛋白质相互作用探索的检索-分割-解决 GraphRAG 框架

发布时间：2025年01月24日

`RAG

理由：这篇论文主要讨论了如何将LLMs和RAG框架整合到药物发现的工作流程中，特别是通过提出一个基于大规模知识图谱的RAG框架（GraPPI）来解决目标识别中的问题。论文的核心内容集中在RAG框架的应用和改进上，因此应归类为RAG。` `药物发现` `蛋白质相互作用`

> GraPPI: A Retrieve-Divide-Solve GraphRAG Framework for Large-scale Protein-protein Interaction Exploration

# 摘要

> # 摘要
药物发现（DD）在公共卫生领域贡献卓著。研究人员假设抑制蛋白质错误折叠可延缓疾病进展，因此专注于目标识别（Target ID），寻找药物结合的蛋白质结构。尽管LLMs和RAG框架加速了药物发现，但将其整合到连贯的工作流程中仍具挑战。我们与药物发现研究人员进行了用户研究，评估LLMs和RAGs在Target ID中的适用性。研究发现：1）LLM应基于初始蛋白质和具有治疗潜力的候选蛋白质，提供多个蛋白质-蛋白质相互作用（PPIs）；2）模型需提供PPI及相关解释，以便更好理解。基于此，我们总结了以往Target ID方法的三大局限：1）语义模糊，2）缺乏可解释性，3）检索单元过短。为此，我们提出了GraPPI，一个基于大规模知识图谱（KG）的检索-分解-解决代理管道RAG框架，通过将PPI信号通路的分析分解为专注于PPI边分析的子任务，支持大规模PPI信号通路探索，助力治疗影响的理解。

> Drug discovery (DD) has tremendously contributed to maintaining and improving public health. Hypothesizing that inhibiting protein misfolding can slow disease progression, researchers focus on target identification (Target ID) to find protein structures for drug binding. While Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) frameworks have accelerated drug discovery, integrating models into cohesive workflows remains challenging. We conducted a user study with drug discovery researchers to identify the applicability of LLMs and RAGs in Target ID. We identified two main findings: 1) an LLM should provide multiple Protein-Protein Interactions (PPIs) based on an initial protein and protein candidates that have a therapeutic impact; 2) the model must provide the PPI and relevant explanations for better understanding. Based on these observations, we identified three limitations in previous approaches for Target ID: 1) semantic ambiguity, 2) lack of explainability, and 3) short retrieval units. To address these issues, we propose GraPPI, a large-scale knowledge graph (KG)-based retrieve-divide-solve agent pipeline RAG framework to support large-scale PPI signaling pathway exploration in understanding therapeutic impacts by decomposing the analysis of entire PPI pathways into sub-tasks focused on the analysis of PPI edges.

[Arxiv](https://arxiv.org/abs/2501.16382)