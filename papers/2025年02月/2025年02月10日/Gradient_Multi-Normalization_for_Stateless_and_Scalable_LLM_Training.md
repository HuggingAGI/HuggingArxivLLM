# 用于无状态且可扩展的大型语言模型训练的梯度多归一化方法

发布时间：2025年02月10日

`LLM理论

摘要讨论了大型语言模型（LLMs）训练中使用的优化器及其改进方法，属于优化和训练策略的理论研究。` `人工智能` `机器学习`

> Gradient Multi-Normalization for Stateless and Scalable LLM Training

# 摘要

> 训练大型语言模型（LLMs）通常使用自适应优化器（如Adam，Kingma & Ba, 2015），这些优化器通过存储额外状态信息加速收敛，但会产生显著内存开销。最近，SWAN（Ma et al., 2024）通过消除优化器状态需求，并借助多步预处理程序处理瞬时梯度，实现了与Adam相当的性能。受SWAN启发，我们提出了一种新的无状态优化器设计框架，该框架根据多种范数对随机梯度进行归一化。我们提出了一种简单交替方案，用于强制执行这些范数下的梯度归一化。我们的方法可产生任意精度的问题固定点，且SWAN是我们的方法特例，通过精心选择的范数，提供了对其设计的更深入理解。然而，SWAN的白化/正交化步骤计算代价高昂，限制了其在大型LMs中的实用性。基于我们的原理性视角，我们开发了一种更高效、可扩展且实用的无状态优化器。我们的算法放宽了SWAN的性质，显著降低了计算成本，同时保持内存效率，使其适用于大规模模型训练。在多达10亿参数的LLaMA模型预训练实验中，我们的算法内存需求显著降低，比Adam快3倍，优于其他内存高效基线方法。

> Training large language models (LLMs) typically relies on adaptive optimizers like Adam (Kingma & Ba, 2015) which store additional state information to accelerate convergence but incur significant memory overhead. Recent efforts, such as SWAN (Ma et al., 2024) address this by eliminating the need for optimizer states while achieving performance comparable to Adam via a multi-step preprocessing procedure applied to instantaneous gradients. Motivated by the success of SWAN, we introduce a novel framework for designing stateless optimizers that normalizes stochastic gradients according to multiple norms. To achieve this, we propose a simple alternating scheme to enforce the normalization of gradients w.r.t these norms. We show that our procedure can produce, up to an arbitrary precision, a fixed-point of the problem, and that SWAN is a particular instance of our approach with carefully chosen norms, providing a deeper understanding of its design. However, SWAN's computationally expensive whitening/orthogonalization step limit its practicality for large LMs. Using our principled perspective, we develop of a more efficient, scalable, and practical stateless optimizer. Our algorithm relaxes the properties of SWAN, significantly reducing its computational cost while retaining its memory efficiency, making it applicable to training large-scale models. Experiments on pre-training LLaMA models with up to 1 billion parameters demonstrate a 3X speedup over Adam with significantly reduced memory requirements, outperforming other memory-efficient baselines.

[Arxiv](https://arxiv.org/abs/2502.06742)