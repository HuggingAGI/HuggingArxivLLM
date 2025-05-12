# KG-HTC：将知识图谱融入大语言模型，实现高效零样本层次文本分类

发布时间：2025年05月08日

`RAG` `文本分类` `知识图谱`

> KG-HTC: Integrating Knowledge Graphs into LLMs for Effective Zero-shot Hierarchical Text Classification

# 摘要

> 层次文本分类（HTC）涉及将文档分配到 taxonomy 中组织的标签。以往的研究大多集中在监督学习方法上。然而，在现实场景中，由于标注数据的缺乏，使用监督 HTC 可能面临挑战。此外，HTC 在处理大规模标签空间和长尾分布时常常遇到困难。在这项研究中，我们提出了知识图谱用于零样本层次文本分类（KG-HTC），旨在通过将知识图谱与大语言模型（LLMs）结合，在分类过程中提供结构化的语义上下文，从而解决 HTC 在实际应用中的这些挑战。我们的方法利用检索增强生成（RAG）方法，从与输入文本相关的知识图谱中检索相关的子图。我们的 KG-HTC 能够增强 LLMs 对不同层次标签语义的理解。我们在三个开源 HTC 数据集上评估了 KG-HTC：WoS、DBpedia 和 Amazon。实验结果表明，在严格的零样本设置下，KG-HTC 显著优于三个基线方法，尤其是在分类层次的更深层实现了显著改进。这一评估证明了将结构化知识整合到 LLMs 中以解决 HTC 在大规模标签空间和长尾标签分布方面挑战的有效性。我们的代码可在以下链接获取：https://github.com/QianboZang/KG-HTC。


> Hierarchical Text Classification (HTC) involves assigning documents to labels organized within a taxonomy. Most previous research on HTC has focused on supervised methods. However, in real-world scenarios, employing supervised HTC can be challenging due to a lack of annotated data. Moreover, HTC often faces issues with large label spaces and long-tail distributions. In this work, we present Knowledge Graphs for zero-shot Hierarchical Text Classification (KG-HTC), which aims to address these challenges of HTC in applications by integrating knowledge graphs with Large Language Models (LLMs) to provide structured semantic context during classification. Our method retrieves relevant subgraphs from knowledge graphs related to the input text using a Retrieval-Augmented Generation (RAG) approach. Our KG-HTC can enhance LLMs to understand label semantics at various hierarchy levels. We evaluate KG-HTC on three open-source HTC datasets: WoS, DBpedia, and Amazon. Our experimental results show that KG-HTC significantly outperforms three baselines in the strict zero-shot setting, particularly achieving substantial improvements at deeper levels of the hierarchy. This evaluation demonstrates the effectiveness of incorporating structured knowledge into LLMs to address HTC's challenges in large label spaces and long-tailed label distributions. Our code is available at: https://github.com/QianboZang/KG-HTC.

[Arxiv](https://arxiv.org/abs/2505.05583)