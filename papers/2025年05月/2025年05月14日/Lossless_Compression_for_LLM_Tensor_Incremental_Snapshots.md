# # 标题
无损压缩在大型语言模型张量增量快照中的应用

发布时间：2025年05月14日

`LLM应用

理由：这篇论文讨论了如何优化大型语言模型（LLMs）训练过程中的检查点保存机制，以减少数据传输和存储的需求。它专注于压缩技术的应用，旨在提高训练效率，属于LLM应用的范畴。` `人工智能` `计算机科学`

> Lossless Compression for LLM Tensor Incremental Snapshots

# 摘要

> 在大型语言模型 (LLMs) 的训练过程中，张量数据会被定期保存为检查点 (checkpoint) 到持久化存储中，以便在发生故障时恢复之前的工作。即使使用 bfloat16 等低精度表示，每次检查点需要复制的数据量也常常达到数百千兆字节。此外，数据必须在网络上传输并在下一个周期开始前写入存储系统。

为了构建一个优化的检查点解决方案，我们对检查点数据进行了实验分析，旨在设计出一种能够最大化无损压缩使用、从而减少数据量的方法。我们研究了模型训练过程中张量数据及其可压缩性如何演变，并评估了现有通用压缩引擎（结合已知的数据优化技术，如字节分组和增量增量压缩）的效力。

基于我们的分析，我们构建了一个有效的压缩解决方案，称为语言模型压缩器 (LMC)，它基于字节分组和霍夫曼编码。与最佳替代方案 (BZ2) 相比，LMC 提供了更高的压缩性能，但压缩所需的时间减少了几个数量级。我们的 16 核并行实现可以达到 2.78 GiB/s 的压缩吞吐量和 3.76 GiB/s 的解压缩吞吐量。这种性能的提升减少了所需的 CPU 资源，并为在下一个周期开始前将数据复制到存储系统提供了更多时间，从而允许更高频率的检查点。

> During the training of Large Language Models (LLMs), tensor data is periodically "checkpointed" to persistent storage to allow recovery of work done in the event of failure. The volume of data that must be copied during each checkpoint, even when using reduced-precision representations such as bfloat16, often reaches hundreds of gigabytes. Furthermore, the data must be moved across a network and written to a storage system before the next epoch occurs. With a view to ultimately building an optimized checkpointing solution, this paper presents experimental analysis of checkpoint data used to derive a design that maximizes the use of lossless compression to reduce the volume of data. We examine how tensor data and its compressibility evolve during model training and evaluate the efficacy of existing common off-the-shelf general purpose compression engines combined with known data optimization techniques such as byte-grouping and incremental delta compression.
  Leveraging our analysis we have built an effective compression solution, known as Language Model Compressor (LMC), which is based on byte-grouping and Huffman encoding. LMC offers more compression performance than the best alternative (BZ2) but with an order-of-magnitude reduction in the time needed to perform the compression. We show that a 16-core parallel implementation of LMC can attain compression and decompression throughput of 2.78 GiB/s and 3.76 GiB/s respectively. This increase in performance ultimately reduces the CPU resources needed and provides more time to copy the data to the storage system before the next epoch thus allowing for higher-frequency checkpoints.

[Arxiv](https://arxiv.org/abs/2505.09810)