# 语言嵌入与动态图结合：神经架构表示学习的新探索

发布时间：2025年06月09日

`其他` `计算机体系结构` `硬件优化`

> Language Embedding Meets Dynamic Graph: A New Exploration for Neural Architecture Representation Learning

# 摘要

> 神经架构表示学习旨在将网络模型转化为特征表示，用于预测网络属性，在实际应用中的网络部署和设计中起着关键作用。近年来，受Transformer成功启发，与图神经网络（GNN）相结合的Transformer模型在表示学习方面取得了显著进展。然而，现有方法仍存在一些限制。首先，现有方法忽视了硬件属性信息，这与当前多样化深度学习硬件的趋势相悖，限制了模型的实际应用。其次，当前编码方法依赖静态邻接矩阵来表示拓扑结构，未能捕捉计算节点间的结构差异，最终影响编码效果。本文提出LeDG-Former，一个通过语言语义嵌入与动态图表示学习协同整合来克服这些限制的创新框架。具体而言，受大型语言模型（LLMs）启发，我们提出了一种语言嵌入框架，其中神经架构和硬件平台规范通过分词和LLM处理被投影到统一的语义空间，首次实现了跨不同硬件平台的零样本预测。然后，我们提出了一种基于动态图的Transformer来建模神经架构，从而提升了神经架构建模性能。在NNLQP基准上，LeDG-Former超越了之前的方法，建立了新的SOTA，同时展示了首次成功的跨硬件延迟预测能力。此外，我们的框架在单元结构的NAS-Bench-101和NAS-Bench-201数据集上也取得了优越性能。

> Neural Architecture Representation Learning aims to transform network models into feature representations for predicting network attributes, playing a crucial role in deploying and designing networks for real-world applications. Recently, inspired by the success of transformers, transformer-based models integrated with Graph Neural Networks (GNNs) have achieved significant progress in representation learning. However, current methods still have some limitations. First, existing methods overlook hardware attribute information, which conflicts with the current trend of diversified deep learning hardware and limits the practical applicability of models. Second, current encoding approaches rely on static adjacency matrices to represent topological structures, failing to capture the structural differences between computational nodes, which ultimately compromises encoding effectiveness. In this paper, we introduce LeDG-Former, an innovative framework that addresses these limitations through the synergistic integration of language-based semantic embedding and dynamic graph representation learning. Specifically, inspired by large language models (LLMs), we propose a language embedding framework where both neural architectures and hardware platform specifications are projected into a unified semantic space through tokenization and LLM processing, enabling zero-shot prediction across different hardware platforms for the first time. Then, we propose a dynamic graph-based transformer for modeling neural architectures, resulting in improved neural architecture modeling performance. On the NNLQP benchmark, LeDG-Former surpasses previous methods, establishing a new SOTA while demonstrating the first successful cross-hardware latency prediction capability. Furthermore, our framework achieves superior performance on the cell-structured NAS-Bench-101 and NAS-Bench-201 datasets.

[Arxiv](https://arxiv.org/abs/2506.07735)