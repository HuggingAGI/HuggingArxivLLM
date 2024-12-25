# 大型语言模型是否擅长三元组预测？这是一项实证研究

发布时间：2024年12月24日

`LLM应用` `知识图谱` `语言模型`

> Is Large Language Model Good at Triple Set Prediction? An Empirical Study

# 摘要

> 知识图谱补全（KGC）任务的核心在于预测并补齐知识图谱中缺失的关系或节点。常见的 KGC 任务通常是在三元组中已知一两个元素的情况下推断未知元素。相较而言，三元组集预测（TSP）任务是更为实际的知识图谱补全任务，旨在依据已知三元组的信息预测未知三元组的所有元素。近些年来，大型语言模型（LLMs）在语言理解方面进展显著，在 KGC 任务中展现出巨大潜力。然而，LLM 在 TSP 任务中的潜力尚未被探究。所以，在本文中，我们提出了一个新的框架来摸索 LLM 在 TSP 任务中的长处与局限。具体而言，该框架包含基于 LLM 的规则挖掘和基于 LLM 的三元组集预测。首先借助嵌入丰富语义信息的知识图谱的关系列表来促使 LLM 生成规则。此过程高效且不依赖统计信息，更易挖掘出有效且切实的规则。对于每个子图，将指定规则与子图内的相关三元组结合运用，引导 LLM 预测缺失的三元组。接着，把所有子图的预测结果整合起来，得到知识图谱上完整的预测三元组集。最后，在相对完整的 CFamily 数据集上对该方法进行评估。实验结果显示，当要求 LLMs 依据大量事实知识来预测缺失的三元组时，会出现显著的幻觉，致使性能大幅下降。为进一步探究此现象的成因，本文通过详细的案例研究展开了全面的分析。

> The core of the Knowledge Graph Completion (KGC) task is to predict and complete the missing relations or nodes in a KG. Common KGC tasks are mostly about inferring unknown elements with one or two elements being known in a triple. In comparison, the Triple Set Prediction (TSP) task is a more realistic knowledge graph completion task. It aims to predict all elements of unknown triples based on the information from known triples. In recent years, large language models (LLMs) have exhibited significant advancements in language comprehension, demonstrating considerable potential for KGC tasks. However, the potential of LLM on the TSP task has not yet to be investigated. Thus in this paper we proposed a new framework to explore the strengths and limitations of LLM in the TSP task. Specifically, the framework consists of LLM-based rule mining and LLM-based triple set prediction. The relation list of KG embedded within rich semantic information is first leveraged to prompt LLM in the generation of rules. This process is both efficient and independent of statistical information, making it easier to mine effective and realistic rules. For each subgraph, the specified rule is applied in conjunction with the relevant triples within that subgraph to guide the LLM in predicting the missing triples. Subsequently, the predictions from all subgraphs are consolidated to derive the complete set of predicted triples on KG. Finally, the method is evaluated on the relatively complete CFamily dataset. The experimental results indicate that when LLMs are required to adhere to a large amount of factual knowledge to predict missing triples, significant hallucinations occurs, leading to a noticeable decline in performance. To further explore the causes of this phenomenon, this paper presents a comprehensive analysis supported by a detailed case study.

[Arxiv](https://arxiv.org/abs/2412.18443)