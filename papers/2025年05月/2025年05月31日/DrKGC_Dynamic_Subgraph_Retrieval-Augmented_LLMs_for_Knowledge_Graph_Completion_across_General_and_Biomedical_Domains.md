# DrKGC：动态子图检索增强的大语言模型助力跨通用与生物医学领域的知识图谱补全

发布时间：2025年05月31日

`LLM应用` `知识图谱` `生物医学`

> DrKGC: Dynamic Subgraph Retrieval-Augmented LLMs for Knowledge Graph Completion across General and Biomedical Domains

# 摘要

> 知识图谱补全（KGC）的目标是通过现有三元组和文本信息预测知识图谱（KGs）中缺失的三元组。近年来，生成型大型语言模型（LLMs）在图任务中的应用不断增加。然而，现有方法通常将图上下文编码为文本形式，未能充分发挥LLMs在感知和推理图结构方面的潜力。为解决这一问题，我们提出了DrKGC（动态子图检索增强的LLMs用于知识图谱补全）。DrKGC采用灵活的轻量级模型训练策略，学习KG中的结构嵌入和逻辑规则。它通过一种创新的自底向上图检索方法，根据学习到的规则为每个查询提取子图。最后，图卷积网络（GCN）适配器利用检索到的子图增强结构嵌入，并将其整合到提示中，实现有效的LLM微调。在两个通用领域基准数据集和两个生物医学数据集上的实验结果表明，DrKGC表现优异。此外，生物医学领域的一个实际案例研究凸显了其可解释性和实际应用价值。

> Knowledge graph completion (KGC) aims to predict missing triples in knowledge graphs (KGs) by leveraging existing triples and textual information. Recently, generative large language models (LLMs) have been increasingly employed for graph tasks. However, current approaches typically encode graph context in textual form, which fails to fully exploit the potential of LLMs for perceiving and reasoning about graph structures. To address this limitation, we propose DrKGC (Dynamic Subgraph Retrieval-Augmented LLMs for Knowledge Graph Completion). DrKGC employs a flexible lightweight model training strategy to learn structural embeddings and logical rules within the KG. It then leverages a novel bottom-up graph retrieval method to extract a subgraph for each query guided by the learned rules. Finally, a graph convolutional network (GCN) adapter uses the retrieved subgraph to enhance the structural embeddings, which are then integrated into the prompt for effective LLM fine-tuning. Experimental results on two general domain benchmark datasets and two biomedical datasets demonstrate the superior performance of DrKGC. Furthermore, a realistic case study in the biomedical domain highlights its interpretability and practical utility.

[Arxiv](https://arxiv.org/abs/2506.00708)