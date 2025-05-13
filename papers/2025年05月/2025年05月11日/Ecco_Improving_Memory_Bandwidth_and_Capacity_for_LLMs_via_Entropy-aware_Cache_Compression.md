# Ecco：熵感知缓存压缩技术助力提升LLMs内存带宽与容量

发布时间：2025年05月11日

`LLM应用

摘要讨论了大型语言模型（LLMs）在资源受限环境中的应用限制，并提出了一种优化技术（Ecco）来提高其效率和性能，这属于LLM的应用层面的优化。` `人工智能` `计算机系统`

> Ecco: Improving Memory Bandwidth and Capacity for LLMs via Entropy-aware Cache Compression

# 摘要

> 大型语言模型（LLMs）在人工智能领域展现了强大的变革能力，但其应用因内存和计算需求巨大而受限，特别是在资源有限的环境中。量化技术作为关键解决方案，通过降低数据精度来提升效率。然而，现有方法常面临高运行开销和精度下降的问题。为解决这些挑战，我们提出Ecco——一种专为LLMs设计的基于熵的缓存压缩技术。Ecco结合分组和非均匀量化，利用预定义的共享k均值模式和霍夫曼编码，挖掘LLM缓存数据的熵特性。针对传统霍夫曼编码的低效问题，我们创新性地设计了一种并行霍夫曼解码流程，采用多级流水线，将延迟降低两个数量级，实现与GPU L2缓存相当的吞吐量。全面评估显示，Ecco在速度上较AWQ和SmoothQuant框架分别提升2.9倍和1.9倍，较Olive加速器提升2.4倍，同时内存容量增加近4倍，且保持先进LLM精度。这些结果证明了我们的熵基缓存压缩技术在提升LLM性能和效率方面的有效性，为部署大规模AI模型铺平了道路。

> Large language models (LLMs) have demonstrated transformative capabilities across diverse artificial intelligence applications, yet their deployment is hindered by substantial memory and computational demands, especially in resource-constrained environments. Quantization techniques have emerged as a critical solution, reducing data precision to enhance memory and computational efficiency. However, existing methods often suffer from high runtime overheads and potential accuracy degradation. To address these challenges, we propose Ecco, an entropy-based cache compression technique tailored for LLMs. Ecco combines group-wise and non-uniform quantization with pre-defined shared k-means patterns and Huffman coding to exploit the inherent entropy characteristics of LLM cache data. Recognizing the inefficiencies of traditional Huffman coding in terms of parallelism and latency, we introduce a novel parallel Huffman-based decoding process with a multi-stage pipeline design, reducing latency by two orders of magnitude and achieving throughput comparable to GPU L2 caches. Comprehensive evaluations demonstrate that Ecco achieves an up to 2.9$\times$ and 1.9$\times$ speedup over the state-of-the-art AWQ and SmoothQuant framework, 2.4$\times$ over the Olive accelerator, all while increasing memory capacity by nearly 4$\times$ and maintaining state-of-the-art LLM accuracy. These results underscore the effectiveness of our entropy-based cache compression in enhancing LLM performance and efficiency, paving the way for more deployable large-scale AI models.

[Arxiv](https://arxiv.org/abs/2505.06901)