# HetGCoT-Rec: 异构图增强的思维链LLM推理助力期刊推荐

发布时间：2025年01月02日

`LLM应用

理由：这篇论文提出了一个名为HetGCoT-Rec的框架，该框架通过链式思维推理深度整合异构图变换器与大型语言模型（LLMs），用于学术期刊推荐。论文的核心在于利用LLMs进行推理和推荐，并结合图神经网络（GNNs）来增强推荐的可解释性和准确性。因此，这篇论文主要关注的是如何将LLMs应用于具体的任务（学术期刊推荐），属于LLM应用的范畴。` `学术出版` `推荐系统`

> HetGCoT-Rec: Heterogeneous Graph-Enhanced Chain-of-Thought LLM Reasoning for Journal Recommendation

# 摘要

> # 摘要
学术期刊推荐需要巧妙融合学术网络的结构理解与可解释的推荐。尽管图神经网络（GNNs）和大型语言模型（LLMs）在各自领域表现出色，但现有方法在推理层面往往难以实现真正的整合。我们提出了HetGCoT-Rec框架，通过链式思维推理深度整合异构图变换器与LLMs。该框架具备两大技术创新：（1）结构感知机制，将异构图神经网络学习到的子图信息转化为自然语言上下文，利用预定义元路径捕捉学术关系；（2）多步推理策略，系统地将图派生的上下文嵌入LLM的分阶段推理过程。在OpenAlex数据集上的实验显示，我们的方法显著超越基线，命中率达96.48%，H@1准确率达92.21%。此外，我们验证了该框架在不同LLM架构上的适应性，推荐准确性和解释质量均得到一致提升。本研究为结合图结构推理与语言模型实现可解释学术场所推荐提供了有效途径。

> Academic journal recommendation requires effectively combining structural understanding of scholarly networks with interpretable recommendations. While graph neural networks (GNNs) and large language models (LLMs) excel in their respective domains, current approaches often fail to achieve true integration at the reasoning level. We propose HetGCoT-Rec, a framework that deeply integrates heterogeneous graph transformer with LLMs through chain-of-thought reasoning. Our framework features two key technical innovations: (1) a structure-aware mechanism that transforms heterogeneous graph neural network learned subgraph information into natural language contexts, utilizing predefined metapaths to capture academic relationships, and (2) a multi-step reasoning strategy that systematically embeds graph-derived contexts into the LLM's stage-wise reasoning process. Experiments on a dataset collected from OpenAlex demonstrate that our approach significantly outperforms baseline methods, achieving 96.48% Hit rate and 92.21% H@1 accuracy. Furthermore, we validate the framework's adaptability across different LLM architectures, showing consistent improvements in both recommendation accuracy and explanation quality. Our work demonstrates an effective approach for combining graph-structured reasoning with language models for interpretable academic venue recommendations.

[Arxiv](https://arxiv.org/abs/2501.01203)