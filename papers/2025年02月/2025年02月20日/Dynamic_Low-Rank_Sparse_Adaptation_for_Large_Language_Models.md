# 大型语言模型的动态低秩稀疏适应方法

发布时间：2025年02月20日

`LLM理论`

> Dynamic Low-Rank Sparse Adaptation for Large Language Models

# 摘要

> 尽管网络稀疏性在缓解大语言模型 (LLMs) 的部署压力方面表现出色，但其性能仍会显著下降。将低秩适配 (LoRA) 应用于稀疏 LLMs 的微调提供了一种直观的方法来应对这一困境，但它也存在以下缺点：1) 无法在训练后将 LoRA 权重集成到稀疏 LLMs 中，以及 2) 在高稀疏性比率下性能恢复不足。为此，我们提出了动态低秩稀疏适配 (LoSA)，这是一种在统一框架内将低秩适配无缝集成到 LLM 稀疏性中的创新方法，从而在不增加推理延迟的情况下提升稀疏 LLMs 的性能。具体而言，LoSA 在微调过程中基于相应的稀疏权重动态稀疏化 LoRA 的结果，确保 LoRA 模块可在训练后集成到稀疏 LLMs 中。此外，LoSA 利用表示互信息 (RMI) 作为指标来确定各层的重要性，从而在微调过程中高效地确定分层稀疏率。基于此，LoSA 根据分层重构误差的变化调整 LoRA 模块的秩，为每一层分配适当的微调，以减少密集和稀疏 LLMs 之间的输出差异。大量实验表明，LoSA 可以在短短几小时内有效提升稀疏 LLMs 的性能，而不会引入任何额外的推理负担。例如，LoSA 将稀疏 LLaMA-2-7B 的困惑度降低了 68.73，零样本准确率提高了 16.32%，在 CPU 上实现了 2.60 倍的速度提升，在 GPU 上实现了 2.23 倍的速度提升，仅需在单个 NVIDIA A100 80GB GPU 上进行 45 分钟的微调。代码可在 https://github.com/wzhuang-xmu/LoSA 获取。

> Despite the efficacy of network sparsity in alleviating the deployment strain of Large Language Models (LLMs), it endures significant performance degradation. Applying Low-Rank Adaptation (LoRA) to fine-tune the sparse LLMs offers an intuitive approach to counter this predicament, while it holds shortcomings include: 1) The inability to integrate LoRA weights into sparse LLMs post-training, and 2) Insufficient performance recovery at high sparsity ratios. In this paper, we introduce dynamic Low-rank Sparse Adaptation (LoSA), a novel method that seamlessly integrates low-rank adaptation into LLM sparsity within a unified framework, thereby enhancing the performance of sparse LLMs without increasing the inference latency. In particular, LoSA dynamically sparsifies the LoRA outcomes based on the corresponding sparse weights during fine-tuning, thus guaranteeing that the LoRA module can be integrated into the sparse LLMs post-training. Besides, LoSA leverages Representation Mutual Information (RMI) as an indicator to determine the importance of layers, thereby efficiently determining the layer-wise sparsity rates during fine-tuning. Predicated on this, LoSA adjusts the rank of the LoRA module based on the variability in layer-wise reconstruction errors, allocating an appropriate fine-tuning for each layer to reduce the output discrepancies between dense and sparse LLMs. Extensive experiments tell that LoSA can efficiently boost the efficacy of sparse LLMs within a few hours, without introducing any additional inferential burden. For example, LoSA reduced the perplexity of sparse LLaMA-2-7B by 68.73 and increased zero-shot accuracy by 16.32$\%$, achieving a 2.60$\times$ speedup on CPU and 2.23$\times$ speedup on GPU, requiring only 45 minutes of fine-tuning on a single NVIDIA A100 80GB GPU. Code is available at https://github.com/wzhuang-xmu/LoSA.

[Arxiv](https://arxiv.org/abs/2502.14816)