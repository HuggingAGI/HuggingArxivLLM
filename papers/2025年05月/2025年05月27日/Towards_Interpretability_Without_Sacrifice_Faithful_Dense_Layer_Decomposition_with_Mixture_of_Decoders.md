# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月27日

`LLM理论` `模型设计`

> Towards Interpretability Without Sacrifice: Faithful Dense Layer Decomposition with Mixture of Decoders

# 摘要

> 多层感知机（MLPs）作为大型语言模型的核心组件，因其密集表征特性而难以被理解和控制。近期研究通过神经元级别稀疏性实现可解释的近似，但未能忠实还原原始映射，导致模型性能显著下降。本文提出采用层级别稀疏性来解决这一难题，推出了解码器混合物（MxDs）。MxDs超越传统MLPs和门控线性单元，将预训练的密集层扩展为数万种专业子层。通过灵活的张量分解，每个MxD子层在稀疏激活下仍能保持全秩权重的线性变换，确保了模型的表达能力。实验结果显示，在高达30亿参数的模型中，MxDs在稀疏性与精度的平衡上远超现有最优方法。进一步研究表明，MxDs能够学习到与自然语言同样专业的特征，为设计可解释且忠实的模型分解方法提供了全新思路。代码已开源：https://github.com/james-oldfield/MxD/。

> Multilayer perceptrons (MLPs) are an integral part of large language models, yet their dense representations render them difficult to understand, edit, and steer. Recent methods learn interpretable approximations via neuron-level sparsity, yet fail to faithfully reconstruct the original mapping--significantly increasing model's next-token cross-entropy loss. In this paper, we advocate for moving to layer-level sparsity to overcome the accuracy trade-off in sparse layer approximation. Under this paradigm, we introduce Mixture of Decoders (MxDs). MxDs generalize MLPs and Gated Linear Units, expanding pre-trained dense layers into tens of thousands of specialized sublayers. Through a flexible form of tensor factorization, each sparsely activating MxD sublayer implements a linear transformation with full-rank weights--preserving the original decoders' expressive capacity even under heavy sparsity. Experimentally, we show that MxDs significantly outperform state-of-the-art methods (e.g., Transcoders) on the sparsity-accuracy frontier in language models with up to 3B parameters. Further evaluations on sparse probing and feature steering demonstrate that MxDs learn similarly specialized features of natural language--opening up a promising new avenue for designing interpretable yet faithful decompositions. Our code is included at: https://github.com/james-oldfield/MxD/.

[Arxiv](https://arxiv.org/abs/2505.21364)