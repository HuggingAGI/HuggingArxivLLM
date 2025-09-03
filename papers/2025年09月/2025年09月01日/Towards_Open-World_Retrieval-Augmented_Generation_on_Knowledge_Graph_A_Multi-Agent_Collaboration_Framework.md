# 面向开放世界的知识图谱检索增强生成：多智能体协作框架

发布时间：2025年09月01日

`RAG` `基础理论`

> Towards Open-World Retrieval-Augmented Generation on Knowledge Graph: A Multi-Agent Collaboration Framework

# 摘要

> 大型语言模型（LLMs）展现出卓越的语言理解与推理能力，但其对静态训练语料库的依赖导致易出现事实错误和知识空白。检索增强生成（RAG）通过整合外部知识源（尤其是结构化知识图谱（KGs））解决了这一局限，后者能提供明确语义和高效检索。然而，现有基于KG的RAG方法通常假设能够获取锚实体来启动图遍历，这使其在开放世界场景中的鲁棒性受限——此类场景中，查询与实体的准确链接并不可靠。为了克服这一局限，我们提出了AnchorRAG——一种适用于无需预定义锚实体的开放世界RAG的新型多智能体协作框架。具体而言，预测器智能体通过将用户查询术语与KG节点对齐，动态识别候选锚实体，并初始化独立的检索器智能体，从每个候选实体出发进行并行多跳探索。随后，监督器智能体为这些检索器智能体制定迭代式检索策略，并对生成的知识路径进行整合，从而生成最终答案。这种多智能体协作框架增强了检索鲁棒性，并降低了模糊或错误锚实体带来的影响。在四个公共基准数据集上的大量实验表明，AnchorRAG显著优于现有基线，并在现实世界问答任务上创下了新的最先进结果。

> Large Language Models (LLMs) have demonstrated strong capabilities in language understanding and reasoning. However, their dependence on static training corpora makes them prone to factual errors and knowledge gaps. Retrieval-Augmented Generation (RAG) addresses this limitation by incorporating external knowledge sources, especially structured Knowledge Graphs (KGs), which provide explicit semantics and efficient retrieval. Existing KG-based RAG approaches, however, generally assume that anchor entities are accessible to initiate graph traversal, which limits their robustness in open world settings where accurate linking between the query and the entity is unreliable. To overcome this limitation, we propose AnchorRAG, a novel multi-agent collaboration framework for open-world RAG without the predefined anchor entities. Specifically, a predictor agent dynamically identifies candidate anchor entities by aligning user query terms with KG nodes and initializes independent retriever agents to conduct parallel multi-hop explorations from each candidate. Then a supervisor agent formulates the iterative retrieval strategy for these retriever agents and synthesizes the resulting knowledge paths to generate the final answer. This multi-agent collaboration framework improves retrieval robustness and mitigates the impact of ambiguous or erroneous anchors. Extensive experiments on four public benchmarks demonstrate that AnchorRAG significantly outperforms existing baselines and establishes new state-of-the-art results on the real-world question answering tasks.

[Arxiv](https://arxiv.org/abs/2509.01238)