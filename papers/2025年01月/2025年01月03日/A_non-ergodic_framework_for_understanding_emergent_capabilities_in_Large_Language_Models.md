# 理解大型语言模型涌现能力的非遍历框架

发布时间：2025年01月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在规模扩大时涌现出新能力的理论框架。它提出了一个基于“邻近可能性”理论的数学框架来解释这些能力的涌现，并通过实验验证了这一框架。因此，这篇论文属于LLM理论类别，因为它专注于理论解释和模型能力的涌现机制。` `人工智能` `语言模型`

> A non-ergodic framework for understanding emergent capabilities in Large Language Models

# 摘要

> 大型语言模型在规模扩大时会意外涌现出新的能力，但我们需要一个理论框架来解释这些能力为何及如何出现。我们证明语言模型是非遍历系统，并基于斯图尔特·考夫曼的“邻近可能性”理论（TAP）提出了一个数学框架来解释能力的涌现。我们的资源受限TAP方程揭示了架构、训练和上下文约束如何通过语义空间中的相变相互作用来塑造模型能力。通过三种不同语言模型的实验，我们证明了能力是通过约束相互作用和路径依赖探索引导的离散转变而涌现的。这一框架为理解语言模型中的涌现提供了理论基础，并指导了能够引导能力涌现的架构设计。

> Large language models have emergent capabilities that come unexpectedly at scale, but we need a theoretical framework to explain why and how they emerge. We prove that language models are actually non-ergodic systems while providing a mathematical framework based on Stuart Kauffman's theory of the adjacent possible (TAP) to explain capability emergence. Our resource-constrained TAP equation demonstrates how architectural, training, and contextual constraints interact to shape model capabilities through phase transitions in semantic space. We prove through experiments with three different language models that capacities emerge through discrete transitions guided by constraint interactions and path-dependent exploration. This framework provides a theoretical basis for understanding emergence in language models and guides the development of architectures that can guide capability emergence.

[Arxiv](https://arxiv.org/abs/2501.01638)