# 一个基于大型语言模型的推荐自动图构建框架

发布时间：2024年12月24日

`LLM应用`

> An Automatic Graph Construction Framework based on Large Language Models for Recommendation

# 摘要

> 图神经网络（GNNs）已成为从图结构数据中学习以实现推荐的前沿方法。然而，现有的多数基于 GNN 的推荐方法，都聚焦于基于预定义图对模型结构和学习策略的优化，却忽视了图构建阶段的重要性。早期的图构建工作往往依赖特定规则或众包，不是过于简单就是太过费力。近来，鉴于大型语言模型（LLMs）丰富的开放世界知识和出色的推理能力，相关工作开始利用其实现图构建的自动化。但它们通常存在两个局限：（1）全局视图不可见（比如，忽略了上下文信息）；（2）构建效率低。为此，我们推出了 AutoGraph，这是一个基于 LLMs 的推荐用自动图构建框架。具体而言，我们先利用 LLMs 推断用户偏好和项目知识，并将其编码为语义向量。接着，通过向量量化从语义向量中提取潜在因素。然后把潜在因素作为额外节点，连接用户/项目节点，从而得到具有深度全局视图语义的图。我们还进一步设计了基于元路径的消息聚合，以有效聚合语义和协作信息。该框架不依赖于模型，能与不同的骨干模型兼容。在三个真实世界数据集上开展的大量实验表明，AutoGraph 比现有基线方法更有效、更高效。我们已在华为广告平台部署了 AutoGraph，在在线 A/B 测试中，RPM 提升了 2.69%，eCPM 提升了 7.31%。当下，AutoGraph 已作为主要流量模型，为数亿人服务。

> Graph neural networks (GNNs) have emerged as state-of-the-art methods to learn from graph-structured data for recommendation. However, most existing GNN-based recommendation methods focus on the optimization of model structures and learning strategies based on pre-defined graphs, neglecting the importance of the graph construction stage. Earlier works for graph construction usually rely on speciffic rules or crowdsourcing, which are either too simplistic or too labor-intensive. Recent works start to utilize large language models (LLMs) to automate the graph construction, in view of their abundant open-world knowledge and remarkable reasoning capabilities. Nevertheless, they generally suffer from two limitations: (1) invisibility of global view (e.g., overlooking contextual information) and (2) construction inefficiency. To this end, we introduce AutoGraph, an automatic graph construction framework based on LLMs for recommendation. Specifically, we first use LLMs to infer the user preference and item knowledge, which is encoded as semantic vectors. Next, we employ vector quantization to extract the latent factors from the semantic vectors. The latent factors are then incorporated as extra nodes to link the user/item nodes, resulting in a graph with in-depth global-view semantics. We further design metapath-based message aggregation to effectively aggregate the semantic and collaborative information. The framework is model-agnostic and compatible with different backbone models. Extensive experiments on three real-world datasets demonstrate the efficacy and efffciency of AutoGraph compared to existing baseline methods. We have deployed AutoGraph in Huawei advertising platform, and gain a 2.69% improvement on RPM and a 7.31% improvement on eCPM in the online A/B test. Currently AutoGraph has been used as the main trafffc model, serving hundreds of millions of people.

[Arxiv](https://arxiv.org/abs/2412.18241)