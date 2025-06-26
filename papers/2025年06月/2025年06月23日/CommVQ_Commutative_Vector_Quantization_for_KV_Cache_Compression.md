# CommVQ: 一种用于键值缓存压缩的交换向量量化方法

发布时间：2025年06月23日

`LLM应用` `AI模型优化` `计算机体系结构`

> CommVQ: Commutative Vector Quantization for KV Cache Compression

# 摘要

> 大型语言模型（LLMs）在需要长上下文的应用中使用越来越多，但随着上下文长度增加，KV缓存常成为GPU内存瓶颈。为此，我们提出了一种可交换向量量化方法（CommVQ），以大幅减少长上下文LLM推理的内存占用。我们首先引入了一种基于轻量化编码器和码本的加法量化方法来压缩KV缓存，该缓存可通过简单的矩阵乘法进行解码。为了进一步降低解码过程的计算成本，我们将码本设计为与旋转位置编码（RoPE）可交换，并使用期望最大化（EM）算法对其进行训练。这使得解码能够高效地融入自注意力机制。我们的方法通过加法量化实现了高精度，并借助RoPE可交换码本实现了低计算开销。在长上下文基准测试和GSM8K上的实验表明，与现有的KV缓存量化方法相比，我们的方法在2位量化下可将FP16 KV缓存大小减少87.5%，并实现更优性能。值得注意的是，该方法还支持1位KV缓存量化且仅带来极小的精度损失，使LLaMA-3.1 8B模型能够在单个RTX 4090 GPU上运行128K上下文长度。源代码已开源：https://github.com/UMass-Embodied-AGI/CommVQ。

> Large Language Models (LLMs) are increasingly used in applications requiring long context lengths, but the key-value (KV) cache often becomes a memory bottleneck on GPUs as context grows. To address this, we propose Commutative Vector Quantization (CommVQ) to significantly reduce memory usage for long-context LLM inference. We first introduce additive quantization with a lightweight encoder and codebook to compress the KV cache, which can be decoded via simple matrix multiplication. To further reduce computational costs during decoding, we design the codebook to be commutative with Rotary Position Embedding (RoPE) and train it using an Expectation-Maximization (EM) algorithm. This enables efficient integration of decoding into the self-attention mechanism. Our approach achieves high accuracy with additive quantization and low overhead via the RoPE-commutative codebook. Experiments on long-context benchmarks and GSM8K show that our method reduces FP16 KV cache size by 87.5% with 2-bit quantization, while outperforming state-of-the-art KV cache quantization methods. Notably, it enables 1-bit KV cache quantization with minimal accuracy loss, allowing a LLaMA-3.1 8B model to run with a 128K context length on a single RTX 4090 GPU. The source code is available at: https://github.com/UMass-Embodied-AGI/CommVQ.

[Arxiv](https://arxiv.org/abs/2506.18879)