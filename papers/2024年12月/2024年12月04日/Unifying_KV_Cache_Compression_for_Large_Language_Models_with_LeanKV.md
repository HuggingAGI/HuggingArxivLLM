# 用 LeanKV 统一大型语言模型的 KV 缓存压缩

发布时间：2024年12月04日

`LLM应用` `语言模型` `缓存压缩`

> Unifying KV Cache Compression for Large Language Models with LeanKV

# 摘要

> 大型语言模型（LLMs）性能卓越，然而因其巨大的内存需求致使服务成本高昂，键值（KV）缓存便是主要的瓶颈所在。现有的 KV 缓存压缩手段，像量化和剪枝等，存在诸多局限，比如对键和值的同等处理以及在注意力头之间的静态内存分配。为解决这些难题，我们推出了 LeanKV，这是一个统一的 KV 缓存压缩框架，凭借三项创新在不折损准确性的前提下提升了 LLM 的服务效率：（1）异质 KV 量化，其以高于值的精度存储键，以体现键对注意力计算的更大作用；（2）每个头的动态稀疏性，依据每个头和每次请求的令牌重要性来分配内存；（3）统一的 KV 压缩，将混合精度量化和选择性剪枝相融合，实现模型准确性与内存效率的平衡。为有效支持这些技术，LeanKV 引入了系统优化，涵盖统一分页和 GPU 上的并行内存管理。在 vLLM 上应用时，LeanKV 能将 KV 缓存压缩 3.0 至 5.0 倍且不损失准确性，最多压缩 11.0 倍且准确性损失低于 5%，使吞吐量提升 1.9 至 2.5 倍，最多达 6.9 倍。

> Large language models (LLMs) demonstrate exceptional performance but incur high serving costs due to substantial memory demands, with the key-value (KV) cache being a primary bottleneck. Existing KV cache compression methods, including quantization and pruning, struggle with limitations such as uniform treatment of keys and values and static memory allocation across attention heads. To address these challenges, we introduce LeanKV, a unified KV cache compression framework that enhances LLM serving efficiency without compromising accuracy through three innovations: (1) Hetero-KV quantization, which stores keys at a higher precision than values to reflect their greater impact on attention computations; (2) per-head dynamic sparsity, which allocates memory based on token importance per head and per request; and (3) unified KV compression, integrating mixed-precision quantization and selective pruning to enable a smooth tradeoff between model accuracy and memory efficiency. To efficiently support these techniques, LeanKV introduces systems optimizations including unified paging and on-GPU parallel memory management. Implemented on vLLM, LeanKV compresses the KV cache by $3.0\times$ to $5.0\times$ without accuracy loss and up to $11.0\times$ with under 5% accuracy loss, enhancing throughput by $1.9\times$ to $2.5\times$, and up to $6.9\times$.

[Arxiv](https://arxiv.org/abs/2412.03131)