# 研究高效且可推广的图检索器，针对知识图谱问答任务

发布时间：2025年06月11日

`RAG` `知识图谱` `问答系统`

> Learning Efficient and Generalizable Graph Retriever for Knowledge-Graph Question Answering

# 摘要

> 大型语言模型（LLMs）在多领域展现了强大的归纳推理能力，但其可靠性受限于知识过时和幻觉现象。检索增强生成（RAG）通过与外部知识结合有效缓解了这些问题，但现有方法主要依赖非结构化文本，限制了可解释性和结构化推理。知识图谱以关系三元组形式表示事实，提供更结构化、紧凑的替代方案。

近期研究将知识图谱与LLMs结合用于知识图谱问答（KGQA），其中大部分采用检索-推理范式。基于图的检索器在此框架下表现优异，但仍面临泛化能力的挑战。本研究提出RAPL框架，通过以下三方面实现高效且有效的图检索：

1. 结合启发式信号与参数化模型的两阶段标注策略，提供因果关联的监督信号；
2. 捕捉三元组内部及跨三元组交互关系的模型不可知图转换方法，提升表达能力；
3. 基于路径的推理策略，支持从理性知识中学习并通过结构化输入支持下游推理。

实证结果表明，RAPL超越现有最优方法2.66%-20.34%，显著缩小了基于LLM的小型推理器与更强大推理器的性能差距，同时也缩小了跨数据集设置下的性能差距，凸显其卓越的检索能力和泛化性能。代码可从以下链接获取：https://github.com/tianyao-aka/RAPL。


> Large Language Models (LLMs) have shown strong inductive reasoning ability across various domains, but their reliability is hindered by the outdated knowledge and hallucinations. Retrieval-Augmented Generation mitigates these issues by grounding LLMs with external knowledge; however, most existing RAG pipelines rely on unstructured text, limiting interpretability and structured reasoning. Knowledge graphs, which represent facts as relational triples, offer a more structured and compact alternative. Recent studies have explored integrating knowledge graphs with LLMs for knowledge graph question answering (KGQA), with a significant proportion adopting the retrieve-then-reasoning paradigm. In this framework, graph-based retrievers have demonstrated strong empirical performance, yet they still face challenges in generalization ability. In this work, we propose RAPL, a novel framework for efficient and effective graph retrieval in KGQA. RAPL addresses these limitations through three aspects: (1) a two-stage labeling strategy that combines heuristic signals with parametric models to provide causally grounded supervision; (2) a model-agnostic graph transformation approach to capture both intra- and inter-triple interactions, thereby enhancing representational capacity; and (3) a path-based reasoning strategy that facilitates learning from the injected rational knowledge, and supports downstream reasoner through structured inputs. Empirically, RAPL outperforms state-of-the-art methods by $2.66\%-20.34\%$, and significantly reduces the performance gap between smaller and more powerful LLM-based reasoners, as well as the gap under cross-dataset settings, highlighting its superior retrieval capability and generalizability. Codes are available at: https://github.com/tianyao-aka/RAPL.

[Arxiv](https://arxiv.org/abs/2506.09645)