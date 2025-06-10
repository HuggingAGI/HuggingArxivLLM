# # 正交等价变换驱动的LLM再参数化训练方法

发布时间：2025年06月09日

`LLM理论` `人工智能`

> Reparameterized LLM Training via Orthogonal Equivalence Transformation

# 摘要

> 尽管大型语言模型（LLMs）正在引领人工智能的快速发展，但如何高效可靠地训练这些模型仍是当前研究的重中之重。为此，我们提出了一种名为POET的全新重新参数化训练算法，通过正交等价变换优化神经元。POET的核心创新在于为每个神经元引入两个可学习的正交矩阵和一个固定随机权重矩阵。得益于其对权重矩阵谱性质的可证明保护，POET不仅能够稳定优化目标函数，还能显著提升模型的泛化能力。我们进一步开发了高效的近似方法，使POET在训练大规模神经网络时更加灵活和可扩展。通过大量实验，我们验证了POET在训练大型语言模型时的卓越效果和强大扩展性。

> While large language models (LLMs) are driving the rapid advancement of artificial intelligence, effectively and reliably training these large models remains one of the field's most significant challenges. To address this challenge, we propose POET, a novel reParameterized training algorithm that uses Orthogonal Equivalence Transformation to optimize neurons. Specifically, POET reparameterizes each neuron with two learnable orthogonal matrices and a fixed random weight matrix. Because of its provable preservation of spectral properties of weight matrices, POET can stably optimize the objective function with improved generalization. We further develop efficient approximations that make POET flexible and scalable for training large-scale neural networks. Extensive experiments validate the effectiveness and scalability of POET in training LLMs.

[Arxiv](https://arxiv.org/abs/2506.08001)