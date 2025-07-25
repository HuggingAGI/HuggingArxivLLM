# 双曲深度学习在基础模型中的应用综述

发布时间：2025年07月23日

`LLM理论

摘要讨论了大型语言模型（LLMs）和其他基础模型的核心局限，并探讨了双曲空间作为替代几何的可能性，以优化模型的归纳偏置和性能。这属于模型的理论层面分析和改进，因此归类为LLM理论。` `基础模型` `几何空间`

> Hyperbolic Deep Learning for Foundation Models: A Survey

# 摘要

> 基于大规模数据预训练的基础模型，如大型语言模型（LLMs）、视觉语言模型（VLMs）和大型多模态模型，在各类下游任务中表现优异。然而，近期研究揭示了这些模型的三大核心局限：（1）表示能力有限，（2）适应性不足，（3）扩展性减弱。这些缺陷引出了一个重要问题：欧几里得几何是否真的是所有基础模型的最优归纳偏置？或者，引入替代几何空间能否帮助模型更好地贴合现实数据的内在结构，从而优化推理过程？

双曲空间，一类以距离为基准呈现指数级体积增长的非欧几何流形，提供了一个数学上严谨的解决方案。这类空间能够以远低于欧几里得对应物的维度，实现层级结构（如树状结构、分类法）和幂律分布的低失真嵌入。近期研究充分利用这些特性，显著提升了基础模型的性能，包括增强LLMs的复杂推理能力、VLMs的零样本泛化能力，以及跨模态语义对齐，同时保持了参数效率。

本文对双曲神经网络及其在基础模型中的最新发展进行了全面回顾，并指出了推动该领域发展的关键挑战和研究方向。

> Foundation models pre-trained on massive datasets, including large language models (LLMs), vision-language models (VLMs), and large multimodal models, have demonstrated remarkable success in diverse downstream tasks. However, recent studies have shown fundamental limitations of these models: (1) limited representational capacity, (2) lower adaptability, and (3) diminishing scalability. These shortcomings raise a critical question: is Euclidean geometry truly the optimal inductive bias for all foundation models, or could incorporating alternative geometric spaces enable models to better align with the intrinsic structure of real-world data and improve reasoning processes? Hyperbolic spaces, a class of non-Euclidean manifolds characterized by exponential volume growth with respect to distance, offer a mathematically grounded solution. These spaces enable low-distortion embeddings of hierarchical structures (e.g., trees, taxonomies) and power-law distributions with substantially fewer dimensions compared to Euclidean counterparts. Recent advances have leveraged these properties to enhance foundation models, including improving LLMs' complex reasoning ability, VLMs' zero-shot generalization, and cross-modal semantic alignment, while maintaining parameter efficiency. This paper provides a comprehensive review of hyperbolic neural networks and their recent development for foundation models. We further outline key challenges and research directions to advance the field.

[Arxiv](https://arxiv.org/abs/2507.17787)