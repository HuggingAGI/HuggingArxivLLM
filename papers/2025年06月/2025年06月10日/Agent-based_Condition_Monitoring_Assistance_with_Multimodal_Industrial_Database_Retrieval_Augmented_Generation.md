# 基于智能体的状态监测辅助系统，结合多模态工业数据库检索增强生成

发布时间：2025年06月10日

`RAG` `流程工业` `工业自动化`

> Agent-based Condition Monitoring Assistance with Multimodal Industrial Database Retrieval Augmented Generation

# 摘要

> 条件监控（CM）在流程工业中发挥着关键作用，确保了可靠性和效率。尽管计算机化维护系统能够有效识别和分类故障，但诸如故障严重性评估和维护决策等任务仍主要依赖于人工专家分析。当前系统自动执行的分析和决策通常表现出显著的不确定性，并伴随着较高的误报率，从而增加了工作负担并降低了效率。

本研究将大型语言模型（LLM）驱动的推理代理与CM工作流相结合，以满足分析师和行业需求，具体包括减少误报、提升故障严重性评估、增强决策支持以及提供可解释界面。我们提出了MindRAG，一个模块化框架，结合了多模态增强生成（RAG）技术和专为CM数据设计的新型向量存储结构。该框架利用现有标注和维护工单作为监督学习协议中的标签替代品，解决了在未标注和嘈杂的真实世界数据集上训练预测模型的常见挑战。

主要贡献包括：（1）一种将工业CM数据结构化为与LLM驱动工作流兼容的半结构化多模态向量存储的方法；（2）开发了针对CM数据的多模态RAG技术；（3）开发了能够应对真实世界CM查询的实际推理代理；（4）构建了一个在现实工业场景中集成和评估此类代理的实验框架。初步结果表明，在经验丰富的分析师的帮助下进行评估，MindRAG为更高效的警报管理提供了有意义的决策支持，从而提高了CM系统的可解释性。


> Condition monitoring (CM) plays a crucial role in ensuring reliability and efficiency in the process industry. Although computerised maintenance systems effectively detect and classify faults, tasks like fault severity estimation, and maintenance decisions still largely depend on human expert analysis. The analysis and decision making automatically performed by current systems typically exhibit considerable uncertainty and high false alarm rates, leading to increased workload and reduced efficiency.
  This work integrates large language model (LLM)-based reasoning agents with CM workflows to address analyst and industry needs, namely reducing false alarms, enhancing fault severity estimation, improving decision support, and offering explainable interfaces. We propose MindRAG, a modular framework combining multimodal retrieval-augmented generation (RAG) with novel vector store structures designed specifically for CM data. The framework leverages existing annotations and maintenance work orders as surrogates for labels in a supervised learning protocol, addressing the common challenge of training predictive models on unlabelled and noisy real-world datasets.
  The primary contributions include: (1) an approach for structuring industry CM data into a semi-structured multimodal vector store compatible with LLM-driven workflows; (2) developing multimodal RAG techniques tailored for CM data; (3) developing practical reasoning agents capable of addressing real-world CM queries; and (4) presenting an experimental framework for integrating and evaluating such agents in realistic industrial scenarios. Preliminary results, evaluated with the help of an experienced analyst, indicate that MindRAG provide meaningful decision support for more efficient management of alarms, thereby improving the interpretability of CM systems.

[Arxiv](https://arxiv.org/abs/2506.09247)