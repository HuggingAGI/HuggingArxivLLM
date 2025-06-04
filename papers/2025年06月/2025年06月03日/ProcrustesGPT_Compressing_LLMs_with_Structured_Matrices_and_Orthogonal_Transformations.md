# ProcrustesGPT: 基于结构化矩阵和正交变换压缩大型语言模型

发布时间：2025年06月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的参数压缩方法，通过结构化矩阵和正交变换来优化模型结构，属于理论层面的研究，旨在提升模型的效率和性能。` `模型压缩`

> ProcrustesGPT: Compressing LLMs with Structured Matrices and Orthogonal Transformations

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现卓越，但其运行需要大量计算和内存资源。结构化矩阵表示方法为减少模型参数数量提供了新思路。然而，直接用结构化矩阵替代预训练模型的权重矩阵而不进行微调，目前尚不现实。我们发现，LLMs的输出在权重矩阵的特定正交变换下保持不变，这一特性可用于识别显著提升权重压缩性的变换。该方法适用于多种支持高效投影操作的结构化矩阵。代码已开源，地址为https://github.com/GrishKate/ProcrustesGPT。

> Large language models (LLMs) demonstrate impressive results in natural language processing tasks but require a significant amount of computational and memory resources. Structured matrix representations are a promising way for reducing the number of parameters of these models. However, it seems unrealistic to expect that weight matrices of pretrained models can be accurately represented by structured matrices without any fine-tuning. To overcome this issue, we utilize the fact that LLM output is invariant under certain orthogonal transformations of weight matrices. This insight can be leveraged to identify transformations that significantly improve the compressibility of weights within structured classes. The proposed approach is applicable to various types of structured matrices that support efficient projection operations. Code is available at https://github.com/GrishKate/ProcrustesGPT

[Arxiv](https://arxiv.org/abs/2506.02818)