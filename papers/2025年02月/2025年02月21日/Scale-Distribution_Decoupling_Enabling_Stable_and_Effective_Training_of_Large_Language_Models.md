# 规模-分布解耦：助力大型语言模型的稳定与高效训练

发布时间：2025年02月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）预训练中的训练稳定性问题，特别是针对Post-Norm Transformers架构。它提出了一种名为Scale-Distribution Decoupling（SDD）的新方法，通过分离全连接层中权重矩阵的尺度和分布来稳定训练。该方法涉及模型训练的优化策略，属于模型训练的理论层面，因此归类为LLM理论。` `人工智能` `模型训练`

> Scale-Distribution Decoupling: Enabling Stable and Effective Training of Large Language Models

# 摘要

> 在大型语言模型（LLMs）的预训练中，训练稳定性始终是一个难题，尤其是对于Post-Norm Transformers等容易出现梯度爆炸和消散的架构。本文提出了一种名为Scale-Distribution Decoupling（SDD）的新方法，通过分离全连接层中权重矩阵的尺度和分布来稳定训练。SDD利用归一化机制调节激活，并通过可学习的缩放向量维持良好条件的梯度，从而有效防止【数学公式】梯度爆炸和消散。这种分离通过确保稳定的梯度传播，特别在深度网络中显著提升了优化效率。实验结果表明，我们的方法在各种LLM架构和归一化配置下均表现出色，且方法轻量级、兼容现有框架，为稳定LLM训练提供了实用解决方案。代码已开源，访问https://github.com/kaihemo/SDD即可获取。

> Training stability is a persistent challenge in the pre-training of large language models (LLMs), particularly for architectures such as Post-Norm Transformers, which are prone to gradient explosion and dissipation. In this paper, we propose Scale-Distribution Decoupling (SDD), a novel approach that stabilizes training by explicitly decoupling the scale and distribution of the weight matrix in fully-connected layers. SDD applies a normalization mechanism to regulate activations and a learnable scaling vector to maintain well-conditioned gradients, effectively preventing $\textbf{gradient explosion and dissipation}$. This separation improves optimization efficiency, particularly in deep networks, by ensuring stable gradient propagation. Experimental results demonstrate that our method stabilizes training across various LLM architectures and outperforms existing techniques in different normalization configurations. Furthermore, the proposed method is lightweight and compatible with existing frameworks, making it a practical solution for stabilizing LLM training. Code is available at https://github.com/kaihemo/SDD.

[Arxiv](https://arxiv.org/abs/2502.15499)