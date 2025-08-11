# 几个词就能误导生成结果：基于图的检索增强生成模型的知识投毒攻击

发布时间：2025年08月06日

`RAG` `知识图谱` `问答系统`

> A Few Words Can Distort Graphs: Knowledge Poisoning Attacks on Graph-based Retrieval-Augmented Generation of Large Language Models

# 摘要

> 基于图的检索增强生成（GraphRAG）作为一种极具前景的方法，通过将原始文本转化为结构化的知识图谱，显著提升了大型语言模型（LLMs）的准确性和可解释性。然而，GraphRAG在构建图谱过程中依赖LLMs从原始文本中提取知识，这一过程可能被恶意操控以植入误导性信息。针对这一攻击面，我们提出了两种知识投毒攻击方法（KPAs），并证明只需修改源文本中的少量词汇，即可大幅改变构建的图谱、污染GraphRAG，并严重误导下游推理。第一种攻击方法名为定向知识投毒攻击（TKPA），通过图论分析定位生成图谱中的脆弱节点，并借助LLMs重写相关叙述，实现对特定问答结果的精准控制，成功率高达93.1%，同时保持中毒文本的流畅与自然。第二种攻击方法名为通用知识投毒攻击（UKPA），通过利用代词和依存关系等语言线索，通过修改具有全局影响力的词汇来破坏生成图谱的结构完整性。实验表明，仅需修改不到0.05%的文本内容，问答准确率就从95%降至50%。此外，实验还表明，现有的先进防御方法无法检测到这些攻击，凸显了在GraphRAG流水线中防范知识投毒攻击仍是一个亟待探索的领域。

> Graph-based Retrieval-Augmented Generation (GraphRAG) has recently emerged as a promising paradigm for enhancing large language models (LLMs) by converting raw text into structured knowledge graphs, improving both accuracy and explainability. However, GraphRAG relies on LLMs to extract knowledge from raw text during graph construction, and this process can be maliciously manipulated to implant misleading information. Targeting this attack surface, we propose two knowledge poisoning attacks (KPAs) and demonstrate that modifying only a few words in the source text can significantly change the constructed graph, poison the GraphRAG, and severely mislead downstream reasoning. The first attack, named Targeted KPA (TKPA), utilizes graph-theoretic analysis to locate vulnerable nodes in the generated graphs and rewrites the corresponding narratives with LLMs, achieving precise control over specific question-answering (QA) outcomes with a success rate of 93.1\%, while keeping the poisoned text fluent and natural. The second attack, named Universal KPA (UKPA), exploits linguistic cues such as pronouns and dependency relations to disrupt the structural integrity of the generated graph by altering globally influential words. With fewer than 0.05\% of full text modified, the QA accuracy collapses from 95\% to 50\%. Furthermore, experiments show that state-of-the-art defense methods fail to detect these attacks, highlighting that securing GraphRAG pipelines against knowledge poisoning remains largely unexplored.

[Arxiv](https://arxiv.org/abs/2508.04276)