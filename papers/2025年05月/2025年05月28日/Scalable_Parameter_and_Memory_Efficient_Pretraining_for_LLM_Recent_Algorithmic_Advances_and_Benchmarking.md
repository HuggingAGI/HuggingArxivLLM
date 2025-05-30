# # 高扩展性参数与内存高效的LLM预训练：近期算法进展与基准测试探索

发布时间：2025年05月28日

`LLM理论` `人工智能` `计算机科学`

> Scalable Parameter and Memory Efficient Pretraining for LLM: Recent Algorithmic Advances and Benchmarking

# 摘要

> 凭借其在多领域多样化任务中的卓越能力，大型语言模型（LLMs）以前所未有的速度增长，某些近期模型已拥有万亿级别参数。这种增长伴随着训练和微调过程中内存与计算资源的巨大挑战。为应对这些挑战，人们探索了多种方法，如LoRA等。尽管这些方法在微调方面表现出色，但预训练中的应用却面临更大挑战，因为预训练需要处理海量数据集。

我们希望回答以下问题：参数高效或内存高效的方法能否在预训练中提升效率，同时达到与全模型训练相当的性能？性能差距能否缩小？为此，本研究的贡献如下。

（1）我们首先进行了一项全面的调查，总结了高效预训练的最新方法。

（2）我们对几种具有代表性的内存高效预训练方法进行了基准评估，以全面评估它们在不同模型规模下的性能。我们观察到，通过选择合适的优化器和超参数，全秩训练确实如预期般表现最佳。我们还发现，在低秩方法中引入高秩更新是提升其性能的关键。

（3）最后，我们提出了两种实用技术，即权重重构和动量重置，以增强高效预训练方法的性能。我们发现，将这些技术应用于低秩方法（在1B规模模型中）可以实现比GaLore和Fira等流行内存高效算法更低的困惑度，同时内存使用量减少约25%。

> Fueled by their remarkable ability to tackle diverse tasks across multiple domains, large language models (LLMs) have grown at an unprecedented rate, with some recent models containing trillions of parameters. This growth is accompanied by substantial computational challenges, particularly regarding the memory and compute resources required for training and fine-tuning. Numerous approaches have been explored to address these issues, such as LoRA. While these methods are effective for fine-tuning, their application to pre-training is significantly more challenging due to the need to learn vast datasets. Motivated by this issue, we aim to address the following questions: Can parameter- or memory-efficient methods enhance pre-training efficiency while achieving performance comparable to full-model training? How can the performance gap be narrowed? To this end, the contributions of this work are the following. (1) We begin by conducting a comprehensive survey that summarizes state-of-the-art methods for efficient pre-training. (2) We perform a benchmark evaluation of several representative memory efficient pre-training approaches to comprehensively evaluate their performance across model sizes. We observe that with a proper choice of optimizer and hyperparameters, full-rank training delivers the best performance, as expected. We also notice that incorporating high-rank updates in low-rank approaches is the key to improving their performance. (3) Finally, we propose two practical techniques, namely weight refactorization and momentum reset, to enhance the performance of efficient pre-training methods. We observe that applying these techniques to the low-rank method (on a 1B model) can achieve a lower perplexity than popular memory efficient algorithms such as GaLore and Fira, while simultaneously using about 25% less memory.

[Arxiv](https://arxiv.org/abs/2505.22922)