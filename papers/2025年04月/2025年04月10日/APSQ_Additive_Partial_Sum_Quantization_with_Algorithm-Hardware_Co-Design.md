# **APSQ：算法与硬件协同设计的累加部分和量化方法**

发布时间：2025年04月10日

`其他` `人工智能` `模型压缩`

> APSQ: Additive Partial Sum Quantization with Algorithm-Hardware Co-Design

# 摘要

> 深度神经网络加速器（DNN accelerators）在模型压缩和专用数据流技术的推动下取得了显著进展。然而，采用输入/权重静止数据流的架构由于频繁访问高精度部分和（PSUMs），导致内存需求过高。传统压缩策略通常忽视了PSUM量化，而这一部分可能占用了69%的功耗。本研究提出了一种新颖的累加式部分和量化（APSQ）方法，将PSUM累加过程无缝融入量化框架。我们进一步提出了一种结合APSQ与可重构架构增强的PSUM量化分组策略。实验结果表明，APSQ在BERT、Segformer和EfficientViT模型上的NLP和CV任务中实现了几乎无损压缩，同时将PSUM压缩至INT8。这一方法显著降低了能源成本，降幅达28-87%。在LLaMA2-7B模型上的扩展实验进一步验证了APSQ在大型语言模型中的潜力。代码可从https://github.com/Yonghao-Tan/APSQ获取。

> DNN accelerators, significantly advanced by model compression and specialized dataflow techniques, have marked considerable progress. However, the frequent access of high-precision partial sums (PSUMs) leads to excessive memory demands in architectures utilizing input/weight stationary dataflows. Traditional compression strategies have typically overlooked PSUM quantization, which may account for 69% of power consumption. This study introduces a novel Additive Partial Sum Quantization (APSQ) method, seamlessly integrating PSUM accumulation into the quantization framework. A grouping strategy that combines APSQ with PSUM quantization enhanced by a reconfigurable architecture is further proposed. The APSQ performs nearly lossless on NLP and CV tasks across BERT, Segformer, and EfficientViT models while compressing PSUMs to INT8. This leads to a notable reduction in energy costs by 28-87%. Extended experiments on LLaMA2-7B demonstrate the potential of APSQ for large language models. Code is available at https://github.com/Yonghao-Tan/APSQ.

[Arxiv](https://arxiv.org/abs/2505.03748)