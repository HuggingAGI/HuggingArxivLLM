# 突破内存瓶颈：梯度小波变换助力LLMs训练

发布时间：2025年01月13日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在训练过程中面临的内存挑战，并提出了一种新的内存高效方法——梯度小波变换（GWT）。该研究聚焦于优化LLMs的训练过程，属于对LLMs理论层面的改进和优化，因此应归类为LLM理论。` `优化算法`

> Breaking Memory Limits: Gradient Wavelet Transform Enhances LLMs Training

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现卓越，但其庞大的参数数量在训练时带来了巨大的内存挑战，尤其是在使用Adam等内存密集型优化器时。现有的内存高效算法多依赖于奇异值分解投影或权重冻结等技术，虽然这些方法能缓解内存压力，但与全秩更新相比，效果往往不尽如人意。本文提出了一种超越低秩训练的内存高效方法——梯度小波变换（GWT），通过将小波变换应用于梯度，大幅减少了优化器状态的内存需求。我们证明，GWT能无缝集成到内存密集型优化器中，在不牺牲性能的前提下实现高效训练。通过大量预训练和微调实验，GWT在内存使用和训练性能上均超越了现有的内存高效优化器和全秩方法，达到了业界领先水平。

> Large language models (LLMs) have shown impressive performance across a range of natural language processing tasks. However, their vast number of parameters introduces significant memory challenges during training, particularly when using memory-intensive optimizers like Adam. Existing memory-efficient algorithms often rely on techniques such as singular value decomposition projection or weight freezing. While these approaches help alleviate memory constraints, they generally produce suboptimal results compared to full-rank updates. In this paper, we investigate the memory-efficient method beyond low-rank training, proposing a novel solution called Gradient Wavelet Transform (GWT), which applies wavelet transforms to gradients in order to significantly reduce the memory requirements for maintaining optimizer states. We demonstrate that GWT can be seamlessly integrated with memory-intensive optimizers, enabling efficient training without sacrificing performance. Through extensive experiments on both pre-training and fine-tuning tasks, we show that GWT achieves state-of-the-art performance compared with advanced memory-efficient optimizers and full-rank approaches in terms of both memory usage and training performance.

[Arxiv](https://arxiv.org/abs/2501.07237)