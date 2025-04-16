# #构建通用图结构编码器之路

发布时间：2025年04月15日

`其他

理由：这篇论文专注于图结构编码和跨领域迁移学习，虽然提到了与大型语言模型的结合，但核心贡献在于图表示学习，属于图神经网络领域，而非直接的LLM应用或理论。因此，归类为其他。` `图数据` `图分析`

> Towards A Universal Graph Structural Encoder

# 摘要

> 大规模预训练的最新进展展示了学习适用于下游任务的通用化表示的潜力。然而，在图领域，跨不同图域捕捉和迁移结构信息仍然具有挑战性，这主要归因于不同上下文中固有的拓扑模式差异。此外，现有大多数模型难以捕捉复杂图结构的复杂性，导致对嵌入空间的探索不足。

为了解决这些挑战，我们提出了GFSE，一种通用的图结构编码器，旨在捕捉跨多样化领域（如分子图、社交网络和引用网络）的可迁移结构模式。GFSE是首个基于多个自监督学习目标预训练的跨域图结构编码器。基于图变换器构建，GFSE集成了由图归纳偏置引导的注意力机制，使其能够编码复杂多层级和细粒度的拓扑特征。

预训练的GFSE为图生成通用且理论上表达丰富的位置和结构编码，这些编码可以与各种下游图特征编码器无缝集成，包括用于向量化特征的图神经网络和用于文本属性图的大型语言模型。在合成和真实世界数据集上的全面实验表明，GFSE显著提升了模型性能，同时大幅减少了特定任务的微调需求。值得注意的是，GFSE在81.6%的评估案例中实现了最先进的性能，涵盖多样化的图模型和数据集，凸显了其作为图结构数据的强大且多功能编码器的潜力。

> Recent advancements in large-scale pre-training have shown the potential to learn generalizable representations for downstream tasks. In the graph domain, however, capturing and transferring structural information across different graph domains remains challenging, primarily due to the inherent differences in topological patterns across various contexts. Additionally, most existing models struggle to capture the complexity of rich graph structures, leading to inadequate exploration of the embedding space. To address these challenges, we propose GFSE, a universal graph structural encoder designed to capture transferable structural patterns across diverse domains such as molecular graphs, social networks, and citation networks. GFSE is the first cross-domain graph structural encoder pre-trained with multiple self-supervised learning objectives. Built on a Graph Transformer, GFSE incorporates attention mechanisms informed by graph inductive bias, enabling it to encode intricate multi-level and fine-grained topological features. The pre-trained GFSE produces generic and theoretically expressive positional and structural encoding for graphs, which can be seamlessly integrated with various downstream graph feature encoders, including graph neural networks for vectorized features and Large Language Models for text-attributed graphs. Comprehensive experiments on synthetic and real-world datasets demonstrate GFSE's capability to significantly enhance the model's performance while requiring substantially less task-specific fine-tuning. Notably, GFSE achieves state-of-the-art performance in 81.6% evaluated cases, spanning diverse graph models and datasets, highlighting its potential as a powerful and versatile encoder for graph-structured data.

[Arxiv](https://arxiv.org/abs/2504.10917)