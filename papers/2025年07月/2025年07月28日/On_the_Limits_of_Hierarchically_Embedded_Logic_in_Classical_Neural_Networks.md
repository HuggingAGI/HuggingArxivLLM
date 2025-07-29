# # 探讨经典神经网络中分层嵌入逻辑的局限性

发布时间：2025年07月28日

`LLM理论` `神经网络` `语言模型`

> On the Limits of Hierarchically Embedded Logic in Classical Neural Networks

# 摘要

> 我们提出了一种基于神经网络架构深度的语言推理限制模型。通过将神经网络视为逻辑谓词空间中的线性算子，我们发现每一层最多只能增加一个逻辑推理层次。我们证明，深度为特定值的神经网络无法忠实表示更高阶逻辑中的谓词，例如对复杂谓词的计数，这表明逻辑表达能力存在严格的上限。这种结构在分词和嵌入过程中引入了一个零空间，从而排除了更高阶谓词的可表示性。我们的框架解释了幻觉、重复和有限规划等现象，并为理解更高阶逻辑的近似出现提供了基础。这些发现为未来语言模型的架构扩展和可解释性策略提供了方向。

> We propose a formal model of reasoning limitations in large neural net models for language, grounded in the depth of their neural architecture. By treating neural networks as linear operators over logic predicate space we show that each layer can encode at most one additional level of logical reasoning. We prove that a neural network of depth a particular depth cannot faithfully represent predicates in a one higher order logic, such as simple counting over complex predicates, implying a strict upper bound on logical expressiveness. This structure induces a nontrivial null space during tokenization and embedding, excluding higher-order predicates from representability. Our framework offers a natural explanation for phenomena such as hallucination, repetition, and limited planning, while also providing a foundation for understanding how approximations to higher-order logic may emerge. These results motivate architectural extensions and interpretability strategies in future development of language models.

[Arxiv](https://arxiv.org/abs/2507.20960)