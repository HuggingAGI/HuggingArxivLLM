# IterNorm：快速的迭代归一化

发布时间：2024年12月06日

`LLM理论` `语言模型`

> IterNorm: Fast Iterative Normalization

# 摘要

> 基于 Transformer 的大型语言模型属于内存受限型模型，其运行依赖大量几乎不重复使用的数据。所以，主机与加速器间的数据移动很可能决定了总耗时。层归一化是 Transformer 模型的关键工作负载之一，位于多头注意力和前馈网络块之后。为减少数据移动，层归一化需在与矩阵乘法引擎相同的芯片上执行。为此，我们为 1D 输入推出了一种迭代 L2 归一化方法（IterNorm），能在五个迭代步骤内快速收敛至稳态解，精度颇高，在 OPT 模型所用嵌入长度的九个情形中，FP32 有六个情形、BFloat16 有五个情形的表现优于快速平方根倒数算法。在 32/28nm CMOS 中实现时，IterNorm 宏可对$d$维向量（其中$64 \leq d \leq 1024$）进行归一化，在 100MHz/1.05V 下延迟为 112 - 227 个周期。

> Transformer-based large language models are a memory-bound model whose operation is based on a large amount of data that are marginally reused. Thus, the data movement between a host and accelerator likely dictates the total wall-clock time. Layer normalization is one of the key workloads in the transformer model, following each of multi-head attention and feed-forward network blocks. To reduce data movement, layer normalization needs to be performed on the same chip as the matrix-matrix multiplication engine. To this end, we introduce an iterative L2-normalization method for 1D input (IterNorm), ensuring fast convergence to the steady-state solution within five iteration steps and high precision, outperforming the fast inverse square root algorithm in six out of nine cases for FP32 and five out of nine for BFloat16 across the embedding lengths used in the OPT models. Implemented in 32/28nm CMOS, the IterNorm macro normalizes $d$-dimensional vectors, where $64 \leq d \leq 1024$, with a latency of 112-227 cycles at 100MHz/1.05V.

[Arxiv](https://arxiv.org/abs/2412.04778)