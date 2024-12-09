# Flash 通信：化解快速大型语言模型推理中的张量并行化瓶颈

发布时间：2024年12月06日

`LLM应用` `语言模型` `通信技术`

> Flash Communication: Reducing Tensor Parallelization Bottleneck for Fast Large Language Model Inference

# 摘要

> 大型语言模型的规模持续增长，这使得实现快速推理必须采用利用多维并行性的分布式解决方案，计算负载会分布在诸如 GPU 集群等各类加速器上。但这种方式常常带来巨大的通信开销，在带宽有限的设备上尤其如此。在本文中，我们推出了“Flash 通信”，这是一种创新的低位压缩技术，旨在缓解推理时的张量并行通信瓶颈。我们的方法使节点内通信速度大幅提升 3 倍有余，将“首次令牌时间”缩短 2 倍，且几乎不影响模型的准确性。针对各种最新的大型语言模型开展的大量实验，验证了我们方法的有效性。

> The ever-increasing sizes of large language models necessitate distributed solutions for fast inference that exploit multi-dimensional parallelism, where computational loads are split across various accelerators such as GPU clusters. However, this approach often introduces significant communication overhead, especially on devices with limited bandwidth. In this paper, we introduce \emph{Flash Communication}, a novel low-bit compression technique designed to alleviate the tensor-parallelism communication bottleneck during inference. Our method substantially boosts intra-node communication speed by more than 3x and reduces the \emph{time-to-first-token} by 2x, with nearly no sacrifice in model accuracy. Extensive experiments on various up-to-date LLMs demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2412.04964)