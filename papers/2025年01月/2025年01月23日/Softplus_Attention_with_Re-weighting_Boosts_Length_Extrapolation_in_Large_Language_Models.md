# Softplus 注意力机制结合重新加权，显著提升了大型语言模型的长度外推性能。

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要讨论了大型语言模型中的注意力机制，特别是针对传统Softmax注意力在推理标记长度增加时面临的问题，提出了一种新型的注意力机制。该研究涉及模型的理论改进和性能优化，属于对大型语言模型内部机制的理论探讨和改进，因此应归类为LLM理论。` `机器学习`

> Softplus Attention with Re-weighting Boosts Length Extrapolation in Large Language Models

# 摘要

> 近年来，大型语言模型凭借自注意力机制取得了显著成就。然而，传统Softmax注意力在推理标记长度增加时，常面临数值不稳定和性能下降的挑战。本文创新性地将Softmax操作拆解为非线性变换和$l_1$-范数，发现后者对维持模型性能至关重要。通过采用Softplus激活函数替代非线性变换，并结合不变性熵为不同标记长度动态调整比例因子，我们设计出一种新型注意力机制，其性能在各种推理长度上均超越传统Softmax注意力。为进一步增强该机制的长度外推能力，我们引入了重新加权策略，强化重要注意力权重，弱化次要权重，使模型更精准聚焦于关键标记。结合我们的注意力机制，该方法在处理长序列时展现出巨大潜力，即使在训练标记长度的16倍情况下，仍能保持验证损失近乎恒定，同时确保数值稳定性。代码已开源：https://github.com/iminfine/freeatten。

> Large language models have achieved remarkable success in recent years, primarily due to the implementation of self-attention mechanisms. However, traditional Softmax attention suffers from numerical instability and reduced performance as the length of inference tokens increases. This paper addresses these issues by decomposing the Softmax operation into a non-linear transformation and the $l_1$-norm. We identify the latter as essential for maintaining model performance. By replacing the non-linear transformation with the Softplus activation function and introducing a dynamic length scale factor for different token lengths based on invariance entropy, we create a novel attention mechanism with performance better than conventional Softmax attention across various inference lengths. To further improve the length extrapolation ability of the proposed attention mechanism, we introduce a re-weighting mechanism that amplifies significant attention weights while diminishing weaker ones, enabling the model to concentrate more effectively on relevant tokens. When combined with our proposed attention mechanism, this approach demonstrates significant promise in managing longer sequences, maintaining nearly constant validation loss even at 16$\times$ the training token length while ensuring numerical stability. Our code is available at: https://github.com/iminfine/freeatten.

[Arxiv](https://arxiv.org/abs/2501.13428)