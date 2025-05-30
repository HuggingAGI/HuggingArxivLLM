# AutoSchemaKG：通过从网络规模文本中动态抽取模式，实现自主知识图谱构建

发布时间：2025年05月29日

`LLM应用

理由：这篇论文探讨了大型语言模型在知识图谱构建中的应用，展示了如何通过LLM提升事实准确性，属于LLM的实际应用案例。` `知识图谱` `问答系统`

> AutoSchemaKG: Autonomous Knowledge Graph Construction through Dynamic Schema Induction from Web-Scale Corpora

# 摘要

> 我们推出了AutoSchemaKG框架，一个完全自主的知识图谱构建系统，告别预先定义模式的时代。系统基于大型语言模型，从文本中同步提取知识三元组并推导全面模式，精准建模实体与事件，通过概念化将实例分类至语义范畴。处理5000万份文档后，我们构建了ATLAS知识图谱家族，包含9亿多节点和59亿条边。该方法在多跳问答任务中超越现有最优模型，显著提升了大型语言模型的事实准确性。值得关注的是，我们的模式推导与人工设计模式在语义上达到95%的对齐度，且完全无需人工干预，这表明百亿级动态模式知识图谱能有效补充分布式参数知识，为大型语言模型注入更强大的知识能力。

> We present AutoSchemaKG, a framework for fully autonomous knowledge graph construction that eliminates the need for predefined schemas. Our system leverages large language models to simultaneously extract knowledge triples and induce comprehensive schemas directly from text, modeling both entities and events while employing conceptualization to organize instances into semantic categories. Processing over 50 million documents, we construct ATLAS (Automated Triple Linking And Schema induction), a family of knowledge graphs with 900+ million nodes and 5.9 billion edges. This approach outperforms state-of-the-art baselines on multi-hop QA tasks and enhances LLM factuality. Notably, our schema induction achieves 95\% semantic alignment with human-crafted schemas with zero manual intervention, demonstrating that billion-scale knowledge graphs with dynamically induced schemas can effectively complement parametric knowledge in large language models.

[Arxiv](https://arxiv.org/abs/2505.23628)