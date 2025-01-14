# ADKGD: 双通道训练在知识图谱异常检测中的应用

发布时间：2025年01月13日

`其他

**理由**：这篇论文主要讨论的是知识图谱（KGs）中的异常检测问题，并提出了一种基于双通道学习的算法（ADKGD）。虽然论文提到了大型语言模型（LLMs）和知识图谱的关系，但核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其归类为“其他”更为合适。` `知识图谱` `异常检测`

> ADKGD: Anomaly Detection in Knowledge Graphs with Dual-Channel Training

# 摘要

> # 摘要
在大型语言模型（LLMs）的发展中，确保数据源的准确性和可靠性至关重要。尽管 LLMs 在多种应用中表现卓越，但由于训练数据中的知识缺口，它们常常出现幻觉和不准确的问题。知识图谱（KGs）作为一种强大的结构化工具，能够作为重要的外部信息来源，有效缓解这些问题。通过提供对现实世界数据的结构化和全面理解，KGs 显著提升了 LLMs 的性能和可靠性。然而，在从非结构化数据中提取三元组构建 KGs 时，常常会出现错误，这可能导致下游任务（如问答和推荐系统）的性能下降。因此，KGs 中的异常检测对于识别和纠正这些错误至关重要。本文提出了一种基于双通道学习的知识图谱异常检测算法（ADKGD）。ADKGD 通过双通道学习方法，从实体视图和三元组视图的角度增强表示学习。此外，我们的框架采用跨层方法，集成了内部信息聚合和上下文信息聚合。我们引入了 Kullback-Leibler（KL）损失组件，以提高双通道之间评分函数的准确性。为了验证 ADKGD 的性能，我们在三个真实世界的 KGs（WN18RR、FB15K 和 NELL-995）上进行了实证研究。实验结果表明，ADKGD 在异常检测方面优于现有最先进的算法。源代码和数据集已公开，可在 https://github.com/csjywu1/ADKGD 获取。

> In the current development of large language models (LLMs), it is important to ensure the accuracy and reliability of the underlying data sources. LLMs are critical for various applications, but they often suffer from hallucinations and inaccuracies due to knowledge gaps in the training data. Knowledge graphs (KGs), as a powerful structural tool, could serve as a vital external information source to mitigate the aforementioned issues. By providing a structured and comprehensive understanding of real-world data, KGs enhance the performance and reliability of LLMs. However, it is common that errors exist in KGs while extracting triplets from unstructured data to construct KGs. This could lead to degraded performance in downstream tasks such as question-answering and recommender systems. Therefore, anomaly detection in KGs is essential to identify and correct these errors. This paper presents an anomaly detection algorithm in knowledge graphs with dual-channel learning (ADKGD). ADKGD leverages a dual-channel learning approach to enhance representation learning from both the entity-view and triplet-view perspectives. Furthermore, using a cross-layer approach, our framework integrates internal information aggregation and context information aggregation. We introduce a kullback-leibler (KL)-loss component to improve the accuracy of the scoring function between the dual channels. To evaluate ADKGD's performance, we conduct empirical studies on three real-world KGs: WN18RR, FB15K, and NELL-995. Experimental results demonstrate that ADKGD outperforms the state-of-the-art anomaly detection algorithms. The source code and datasets are publicly available at https://github.com/csjywu1/ADKGD.

[Arxiv](https://arxiv.org/abs/2501.07078)