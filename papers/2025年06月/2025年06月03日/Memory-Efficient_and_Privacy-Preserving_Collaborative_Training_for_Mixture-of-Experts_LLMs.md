# 内存高效且隐私保护的专家混合型LLM协作训练方法

发布时间：2025年06月03日

`LLM理论` `人工智能` `隐私保护`

> Memory-Efficient and Privacy-Preserving Collaborative Training for Mixture-of-Experts LLMs

# 摘要

> 混合专家模型（MoE）因其成功应用于大型语言模型（LLMs）而备受关注。本研究提出了一种隐私保护协作混合专家模型（PC-MoE），该模型利用MoE架构的稀疏性，实现了一种内存高效的去中心化协作LLM训练方法。这种方法使多个GPU内存和数据资源有限的参与方能够共同训练出比各自单独训练更强大的LLMs。同时，通过将训练数据以及部分前向传播信号和梯度保留在各参与方本地，该方法保护了各参与方的训练数据隐私。设计上，PC-MoE将分布式计算的优势与强大的保密性保证相结合。与大多数隐私保护方案不同，这些方案通常以降低任务准确性为代价来换取保密性，我们的框架打破了这一权衡：在七个流行的LLM基准测试中，其性能和收敛速度几乎与完全集中化的模型相匹配（有时甚至超越），同时实现了近70%的GPU显存峰值减少，并且完全抵御了重建攻击。

> Mixture-of-Experts (MoE) has been gaining popularity due to its successful adaptation to large language models (LLMs). In this work, we introduce Privacy-preserving Collaborative Mixture-of-Experts (PC-MoE), which leverages the sparsity of the MoE architecture for memory-efficient decentralized collaborative LLM training, enabling multiple parties with limited GPU-memory and data resources to collectively train more capable LLMs than they could achieve individually. At the same time, this approach protects training data privacy of each participant by keeping training data, as well as parts of the forward pass signal and gradients locally within each party. By design, PC-MoE synergistically combines the strengths of distributed computation with strong confidentiality assurances. Unlike most privacy-preserving schemes, which pay for confidentiality with lower task accuracy, our framework breaks that trade-off: across seven popular LLM benchmarks, it almost matches (and sometimes exceeds) the performance and convergence rate of a fully centralized model, enjoys near 70% peak GPU RAM reduction, while being fully robust against reconstruction attacks.

[Arxiv](https://arxiv.org/abs/2506.02965)