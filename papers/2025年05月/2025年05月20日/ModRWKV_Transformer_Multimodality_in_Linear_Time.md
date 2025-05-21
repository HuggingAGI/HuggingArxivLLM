# # ModRWKV：Transformer 多模态线性时间实现

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了现代RNN架构在多模态大型语言模型中的应用，提出了一种新的框架ModRWKV，并进行了详细的实验和分析。研究集中在模型架构的设计和优化上，属于LLM理论层面的探讨。` `人工智能`

> ModRWKV: Transformer Multimodality in Linear Time

# 摘要

> 目前，多模态研究主要基于具有二次复杂度的Transformer架构的大型语言模型（LLMs）。尽管循环神经网络（RNN）等线性模型在推理成本上具有优势，但其应用主要局限于纯文本模态。本研究旨在探索现代RNN架构在多模态环境中的潜力。我们提出了一种名为ModRWKV的解耦多模态框架，其基于RWKV7架构作为其大型语言模型的主干，并通过动态可适应的异构模态编码器实现多源信息融合。我们为ModRWKV设计了极其轻量级的多模态模块，并通过大量实验发现了一种在性能和计算效率之间达到最佳平衡的配置。ModRWKV利用RWKV7 LLM的预训练权重进行初始化，显著加速了多模态训练。与不同预训练检查点的比较实验进一步证明，这种初始化在增强模型理解多模态信号的能力方面起着关键作用。通过广泛的实验支持，我们得出结论：现代RNN架构在多模态大型语言模型（MLLMs）领域为Transformer架构提供了一种可行的替代方案。此外，我们通过系统性探索确定了ModRWKV架构的最优配置。

> Currently, most multimodal studies are based on large language models (LLMs) with quadratic-complexity Transformer architectures. While linear models like RNNs enjoy low inference costs, their application has been largely limited to the text-only modality. This work explores the capabilities of modern RNN architectures in multimodal contexts. We propose ModRWKV-a decoupled multimodal framework built upon the RWKV7 architecture as its LLM backbone-which achieves multi-source information fusion through dynamically adaptable heterogeneous modality encoders. We designed the multimodal modules in ModRWKV with an extremely lightweight architecture and, through extensive experiments, identified a configuration that achieves an optimal balance between performance and computational efficiency. ModRWKV leverages the pretrained weights of the RWKV7 LLM for initialization, which significantly accelerates multimodal training. Comparative experiments with different pretrained checkpoints further demonstrate that such initialization plays a crucial role in enhancing the model's ability to understand multimodal signals. Supported by extensive experiments, we conclude that modern RNN architectures present a viable alternative to Transformers in the domain of multimodal large language models (MLLMs). Furthermore, we identify the optimal configuration of the ModRWKV architecture through systematic exploration.

[Arxiv](https://arxiv.org/abs/2505.14505)