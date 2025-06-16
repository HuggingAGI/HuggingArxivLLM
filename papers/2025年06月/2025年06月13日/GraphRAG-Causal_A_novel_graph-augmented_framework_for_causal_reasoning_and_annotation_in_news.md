# GraphRAG-Causal: 基于图结构增强的新闻因果推理与标注创新框架

发布时间：2025年06月13日

`RAG` `因果推理`

> GraphRAG-Causal: A novel graph-augmented framework for causal reasoning and annotation in news

# 摘要

> # GraphRAG-Causal：结合图检索与大语言模型的因果推理框架
GraphRAG-Causal 提出了一种结合图检索与大语言模型的创新框架，旨在提升新闻分析中的因果推理能力。传统 NLP 方法在识别复杂隐性因果关系时往往表现欠佳，尤其是在数据量有限的情况下。我们的方法通过将标注的新闻标题转化为结构化的因果知识图谱，有效解决了这一难题。

该框架采用三阶段流水线设计：
1. **数据准备**：将新闻句子标注并转化为因果图，捕捉原因、效果和触发关系。
2. **图检索**：利用 Neo4j 数据库存储因果图及其嵌入，并通过混合 Cypher 查询高效检索语义和结构上与查询相似的事件。
3. **LLM 推理**：基于 XML 提示的少量样本学习，利用检索到的因果图进行因果关系分类和标注。

实验结果表明，GraphRAG-Causal 在仅使用 20 个样本的情况下，因果分类任务的 F1 值可达 82.1%。这一方法在准确性和一致性上均有显著提升，特别适用于新闻可信度评估、虚假信息检测和政策分析等实时应用场景。

> GraphRAG-Causal introduces an innovative framework that combines graph-based retrieval with large language models to enhance causal reasoning in news analysis. Traditional NLP approaches often struggle with identifying complex, implicit causal links, especially in low-data scenarios. Our approach addresses these challenges by transforming annotated news headlines into structured causal knowledge graphs. It then employs a hybrid retrieval system that merges semantic embeddings with graph-based structural cues leveraging Neo4j to accurately match and retrieve relevant events. The framework is built on a three-stage pipeline: First, during Data Preparation, news sentences are meticulously annotated and converted into causal graphs capturing cause, effect, and trigger relationships. Next, the Graph Retrieval stage stores these graphs along with their embeddings in a Neo4j database and utilizes hybrid Cypher queries to efficiently identify events that share both semantic and structural similarities with a given query. Finally, the LLM Inference stage utilizes these retrieved causal graphs in a few-shot learning setup with XML-based prompting, enabling robust classification and tagging of causal relationships. Experimental evaluations demonstrate that GraphRAG-Causal achieves an impressive F1-score of 82.1% on causal classification using just 20 few-shot examples. This approach significantly boosts accuracy and consistency, making it highly suitable for real-time applications in news reliability assessment, misinformation detection, and policy analysis.

[Arxiv](https://arxiv.org/abs/2506.11600)