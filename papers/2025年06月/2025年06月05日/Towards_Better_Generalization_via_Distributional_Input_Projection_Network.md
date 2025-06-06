# # 迈向更好的泛化：基于分布式输入投影网络
通过分布式输入投影网络，我们朝着模型泛化能力的提升迈出了重要一步。

发布时间：2025年06月05日

`其他

理由：这篇论文主要探讨了模型泛化能力的提升方法，提出了一个通用的框架DIPNet，并在多种模型架构中进行了验证，包括LLMs。虽然涉及LLMs，但其核心是模型泛化的理论和方法，属于更广泛的深度学习理论，而非专注于LLM的应用或理论。因此，归类为其他。` `人工智能` `机器学习`

> Towards Better Generalization via Distributional Input Projection Network

# 摘要

> 随着过参数化模型的广泛应用，单靠训练损失已不足以全面反映模型的泛化能力。虽然平滑性与多种场景下的更好泛化表现相关，但在神经网络中直接实现平滑性仍具挑战。为解决这一难题，我们提出了一种创新框架——分布式输入投影网络（DIPNet），该框架在每层将输入投影到可学习的分布中。这种分布表示能够生成更平滑的损失景观，从而促进更佳的泛化性能。我们的理论分析表明，DIPNet通过降低网络的局部平滑性度量和Lipschitz常数，显著提升了模型的泛化能力。在实验中，我们对包括视觉变换器（ViTs）、大型语言模型（LLMs）、ResNet和MLPs在内的多种架构和任务进行了验证，结果表明，DIPNet在标准设置、对抗攻击、分布外输入和推理基准测试中均能显著提升测试性能。此外，我们展示了该输入投影策略可轻松整合到现有模型中，为提升现代深度学习的泛化性能提供了一种通用且有效的方法。

> As overparameterized models become increasingly prevalent, training loss alone offers limited insight into generalization performance. While smoothness has been linked to improved generalization across various settings, directly enforcing smoothness in neural networks remains challenging. To address this, we introduce Distributional Input Projection Networks (DIPNet), a novel framework that projects inputs into learnable distributions at each layer. This distributional representation induces a smoother loss landscape with respect to the input, promoting better generalization. We provide theoretical analysis showing that DIPNet reduces both local smoothness measures and the Lipschitz constant of the network, contributing to improved generalization performance. Empirically, we validate DIPNet across a wide range of architectures and tasks, including Vision Transformers (ViTs), Large Language Models (LLMs), ResNet and MLPs. Our method consistently enhances test performance under standard settings, adversarial attacks, out-of-distribution inputs, and reasoning benchmarks. We demonstrate that the proposed input projection strategy can be seamlessly integrated into existing models, providing a general and effective approach for boosting generalization performance in modern deep learning.

[Arxiv](https://arxiv.org/abs/2506.04690)