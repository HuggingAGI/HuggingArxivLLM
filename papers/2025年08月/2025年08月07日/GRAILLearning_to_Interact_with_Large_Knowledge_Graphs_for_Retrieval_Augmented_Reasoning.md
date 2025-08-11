# GRAIL：学习与大型知识图谱交互以增强检索推理

发布时间：2025年08月07日

`RAG

理由：这篇论文主要探讨了如何改进检索增强生成（RAG）技术，特别是在处理知识图谱等结构化知识方面的应用。论文提出了GRAIL框架，旨在解决现有RAG方法在图检索中的局限性，并通过实验验证了其有效性。因此，这篇论文应归类到RAG类别中。` `知识图谱` `问答系统`

> GRAIL:Learning to Interact with Large Knowledge Graphs for Retrieval Augmented Reasoning

# 摘要

> 大型语言模型（LLMs）与检索增强生成（RAG）技术的结合，在多个领域展现了卓越性能。然而，现有RAG方法在处理知识图谱等结构化知识方面存在局限。当前图检索方法在捕捉整体图结构和精度控制方面面临双重挑战，导致推理性能下降。为解决这一问题，我们提出GRAIL：一种基于大规模图交互的检索增强推理框架。GRAIL通过整合基于LLM的随机探索与路径筛选，构建数据合成管道，为每个任务自动生成精细推理轨迹。基于合成数据，我们采用两阶段训练过程，学习动态决策策略。通过将检索精度与简洁性平衡目标分解为细粒度监督奖励，提升数据效率与训练稳定性。在实际应用中，GRAIL采用交互式检索范式，使模型自主探索图路径，动态平衡检索广度与精度。实验结果显示，GRAIL在三个知识图问答数据集上实现了平均准确率提升21.01%，F1值提升22.43%。我们的源代码和数据集已开源，详情请访问https://github.com/Changgeww/GRAIL。

> Large Language Models (LLMs) integrated with Retrieval-Augmented Generation (RAG) techniques have exhibited remarkable performance across a wide range of domains. However, existing RAG approaches primarily operate on unstructured data and demonstrate limited capability in handling structured knowledge such as knowledge graphs. Meanwhile, current graph retrieval methods fundamentally struggle to capture holistic graph structures while simultaneously facing precision control challenges that manifest as either critical information gaps or excessive redundant connections, collectively undermining reasoning performance. To address this challenge, we propose GRAIL: Graph-Retrieval Augmented Interactive Learning, a framework designed to interact with large-scale graphs for retrieval-augmented reasoning. Specifically, GRAIL integrates LLM-guided random exploration with path filtering to establish a data synthesis pipeline, where a fine-grained reasoning trajectory is automatically generated for each task. Based on the synthesized data, we then employ a two-stage training process to learn a policy that dynamically decides the optimal actions at each reasoning step. The overall objective of precision-conciseness balance in graph retrieval is decoupled into fine-grained process-supervised rewards to enhance data efficiency and training stability. In practical deployment, GRAIL adopts an interactive retrieval paradigm, enabling the model to autonomously explore graph paths while dynamically balancing retrieval breadth and precision. Extensive experiments have shown that GRAIL achieves an average accuracy improvement of 21.01% and F1 improvement of 22.43% on three knowledge graph question-answering datasets. Our source code and datasets is available at https://github.com/Changgeww/GRAIL.

[Arxiv](https://arxiv.org/abs/2508.05498)